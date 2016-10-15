source 'https://rubygems.org'
ruby '2.3.0'

# comment is rails <= 4  gem

# gem 'rails',        '4.2.2'
gem 'rails', '5.0.0'
# gem 'sass-rails',   '5.0.6'
gem 'sass-rails'
gem 'uglifier',     '2.5.3'
# gem 'coffee-rails', '4.1.0'
# gem 'jquery-rails', '4.0.3'
# gem 'turbolinks',   '2.3.0'
# gem 'jbuilder',     '2.2.3'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder'
gem 'sdoc',         '0.4.0', group: :doc

group :development do
  gem 'annotate'
  gem 'letter_opener'
  gem 'rack-mini-profiler'
  # gem 'quiet_assets'
  # [evrone/quiet_assets: Mutes assets pipeline log messages.](https://github.com/evrone/quiet_assets)
  # config/environments/development.rb
  # config.assets.quiet = true
end

# # 開発補助developmentにいれるとエラー
# # [Rails better_errors gem server not starting - Stack Overflow](http://stackoverflow.com/questions/33166078/rails-better-errors-gem-server-not-starting)
gem 'better_errors'
gem 'binding_of_caller'


group :development, :test do
  gem 'sqlite3',     '1.3.9'
  # gem 'byebug',      '3.4.0'
  gem 'byebug'
  # gem 'web-console', '2.0.0.beta3'
  gem 'web-console'
  gem 'spring',      '1.1.3'
  gem 'pry-rails'  # rails console(もしくは、rails c)でirbの代わりにpryを使われる
  gem 'pry-doc'    # methodを表示
  gem 'pry-byebug' # デバッグを実施(Ruby 2.0以降で動作する)
  gem 'pry-stack_explorer' # スタックをたどれるend
  gem "view_source_map" # partical位置がわかる
  gem 'factory_girl_rails' # データ生成
end

group :test do
  gem 'minitest-reporters', '1.0.5'
  # gem 'mini_backtrace',     '0.1.3'
  gem 'mini_backtrace'
  gem 'guard-minitest',     '2.3.1'
  # [colszowka/simplecov: Code coverage for Ruby 1.9+ with a powerful configuration library and automatic merging of coverage across test suites](https://github.com/colszowka/simplecov)
  # test gem
  gem 'simplecov', :require => false
  # require 'simplecov'
  # SimpleCov.start
end

group :production do
  gem 'pg',             '0.17.1'
  gem 'rails_12factor', '0.0.2'
  gem 'puma'
end

gem 'bootstrap-sass',       '3.2.0.0'
gem 'bcrypt', '3.1.7'
gem 'faker','1.4.2'
gem 'carrierwave',             '0.10.0'
gem 'mini_magick',             '3.8.0'
gem 'fog',                     '1.36.0'
gem 'simple_form'
gem 'slim-rails'
gem 'awesome_print'
gem 'grape'
gem 'rest-client'
gem 'bower-rails'
# crontab管理
# gem 'whenever'
# gem 'twitter-bootstrap-rails'

# gem 'will_paginate', '3.0.7'
# gem 'will_paginate-bootstrap'
# gem 'bootstrap-will_paginate', '0.0.10'

# めんてされてないらしい
# gem 'client_side_validations'
# gem 'client_side_validations-simple_form'
