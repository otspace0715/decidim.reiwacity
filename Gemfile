# frozen_string_literal: true

source "https://rubygems.org"

ruby RUBY_VERSION

gem "decidim", "0.23.3"
# gem "decidim-consultations", "0.23.3"
# gem "decidim-initiatives", "0.23.3"
# gem "decidim-templates", "0.23.3"

gem "bootsnap", "1.4.6"

gem "puma", "4.3.5"
gem "uglifier", "~> 4.1"

gem "faker", "~> 1.9"

gem "wicked_pdf", "~> 1.4"

group :development, :test do
  gem "byebug", "~> 11.0", platform: :mri

  gem "decidim-dev", "0.23.3"
end

group :development do
  gem "letter_opener_web", "~> 1.3"
  gem "listen", "3.2.1"
  gem "spring", "2.1.0"
  gem "spring-watcher-listen", "~> 2.0"
  gem "web-console", "~> 3.5"
end

gem "figaro"

group :production do
  gem "passenger"
  gem 'delayed_job_active_record'
  gem "daemons"
end

gem "aws-sdk-s3", require: false

gem 'fog-aws' 
#gem 'fog', require: 'fog/aws'

gem 'tzinfo-data'
gem 'rails', '5.2.4.4'
gem 'doc2text', '0.4.2'
gem 'ffi', '1.13.1'
gem 'msgpack', '1.3.3'
gem 'rake', '13.0.1'
gem 'concurrent-ruby', '1.1.7'

