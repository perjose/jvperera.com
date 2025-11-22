source "https://rubygems.org"

# --- REQUIRED CORE GEMS ---
# 1. Use the official GitHub Pages gem to ensure local dependencies match the server.
#    This gem automatically includes Jekyll, the supported theme, and all supported plugins.
gem "github-pages", group: :jekyll_plugins

# --- OPTIONAL: Non-supported Plugins/Themes ---
# If you want to use a theme or a plugin NOT supported by GitHub Pages, you must
# deploy using GitHub Actions to build your site manually.
# gem "my-custom-theme"
# gem "my-custom-plugin"

# --- PLATFORM-SPECIFIC GEMS (KEEP AS IS) ---
# These improve performance/compatibility on non-Linux systems (Windows/JRuby)
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]