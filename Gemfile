source 'https://rubygems.org'

ruby File.read('.ruby-version').match(/\S*/).to_s

gem 'sinatra'

gem 'tux'

group :development do
  gem 'shotgun'
  gem 'thin'
end

group :development, :test do
  gem 'awesome_print'
  gem 'pry'
  gem 'pry-byebug'
  gem 'rubocop', require: false
end
