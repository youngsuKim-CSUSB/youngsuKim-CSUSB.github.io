source "https://rubygems.org"
# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
# gem "jekyll", "~> 4.2.0"

# This is the default theme for new Jekyll sites. You may change this to anything you like.
# gem "minima", "~> 2.5"
# The theme itself is pinned in _config.yml via remote_theme, so it is not declared as a
# gem here. That keeps the Pages build and local `bundle exec jekyll serve` in sync.
gem "jekyll-remote-theme"

# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
gem "github-pages", group: :jekyll_plugins
# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows and JRuby do not include zoneinfo files, so bundle the tzinfo-data gem.
# (tzinfo itself is deliberately not pinned here: ~> 1.2 conflicts with the
# tzinfo ~> 2.0 that activesupport requires, which blocked dependency updates.)
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# ~> 1.8 (not >= 1.8.2) so the requirement stays satisfiable by the gems GitHub's
# Pages image pins; a fresh local resolve still picks up 1.8.2+.
gem "webrick", "~> 1.8"

# Do not pin nokogiri below what the github-pages gem requires (>= 1.16.2): a tight
# upper pin here is what kept 1.13.x, and its advisories, locked in Gemfile.lock.
gem "nokogiri", ">= 1.16.2"

