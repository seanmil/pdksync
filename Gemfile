source "https://rubygems.org"

git_source(:github) { |repo_name| "https://github.com/#{repo_name}" }

# Specify your gem's dependencies in pdksync.gemspec
gemspec

group :development do
  gem 'rb-readline', require: true
end

group :rubocop do
    gem 'rubocop', '~> 1.48.1',           require: false
    gem 'rubocop-rspec', '~> 2.19',       require: false
    gem 'rubocop-performance', '~> 1.16', require: false
end
