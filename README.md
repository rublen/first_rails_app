Blogger is my first app. It's done whithin The Odin Project with tutorial http://tutorials.jumpstartlab.com/projects/blogger.html

To be sure that everyone can login and try my app I blocked from deleting and changing first article with instructions and first author, whos email and password can be got from this first article 'README'. To get off this blocking you need modify actions 'destroy' and 'update' in articles_controller.rb and authors_controller.rb and modify articles/show.html.erb, authors/show.html.erb, authors/index.html.erb - find statements about 'Article.first' and 'Author.first' and delete them.

* Ruby version - 2.3.3

* Rails version - 5.1.3

* Database - MySQL

* Added gems - 'paperclip', 'sorcery'

=======

https://github.com/rublen/first_rails_app

rublen77@gmail.com
