# recipe-app-api
api project
commends docker-compose build
docker-compose run --rm app sh -c "flake8"
docker-compose run --rm app sh -c "django-admin startproject app ."

docker-compose up

git commit -am "Added GitHub Actions."
git push origin