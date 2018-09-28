source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.4.0'

gem 'bootsnap', '>= 1.1.0', require: false
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.11'
gem 'rails', '~> 5.2.1'
gem 'turbolinks', '~> 5'

# Front-end related gems
gem 'coffee-rails'
gem 'jquery-rails'
gem 'sass-rails'
gem 'uglifier'

group :development, :test do
  gem 'factory_bot_rails'
  gem 'guard-rspec'
  gem 'guard-spring'
  gem 'pdf-inspector'
  gem 'pry'
  gem 'pry-byebug'
  gem 'pry-rails'
  gem 'rspec-core'
  gem 'rspec-rails'
  gem 'shoulda-matchers'
  gem 'sinatra', require: false
  gem 'sinatra-contrib', require: false
  gem 'spring-commands-rspec'
  gem 'timecop'
end

group :development do
  gem 'awesome_print'
  gem 'better_errors'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console', '>= 3.3.0'
  gem 'xray-rails'
end

group :test do
  gem 'capybara', '>= 2.15'
  gem 'chromedriver-helper'
  gem 'selenium-webdriver'
end
