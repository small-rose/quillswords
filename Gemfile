# Gemfile
source "https://rubygems.org"

# Jekyll 核心
gem "jekyll", "~> 4.3"

# GitHub Pages 官方依赖（包含所有插件和兼容版本）
gem "github-pages", "~> 232", group: :jekyll_plugins

# 你的主题（因为用 remote_theme）
gem "jekyll-remote-theme"

# 常用插件（根据你实际使用添加）
group :jekyll_plugins do
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
  gem "jekyll-feed"
end

# Windows 和 JRuby 用户可选
gem "webrick"  # Jekyll 4+ 需要