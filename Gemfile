source "https://rubygems.org"

gem 'puppet', '4.9.4'
gem 'aws-sdk', '~>2.9.23'

group :test do
  gem 'puppetlabs_spec_helper'
  gem 'serverspec'
  gem 'kitchen-pester'
  gem 'test-kitchen', '1.16.0'
  gem 'kitchen-ec2'
  gem 'kitchen-puppet'
  gem 'winrm'
  gem 'winrm-fs'
end

group :development do
  gem 'pry'
end


group :spec do
  gem 'rspec', '>=3.4', '<3.5'
  gem 'rake'
  gem 'puppet-lint'
  gem 'rspec-puppet'
end

