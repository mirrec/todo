source 'http://rubygems.org'

gem 'rails', '3.0.9' #comment

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'mysql2', '0.2.6'
gem "jquery-rails"

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger (ruby-debug for Ruby 1.8.7+, ruby-debug19 for Ruby 1.9.2+)
# gem 'ruby-debug'
# gem 'ruby-debug19', :require => 'ruby-debug'

# Bundle the extra gems:
# gem 'bj'
# gem 'nokogiri'
# gem 'sqlite3-ruby', :require => 'sqlite3'
# gem 'aws-s3', :require => 'aws/s3'

# Bundle gems for the local environment. Make sure to
# put test-only gems in this group so their generators
# and rake tasks are available in development mode:
group :development do
	# gem 'guard'
	# 	gem 'guard-rspec'
	# 	gem 'guard-bundler'
	# 
	# 	if RUBY_PLATFORM.downcase.include?("darwin")
	# 		gem 'rb-fsevent'
	# 		gem 'growl' # also install growlnotify from the Extras/growlnotify/growlnotify.pkg in Growl disk image
	# 	end
end

gem "growl"
gem "rspec-rails", :group => [:test, :development]

group :test do
  gem "factory_girl_rails"
  gem "capybara"
  gem "guard-rspec"
end
