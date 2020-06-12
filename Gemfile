source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.4'

gem 'rails', '~> 5.2.4', '>= 5.2.4.3'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.11'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'bootstrap-sass', '~> 3.4.1'
gem 'sassc-rails', '>= 2.1.0'
gem 'jquery-rails'
gem 'faker', :git => 'https://github.com/faker-ruby/faker.git', :branch => 'master'
gem 'oj'
gem 'oj_mimic_json', '~> 1.0', '>= 1.0.1'

group :development, :test do
  gem 'factory_bot'
  gem 'rspec-json_expectations'
  gem 'rspec-rails', '~> 4.0.0'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
end

group :test do
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'chromedriver-helper'
  gem 'db-query-matchers'
  gem 'json_spec', '~> 1.1', '>= 1.1.5'
  gem 'launchy', '~> 2.5'
  gem 'shoulda-matchers', '~> 4.3'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]