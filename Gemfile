# frozen_string_literal: true

source "https://rubygems.org"
gemspec

gem "jekyll", ENV["JEKYLL_VERSION"] if ENV["JEKYLL_VERSION"]

# Keep local builds working on Ruby 2.6 by defaulting to Jekyll 3.9.
gem "jekyll", "~> 3.9.3" unless ENV["JEKYLL_VERSION"]
gem "kramdown-parser-gfm", "~> 1.1"
gem "ffi", "~> 1.15.5"
