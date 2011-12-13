source "http://rubygems.org"

gem 'bundler', '>= 1.0.10'
gem 'nats', '>= 0.4.10', :require => 'nats/client'
gem 'eventmachine',  '~> 0.12.11.cloudfoundry.2'
gem 'em-http-request', '~> 1.0.0.beta.3', :require => 'em-http'

gem 'rack', :require => ["rack/utils", "rack/mime"]
gem 'rake'
gem 'thin', '~> 1.2.11'
gem 'yajl-ruby', :require => ['yajl', 'yajl/json_gem']
gem 'logging', '>= 1.5.0'

gem 'vcap_common'
gem 'vcap_logging', :require => ['vcap/logging']

group :test do
  gem "rspec"
  gem "rcov"
  gem "ci_reporter"
end
