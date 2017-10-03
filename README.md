![Nanobox & Hacktoberfest](https://content.nanobox.io/content/images/2017/10/hacktoberfest-gh-banner.png)

# Hacktoberfest
Contribute to all the [Nanobox] things! [Hacktoberfest](https://hacktoberfest.digitalocean.com/) is here, and if you're looking for an opportunity to contribute, we're here to help. We have a ton of open source projects that are ready and waiting for your pull requests.

### Guides
Our guides are the place where people learn how to configure their applications to deploy with Nanobox. We created many of these long ago and frameworks and processes have changed. Updating them is on our to-do lists, but if you'd like to help, you're more than welcome to. Everything from typos, flow, to full-fledged guides are welcome changes and additions.  
Grab a guide and run through it. If it doesn't work, fix it! Also, fix any typos or steps of the process that just don't work.

[Site](https://guides.nanobox.io) | [On Github](https://github.com/nanobox-io/nanobox-guides)

#### General Updates

- Typos
- Flow
- Functionality (Make sure the process works)

#### Specific Guides
If you're looking to contribute full-fledged guides, the following guides are highly requested, they just need updated content:

**Generic Scala Guides**  
There are currently guides for the Play framework, but generic Scala guides would be awesome. The easiest way to do this is to copy files for existing generic language guides and adapt them accordingly. Using existing Python guides as an example, here's what you would do.

- [ ] `cp -a app/pages/python/generic app/pages/scala/generic` and update jade content for Scala
- [ ] `cp app/pages/python/generic.jade app/pages/scala/generic.jade` and update jade content for Scala
- [ ] `cp articles/article-groups/python/generic.yml articles/article-groups/scala/generic.yml` and update yaml content for Scala
- [ ] `cp -a articles/python/generic articles/scala/generic` and update markdown content for Scala

Engine settings can be viewed in the [Scala Engine](https://github.com/nanobox-io/nanobox-engine-scala).

**Generic Java Guides**  
Guides for running Java apps with Nanobox would be great! The easiest way to do this is to copy files for existing generic language guides and adapt them accordingly. Using existing Python guides as an example, here's what you would do.

- [ ] `cp -a app/pages/python/generic app/pages/java/generic` and update jade content for Java
- [ ] `cp app/pages/python/generic.jade app/pages/java/generic.jade` and update jade content for Java
- [ ] `cp articles/article-groups/python/generic.yml articles/article-groups/java/generic.yml` and update yaml content for Java
- [ ] `cp -a articles/python/generic articles/java/generic` and update markdown content for Java

Engine settings can be viewed in the [Java Engine](https://github.com/nanobox-io/nanobox-engine-java).

**(PHP) CakePHP Guides**
- [ ] Update content in `articles/php/cakephp/add-a-database.md`
- [ ] Update content in `articles/php/cakephp/configure-yii.md`
- [ ] Update content in `articles/php/cakephp/existing-app.md`
- [ ] Update content in `articles/php/cakephp/from-scratch.md`

**(Python) Pyramid Guides**
- [ ] Update content in `articles/python/pyramid/add-a-database.md`
- [ ] Update content in `articles/python/pyramid/configure-yii.md`
- [ ] Update content in `articles/python/pyramid/existing-app.md`
- [ ] Update content in `articles/python/pyramid/from-scratch.md`
- [ ] Update content in `articles/python/pyramid/preview-your-app.md`

**(PHP) Yii Guides**
- [ ] Update content in `articles/php/yii/add-a-database.md`
- [ ] Update content in `articles/php/yii/configure-yii.md`
- [ ] Update content in `articles/php/yii/existing-app.md`
- [ ] Update content in `articles/php/yii/from-scratch.md`

**(PHP) Zend Framework Guides**
- [ ] Update content in `articles/php/zendframework/add-a-database.md`
- [ ] Update content in `articles/php/zendframework/configure-yii.md`
- [ ] Update content in `articles/php/zendframework/existing-app.md`
- [ ] Update content in `articles/php/zendframework/from-scratch.md`

### Quickstarts
Our quickstarts are a way for people to get started quickly with Nanobox. We created as many of these as we could as fast as we could, but over time, they've gotten old and likely need updating!  
Grab a quickstart and test it out. If it doesn't work, make it work! If you see one missing... add it!

[On Github](https://github.com/nanobox-quickstarts)

**Node/Javascript**

- [Adonis](https://github.com/nanobox-quickstarts/nanobox-adonis)
- [Angular](https://github.com/nanobox-quickstarts/nanobox-angular)
- [Ember](https://github.com/nanobox-quickstarts/nanobox-ember)
- [Express](https://github.com/nanobox-quickstarts/nanobox-express)
- [Feathers](https://github.com/nanobox-quickstarts/nanobox-feathers)
- [Hapi](https://github.com/nanobox-quickstarts/nanobox-hapi)
- [Nette](https://github.com/nanobox-quickstarts/nanobox-nette)
- [React](https://github.com/nanobox-quickstarts/nanobox-react)
- [Sails](https://github.com/nanobox-quickstarts/nanobox-sails)
- [Vue](https://github.com/nanobox-quickstarts/nanobox-vue)

**Ruby**

- [Discourse](https://github.com/nanobox-quickstarts/nanobox-discourse)
- [Rails](https://github.com/nanobox-quickstarts/nanobox-rails) (needs updated for Rails 5+)
- [Sinatra](https://github.com/nanobox-quickstarts/nanobox-sinatra)

**Python**

- [Django](https://github.com/nanobox-quickstarts/nanobox-django)
- [Flask](https://github.com/nanobox-quickstarts/nanobox-flask)

**Golang**

- [Beego](https://github.com/nanobox-quickstarts/nanobox-beego)
- [Echo](https://github.com/nanobox-quickstarts/nanobox-echo)
- [Gin](https://github.com/nanobox-quickstarts/nanobox-gin)
- [Revel](https://github.com/nanobox-quickstarts/nanobox-revel)
- [Buffalo]() (Needs Quickstart!)

**Elixir**

- [Firestorm](https://github.com/nanobox-quickstarts/nanobox-firestorm)
- [Kitto](https://github.com/nanobox-quickstarts/nanobox-kitto)
- [Phoenix](https://github.com/nanobox-quickstarts/nanobox-phoenix-example)

**PHP**

- [Codeigniter](https://github.com/nanobox-quickstarts/nanobox-codeigniter)
- [Laravel](https://github.com/nanobox-quickstarts/nanobox-laravel)
- [Lumen](https://github.com/nanobox-quickstarts/nanobox-lumen)
- [Phalcon](https://github.com/nanobox-quickstarts/nanobox-phalcon)
- [Slim](https://github.com/nanobox-quickstarts/nanobox-slim)
- [Symfony](https://github.com/nanobox-quickstarts/nanobox-symfony)
- [Wordpress](https://github.com/nanobox-quickstarts/nanobox-wordpress)

**Misc.**

- [Ghost](https://github.com/nanobox-quickstarts/nanobox-ghost) (Needs Guides!)
- [Hugo](https://github.com/nanobox-quickstarts/nanobox-hugo) (Needs Guides!)
- [Middleman](https://github.com/nanobox-quickstarts/nanobox-middleman) (Needs Guides!)

> Extra Credit: Initially we created these as quick development environments to *test* Nanobox. Turn's out, people are using them as boilerplate for production applications. All they really need are [web components](https://docs.nanobox.io/boxfile/web/) and potentially data migrations added to their `boxfile.yml`s. Some have them and are good to go. Other don't. Some are somewhere in between...

### Docs

We're constantly working on our docs, making sure they're up to date. If you'd like to help by fixing typos, grammar, and flow, have at it! If you feel like our docs are missing something... add it!

[Site](https://docs.nanobox.io) | [On Github](https://github.com/nanobox-io/nanobox-docs)

### Nanobox/Nanopack

**Nanopack**  
This is our open source collection of microservices. These are what power Nanobox under the hood. Any of these projects are free game during Hacktoberfest.

[Site](http://nanopack.io/) | [On Github](https://github.com/nanopack)

**Nanobox**  
This is the bread and butter of Nanobox. The is what makes it all happen. We'd love any contributions you have to help us make Nanobox better!

[Site](https://nanobox.io/) | [On Github](https://github.com/nanobox-io/nanobox)
