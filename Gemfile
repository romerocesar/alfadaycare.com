source "https://rubygems.org"
# jekyll version
# gem "jekyll", "~> 4.2.0"
# This is the default theme for new Jekyll sites.
# gem "minima", "~> 2.5"
gem "jekyll-remote-theme"

# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
gem "github-pages", "~> 231", group: :jekyll_plugins
# plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-agency"
end

# webrick is no longer included by default in Ruby installations
# starting from Ruby 3.0. it is needed by jekyll to serve the site
# locally
gem "webrick"

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
