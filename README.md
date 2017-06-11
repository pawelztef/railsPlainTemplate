== README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version
    ruby 2.3.1p112
    rails 4.2.5

* System dependencies
    Ubuntu 16.04

* Development Configuration

  # extra gems and their configs
    
  gem 'letter opener'
    in config/environments/development.rb
    config.action_mailer.delivery_method = :letter_opener

  gem 'guard-livereload', '~> 2.5', require: false
    $ guard init livereload
    custom Guardfile configuration

  gem 'byebug'
  gem 'rack-mini-profiler'
  gem 'rack-livereload'
  gem 'pry-rails'
  gem 'pry-byebug' 
  gem 'faker'
  gem 'simple_form'
    rails g simple_form:install --bootstrap

  # turning off a tests generation
  config.generators do |g|
    g.test_framework  nil #to skip test framework
  end


* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions




