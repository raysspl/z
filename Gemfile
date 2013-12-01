source 'https://rubygems.org'

ruby '2.0.0'
gem 'rails', '4.0.0'
gem 'jquery-rails'
gem 'sass-rails', '~> 4.0.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'turbolinks'
gem 'jbuilder', '~> 1.2'	
gem 'bootstrap-sass', '~> 2.3.2.1'
gem 'unicorn'

group :production do
	gem 'pg'
	gem 'rails_12factor'
	gem 'unicorn'
	gem 'rails_log_stdout', github: 'heroku/rails_log_stdout'
end

group :development, :test do
	gem 'sqlite3'
end

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]