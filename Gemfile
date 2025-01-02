# frozen_string_literal: true

source "https://rubygems.org"

gem "jekyll", "~> 4.3.2" # Jekyll 최신 버전
gem "jekyll-theme-chirpy" # Chirpy 테마 추가

gemspec

gem "html-proofer", "~> 5.0", group: :test

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]
