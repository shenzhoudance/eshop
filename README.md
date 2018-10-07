# 新建一个仓库，初始化仓库，代码上传远端，远端上传服务器；
## 在这个过程中，在流程体系逐渐的清晰的情况下，最需要知道的核心的知识体系的框架就是
>1、后端的逻辑体系的梳理
2、前端的页面体系的美化
3、产品的内容体系的运营

## 掌握了以上的知识体系的架构，接下来就是需要完成的三个知识的结构：
>1、公司的体系的财务架构
2、公司的体系的人事结构
3、公司的体系的投资结构

通过掌握一个公司的行为，逐渐的过度到通过资本掌握无数个公司的行为，当我们的手上局别了无数家公司的行为之后，就逐渐的从一家公司的运营的执行的情况，过度到对于资本和股份的买卖情况，从卖商品到卖公司的行为逐渐的过度，从而进一步的释放自己的时间。

## 当我们的时间进一步的得到了释放，我其实就需要完成人生的三件事情的处理：
>1、婚姻家庭的组建和对于子女的抚养，以及对于父辈的赡养工作；
2、全球世界活动的参与和组织，构建最大的个人影响力和号召力；
3、撰写人生的知识体系的回忆录、技术路、投资路，进一步的梳理自己的人生；

然后当我们的人生逐渐的走向了尽头之后，坦然的接受死亡的到来；

# 电子商务的知识体系的逻辑
1、构建一个产品（Product）的数据库；
2、搭建一个购物车（Cart）的查看体系；
3、将购物车的价格数据（Pay）传递给支付系统，完成支付；

有型的商品需要填写购物地址；

无形的商品直接在已购栏目里面查看，具备了查看权限；

已购的商品可以传递给家人（4+4+2）使用；

![超级空间1.gif](https://upload-images.jianshu.io/upload_images/7680238-3add0809421eefe9.gif?imageMogr2/auto-orient/strip)

```
Last login: Sun Oct  7 08:55:44 on console
 xiaowei@xiaoweideMacBook-Pro ⮀ ~ ⮀ ⭠ master± ⮀ cd newspace
 xiaowei@xiaoweideMacBook-Pro ⮀ ~/newspace ⮀ ⭠ master± ⮀ ls
Vote           blog           demowork       dribbble_clone txblog
 xiaowei@xiaoweideMacBook-Pro ⮀ ~/newspace ⮀ ⭠ master± ⮀ rails new eshop
      create  
      create  README.md
      create  Rakefile
      create  config.ru
      create  .gitignore
      create  Gemfile
         run  git init from "."
Initialized empty Git repository in /Users/xiaowei/newspace/eshop/.git/
      create  app
      create  app/assets/config/manifest.js
      create  app/assets/javascripts/application.js
      create  app/assets/javascripts/cable.js
      create  app/assets/stylesheets/application.css
      create  app/channels/application_cable/channel.rb
      create  app/channels/application_cable/connection.rb
      create  app/controllers/application_controller.rb
      create  app/helpers/application_helper.rb
      create  app/jobs/application_job.rb
      create  app/mailers/application_mailer.rb
      create  app/models/application_record.rb
      create  app/views/layouts/application.html.erb
      create  app/views/layouts/mailer.html.erb
      create  app/views/layouts/mailer.text.erb
      create  app/assets/images/.keep
      create  app/assets/javascripts/channels
      create  app/assets/javascripts/channels/.keep
      create  app/controllers/concerns/.keep
      create  app/models/concerns/.keep
      create  bin
      create  bin/bundle
      create  bin/rails
      create  bin/rake
      create  bin/setup
      create  bin/update
      create  bin/yarn
      create  config
      create  config/routes.rb
      create  config/application.rb
      create  config/environment.rb
      create  config/secrets.yml
      create  config/cable.yml
      create  config/puma.rb
      create  config/spring.rb
      create  config/environments
      create  config/environments/development.rb
      create  config/environments/production.rb
      create  config/environments/test.rb
      create  config/initializers
      create  config/initializers/application_controller_renderer.rb
      create  config/initializers/assets.rb
      create  config/initializers/backtrace_silencers.rb
      create  config/initializers/cookies_serializer.rb
      create  config/initializers/cors.rb
      create  config/initializers/filter_parameter_logging.rb
      create  config/initializers/inflections.rb
      create  config/initializers/mime_types.rb
      create  config/initializers/new_framework_defaults_5_1.rb
      create  config/initializers/wrap_parameters.rb
      create  config/locales
      create  config/locales/en.yml
      create  config/boot.rb
      create  config/database.yml
      create  db
      create  db/seeds.rb
      create  lib
      create  lib/tasks
      create  lib/tasks/.keep
      create  lib/assets
      create  lib/assets/.keep
      create  log
      create  log/.keep
      create  public
      create  public/404.html
      create  public/422.html
      create  public/500.html
      create  public/apple-touch-icon-precomposed.png
      create  public/apple-touch-icon.png
      create  public/favicon.ico
      create  public/robots.txt
      create  test/fixtures
      create  test/fixtures/.keep
      create  test/fixtures/files
      create  test/fixtures/files/.keep
      create  test/controllers
      create  test/controllers/.keep
      create  test/mailers
      create  test/mailers/.keep
      create  test/models
      create  test/models/.keep
      create  test/helpers
      create  test/helpers/.keep
      create  test/integration
      create  test/integration/.keep
      create  test/test_helper.rb
      create  test/system
      create  test/system/.keep
      create  test/application_system_test_case.rb
      create  tmp
      create  tmp/.keep
      create  tmp/cache
      create  tmp/cache/assets
      create  vendor
      create  vendor/.keep
      create  package.json
      remove  config/initializers/cors.rb
      remove  config/initializers/new_framework_defaults_5_1.rb
         run  bundle install
The dependency tzinfo-data (>= 0) will be unused by any of the platforms Bundler is installing for. Bundler is installing for ruby but the dependency is only for x86-mingw32, x86-mswin32, x64-mingw32, java. To add those platforms to the bundle, run `bundle lock --add-platform x86-mingw32 x86-mswin32 x64-mingw32 java`.
Fetching gem metadata from https://rubygems.org/.........
Fetching gem metadata from https://rubygems.org/.
Resolving dependencies.....
Using rake 12.3.1
Using concurrent-ruby 1.0.5
Using i18n 1.1.0
Using minitest 5.11.3
Using thread_safe 0.3.6
Using tzinfo 1.2.5
Using activesupport 5.1.6
Using builder 3.2.3
Using erubi 1.7.1
Using mini_portile2 2.3.0
Using nokogiri 1.8.5
Using rails-dom-testing 2.0.3
Using crass 1.0.4
Using loofah 2.2.2
Using rails-html-sanitizer 1.0.4
Using actionview 5.1.6
Using rack 2.0.5
Using rack-test 1.1.0
Using actionpack 5.1.6
Using nio4r 2.3.1
Using websocket-extensions 0.1.3
Using websocket-driver 0.6.5
Using actioncable 5.1.6
Using globalid 0.4.1
Using activejob 5.1.6
Using mini_mime 1.0.1
Using mail 2.7.0
Using actionmailer 5.1.6
Using activemodel 5.1.6
Using arel 8.0.0
Using activerecord 5.1.6
Using public_suffix 3.0.3
Using addressable 2.5.2
Using bindex 0.5.0
Using bundler 1.16.0
Using byebug 10.0.2
Using xpath 3.1.0
Using capybara 2.18.0
Using ffi 1.9.25
Using childprocess 0.9.0
Using coffee-script-source 1.12.2
Using execjs 2.7.0
Using coffee-script 2.4.1
Using method_source 0.9.0
Using thor 0.20.0
Using railties 5.1.6
Using coffee-rails 4.2.2
Using multi_json 1.13.1
Using jbuilder 2.7.0
Using rb-fsevent 0.10.3
Using rb-inotify 0.9.10
Using ruby_dep 1.5.0
Using listen 3.1.5
Using puma 3.12.0
Using sprockets 3.7.2
Using sprockets-rails 3.2.1
Using rails 5.1.6
Using rubyzip 1.2.2
Using sass-listen 4.0.0
Using sass 3.6.0
Using tilt 2.0.8
Using sass-rails 5.0.7
Using selenium-webdriver 3.14.1
Using spring 2.0.2
Using spring-watcher-listen 2.0.1
Using sqlite3 1.3.13
Using turbolinks-source 5.2.0
Using turbolinks 5.2.0
Using uglifier 4.1.19
Using web-console 3.7.0
Bundle complete! 16 Gemfile dependencies, 70 gems now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
         run  bundle exec spring binstub --all
* bin/rake: spring inserted
* bin/rails: spring inserted
 xiaowei@xiaoweideMacBook-Pro ⮀ ~/newspace ⮀ ⭠ master± ⮀ cd eshop
 xiaowei@xiaoweideMacBook-Pro ⮀ ~/newspace/eshop ⮀ ⭠ master± ⮀ git init    
Reinitialized existing Git repository in /Users/xiaowei/newspace/eshop/.git/
 xiaowei@xiaoweideMacBook-Pro ⮀ ~/newspace/eshop ⮀ ⭠ master± ⮀ git add .
 xiaowei@xiaoweideMacBook-Pro ⮀ ~/newspace/eshop ⮀ ⭠ master± ⮀ git commit -m "first commit"
[master (root-commit) 7417364] first commit
 76 files changed, 1198 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 Gemfile
 create mode 100644 Gemfile.lock
 create mode 100644 README.md
 create mode 100644 Rakefile
 create mode 100644 app/assets/config/manifest.js
 create mode 100644 app/assets/images/.keep
 create mode 100644 app/assets/javascripts/application.js
 create mode 100644 app/assets/javascripts/cable.js
 create mode 100644 app/assets/javascripts/channels/.keep
 create mode 100644 app/assets/stylesheets/application.css
 create mode 100644 app/channels/application_cable/channel.rb
 create mode 100644 app/channels/application_cable/connection.rb
 create mode 100644 app/controllers/application_controller.rb
 create mode 100644 app/controllers/concerns/.keep
 create mode 100644 app/helpers/application_helper.rb
 create mode 100644 app/jobs/application_job.rb
 create mode 100644 app/mailers/application_mailer.rb
 create mode 100644 app/models/application_record.rb
 create mode 100644 app/models/concerns/.keep
 create mode 100644 app/views/layouts/application.html.erb
 create mode 100644 app/views/layouts/mailer.html.erb
 create mode 100644 app/views/layouts/mailer.text.erb
 create mode 100755 bin/bundle
 create mode 100755 bin/rails
 create mode 100755 bin/rake
 create mode 100755 bin/setup
 create mode 100755 bin/spring
 create mode 100755 bin/update
 create mode 100755 bin/yarn
 create mode 100644 config.ru
 create mode 100644 config/application.rb
 create mode 100644 config/boot.rb
 create mode 100644 config/cable.yml
 create mode 100644 config/database.yml
 create mode 100644 config/environment.rb
 create mode 100644 config/environments/development.rb
 create mode 100644 config/environments/production.rb
 create mode 100644 config/environments/test.rb
 create mode 100644 config/initializers/application_controller_renderer.rb
 create mode 100644 config/initializers/assets.rb
 create mode 100644 config/initializers/backtrace_silencers.rb
 create mode 100644 config/initializers/cookies_serializer.rb
 create mode 100644 config/initializers/filter_parameter_logging.rb
 create mode 100644 config/initializers/inflections.rb
 create mode 100644 config/initializers/mime_types.rb
 create mode 100644 config/initializers/wrap_parameters.rb
 create mode 100644 config/locales/en.yml
 create mode 100644 config/puma.rb
 create mode 100644 config/routes.rb
 create mode 100644 config/secrets.yml
 create mode 100644 config/spring.rb
 create mode 100644 db/seeds.rb
 create mode 100644 lib/assets/.keep
 create mode 100644 lib/tasks/.keep
 create mode 100644 log/.keep
 create mode 100644 package.json
 create mode 100644 public/404.html
 create mode 100644 public/422.html
 create mode 100644 public/500.html
 create mode 100644 public/apple-touch-icon-precomposed.png
 create mode 100644 public/apple-touch-icon.png
 create mode 100644 public/favicon.ico
 create mode 100644 public/robots.txt
 create mode 100644 test/application_system_test_case.rb
 create mode 100644 test/controllers/.keep
 create mode 100644 test/fixtures/.keep
 create mode 100644 test/fixtures/files/.keep
 create mode 100644 test/helpers/.keep
 create mode 100644 test/integration/.keep
 create mode 100644 test/mailers/.keep
 create mode 100644 test/models/.keep
 create mode 100644 test/system/.keep
 create mode 100644 test/test_helper.rb
 create mode 100644 tmp/.keep
 create mode 100644 vendor/.keep
 xiaowei@xiaoweideMacBook-Pro ⮀ ~/newspace/eshop ⮀ ⭠ master ⮀ git remote add origin https://github.com/shenzhoudance/eshop.git
 xiaowei@xiaoweideMacBook-Pro ⮀ ~/newspace/eshop ⮀ ⭠ master ⮀ git push -u origin master
Counting objects: 84, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (70/70), done.
Writing objects: 100% (84/84), 20.67 KiB | 1.72 MiB/s, done.
Total 84 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), done.
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/shenzhoudance/eshop/pull/new/master
remote:
To https://github.com/shenzhoudance/eshop.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.
 xiaowei@xiaoweideMacBook-Pro ⮀ ~/newspace/eshop ⮀ ⭠ master ⮀ atom .
 xiaowei@xiaoweideMacBook-Pro ⮀ ~/newspace/eshop ⮀ ⭠ master ⮀
```
git checkout -b gems
```
gem 'bulma-rails', '~> 0.6.1'
gem 'simple_form', '~> 3.5'
gem 'devise', '~> 4.4'
gem 'gravatar_image_tag', '~> 1.2'
gem 'carrierwave'
gem 'mini_magick'

https://rubygems.org/
https://github.com/plataformatec/simple_form
https://github.com/plataformatec/devise
https://github.com/carrierwaveuploader/carrierwave
https://github.com/minimagick/minimagick
rails generate simple_form:install

rails generate devise:install
config/environments/development.rb:
config.action_mailer.default_url_options = { host: 'localhost', port: 3000 }
rails g devise:views
rails generate devise User
rake db:migrate
rails g controller store index

app/assets/stylesheets/application.scss
```
@import "bulma";

.navbar-brand .title {
	color: white;
}

.notification:not(:last-child) {
	margin-bottom: 0;
}

```

app/views/layouts/application.html.erb
```
<!DOCTYPE html>
<html>
  <head>
    <title>eshop</title>
    <%= csrf_meta_tags %>

    <meta name="viewport" content="width=device-width, initial-scale=1">
    <%= stylesheet_link_tag 'https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css' %>
    <%= stylesheet_link_tag 'application', media: 'all', 'data-turbolinks-track': 'reload' %>
    <%= javascript_include_tag 'application' %>
  </head>

  <body class="<%= yield (:body_class) %>">
    <% if flash[:notice] %>
      <div class="notification is-success global-notification">
        <p class="notice"><%= notice %></p>
      </div>
    <% end %>
    <% if flash[:alert] %>
    <div class="notification is-danger global-notification">
      <p class="alert"><%= alert %></p>
    </div>
    <% end %>
     <nav class="navbar is-info" role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
        <%= link_to root_path, class:"navbar-item" do %>
          <h1 class="title is-5">超级空间</h1>
        <% end  %>
      <div class="navbar-burger burger" data-target="navbar">
        <span></span>
        <span></span>
        <span></span>
      </div>
    </div>

      <div id="navbar" class="navbar-menu">
        <div class="navbar-end">
          <div class="navbar-item">
            <div class="field is-grouped">

            <% if user_signed_in? %>
              <div class="navbar-item has-dropdown is-hoverable">
                  <%= link_to "退出", destroy_user_session_path, method: :delete, class: "button is-info" %>
                </div>
              </div>
            <% else %>

            <%= link_to "登录", new_user_session_path, class: "button is-info" %>
            <%= link_to "注册", new_user_registration_path, class: "button is-info" %>

            <% end %>

            </div>
          </div>
        </div>
    </div>
  </nav>

  <%= yield(:header) %>

  <div class="container">

    <%= yield %>

  </div>

  </body>
</html>


```
