source 'https://rubygems.org'
ruby '2.1.5'

gem 'rails', '4.2.4'
gem 'puma'
gem 'sqlite3', :group => [:development, :test]
group :production do
  gem 'thin'
  gem 'pg'
end
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'

gem 'jbuilder', '~> 2.0'
gem 'bootstrap-sass'
gem 'font-awesome-rails'
gem 'animate-rails'

group :doc do
  gem 'sdoc', '~> 0.4.0'
end

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'annotate', '~> 2.6.10'
  gem 'spring'
end

group :test do
  gem 'byebug'
end

group :production do
  gem 'rails_12factor'
end

# Required gems for time-zone in windows environments

gem 'tzinfo-data', platforms: [:mingw, :mswin]
require 'rbconfig'
gem 'wdm', '>= 0.1.0' if RbConfig::CONFIG['target_os'] =~ /mswin|mingw|cygwin/i
