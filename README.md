# petadmin with RAILS

# A small project with fae, sidekiq and redis.

* docker-compose run --rm app bundle exec rake db:create
* docker-compose run --rm app bundle exec rake db:migrate
* docker-compose run --rm app bundle exec rake fae:seed_db
* docker-compose Build
* docker-compose up
