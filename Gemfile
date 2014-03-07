if RUBY_VERSION =~ /1.9/
  Encoding.default_external = Encoding::UTF_8
  Encoding.default_internal = Encoding::UTF_8
end

source 'https://rubygems.org'

gemspec

gem 'rake'
gem 'capybara', "~> 2.2.1"
gem 'pry'

group :test do
  gem 'cucumber'
  gem 'jasmine', '~> 1.3'
  gem 'sauce-connect', :path => './gems/sauce-connect'
end

group :development do
  gem 'debugger', :platform => :mri_19
end
