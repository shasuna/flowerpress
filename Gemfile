source "https://rubygems.org"

ruby "3.3.4"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 7.1.3", ">= 7.1.3.4"

# The original asset pipeline for Rails [https://github.com/rails/sprockets-rails]
gem "sprockets-rails"

# Use postgresql as the database for Active Record
gem "pg", "~> 1.1"

# Use the Puma web server [https://github.com/puma/puma]
gem "puma", ">= 5.0"

# ActiveStorage Image Processing
gem "image_processing", ">= 1.2"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ windows jruby ]

# General

gem 'bcrypt', '~> 3.1.7'

group :test do
  gem "capybara"
  gem 'simplecov', require: false
end

group :development, :test do
  gem 'pry-rails'
  gem 'rspec-rails', '~> 6.1.0'
end