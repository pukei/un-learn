source 'https://rubygems.org'
ruby File.read('.ruby-version').rstrip

gem 'rails', '4.2.3'

gem 'coffee-rails', '~> 4.1.0'
gem 'jbuilder', '~> 2.0'

gem 'devise'

gem 'jquery-rails'
gem 'sass-rails', '~> 5.0'
gem 'sdoc', '~> 0.4.0', group: :doc
gem 'turbolinks'
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby


# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

gem 'letter_opener', group: :development

group :development, :test do
  gem 'awesome_print'
  gem 'byebug'
  gem 'spring'
	gem 'sqlite3'
  gem 'web-console', '~> 2.0'
end

group :production do
	gem 'pg'
end

group :test do
	gem 'simplecov'
	gem 'rubocop'
end
