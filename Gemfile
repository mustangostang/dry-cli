# frozen_string_literal: true

source "https://rubygems.org"
gemspec

unless ENV["TRAVIS"]
  gem "byebug", require: false, platforms: :mri
  gem "yard",   require: false
end

gem "hanami-utils", "~> 1.1", require: false, git: "https://github.com/hanami/utils.git", branch: "develop"

gem "hanami-devtools", require: false, git: "https://github.com/hanami/devtools.git"
