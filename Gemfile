source 'https://rubygems.org'

ruby '2.7.0'

##-- base gems for rails --##
gem 'rack-cors', require: 'rack/cors'
gem 'rails'
# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', require: false

##-- rails application helper gems --##
gem 'acts-as-taggable-on'
gem 'attr_extras'
gem 'browser'
gem 'hashie'
gem 'jbuilder'
gem 'kaminari'
gem 'responders'
gem 'rest-client'
gem 'telephone_number'
gem 'time_diff'
gem 'tzinfo-data'
gem 'valid_email2'
gem 'paper_trail'
# gem "cancan"
# compress javascript config.assets.js_compressor
gem 'uglifier'
##-- used for single column multiple binary flags in notification settings/feature flagging --##
gem 'flag_shih_tzu'
# Random name generator for user names
gem 'haikunator'
# Template parsing safely
gem 'liquid'
# Parse Markdown to HTML
gem 'commonmarker'
# Validate Data against JSON Schema
gem 'json_schemer'

##-- for active storage --##
gem 'aws-sdk-s3', require: false
gem 'azure-storage-blob', require: false
gem 'google-cloud-storage', require: false
gem 'mini_magick'

##-- gems for database --#
gem 'groupdate'
gem 'pg'
gem 'redis'
gem 'redis-namespace'
gem 'redis-rack-cache'
# super fast record imports in bulk
gem 'activerecord-import'

##--- gems for server & infra configuration ---##
gem 'dotenv-rails'
gem 'foreman'
gem 'puma'
gem 'webpacker', '~> 5.x'
# metrics on heroku
gem 'barnes'

##--- gems for authentication & authorization ---##
gem 'devise'
gem 'devise-secure_password', '~> 2.0'
gem 'devise_token_auth'
# authorization
gem 'jwt'
gem 'pundit'
# super admin
gem 'administrate'

##--- gems for pubsub service ---##
# https://karolgalanciak.com/blog/2019/11/30/from-activerecord-callbacks-to-publish-slash-subscribe-pattern-and-event-driven-design/
gem 'wisper', '2.0.0'

##--- gems for channels ---##
# TODO: bump up gem to 2.0
gem 'facebook-messenger'
gem 'telegram-bot-ruby'
gem 'twilio-ruby', '~> 5.32.0'
# twitty will handle subscription of twitter account events
# gem 'twitty', git: 'https://github.com/chatwoot/twitty'
gem 'twitty'
# facebook client
gem 'koala'
# slack client
gem 'slack-ruby-client'
# for dialogflow integrations
gem 'google-cloud-dialogflow'

##--- gems for debugging and error reporting ---##
# static analysis
gem 'brakeman'
gem 'scout_apm'
gem 'sentry-raven'

##-- background job processing --##
gem 'sidekiq'
# We want cron jobs
gem 'sidekiq-cron'

##-- Push notification service --##
gem 'fcm'
gem 'webpush'

##-- geocoding / parse location from ip --##
# http://www.rubygeocoder.com/
gem 'geocoder'
# to parse maxmind db
gem 'maxminddb'

# to create db triggers
gem 'hairtrigger'

gem 'procore-sift'

#gems for moonboard
gem 'sass-rails', '>= 6'
gem 'turbolinks', '~> 5'
gem 'zip_tricks'
gem 'cloudinary', require: true
gem 'activestorage-cloudinary-service'

#gems for trello-clone
gem 'devise-bootstrap-views'
gem 'sprockets-rails'
gem 'jquery-rails'
gem 'rails-ujs'
gem 'coffee-rails', '~> 4.2'
gem 'acts_as_list'

group :development do
  gem 'annotate'
  gem 'bullet'
  gem 'letter_opener'
  gem 'web-console'

  # used in swagger build
  gem 'json_refs', git: 'https://github.com/tzmfreedom/json_refs', ref: '131b11294fd6af9c428171f38516e6222a58c874'

  # When we want to squash migrations
  gem 'squasher'
end

group :test do
  # Cypress in rails.
  gem 'cypress-on-rails', '~> 1.0'
  # fast cleaning of database
  gem 'database_cleaner'

  #moonboard
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end

group :development, :test do
  gem 'bundle-audit', require: false
  gem 'byebug', platform: :mri
  gem 'factory_bot_rails'
  gem 'faker'
  gem 'listen'
  gem 'mock_redis', git: 'https://github.com/sds/mock_redis', ref: '16d00789f0341a3aac35126c0ffe97a596753ff9'
  gem 'pry-rails'
  gem 'rspec-rails', '~> 4.0.0.beta2'
  gem 'rubocop', require: false
  gem 'rubocop-performance', require: false
  gem 'rubocop-rails', require: false
  gem 'rubocop-rspec', require: false
  gem 'scss_lint', require: false
  gem 'seed_dump'
  gem 'shoulda-matchers'
  gem 'simplecov', '0.17.1', require: false
  gem 'spring'
  gem 'spring-watcher-listen'
  gem 'webmock'
end