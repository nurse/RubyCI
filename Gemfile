source 'https://rubygems.org'

ruby ENV['CUSTOM_RUBY_VERSION'] || '~> 3.2.1'

gem 'rails', '~> 7.0'
gem 'puma'
gem 'bootsnap'
gem "importmap-rails"
gem 'propshaft'

gem 'aws-sdk-s3', '~> 1'

group :development do
  gem 'foreman'
  gem 'sqlite3'
  gem 'listen'
  group :assets do
    gem 'cssbundling-rails'
  end
end

group :production do
  gem 'pg'
end


gem "dartsass-rails", "~> 0.4.1"
