source 'https://rubygems.org'
ruby '1.9.3'

# PostgreSQL driver
gem 'pg'

# Sinatra driver
gem 'sinatra'
gem 'sinatra-contrib'

# Use Thin for our web server
gem 'thin'

gem 'activesupport'
gem 'activerecord'

gem 'rake'

gem 'shotgun'

# Gems needed for API calls
gem 'cryptsy-api'

# Gem needed for Testing
gem 'simplecov', :require => false

gem 'rspec'

group :test do
  gem 'shoulda-matchers'
  gem 'rack-test'
end

group :test, :development do
  gem 'factory_girl'
  gem 'faker'
end
