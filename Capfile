require "capistrano/setup"
require "capistrano/deploy"
require "capistrano/scm/git"
install_plugin Capistrano::SCM::Git
require 'capistrano/rails'
require 'capistrano/passenger'
require 'capistrano/rbenv'
require 'thinking_sphinx/capistrano'

set :rbenv_type, :user
set :rbenv_ruby, '2.7.1'
Dir.glob("lib/capistrano/tasks/*.rake").each { |r| import r }
