# redmine

Steps:

rake db:create
rake db:migrate
bundle exec rake generate_secret_token
bundle exec rake redmine:load_default_data