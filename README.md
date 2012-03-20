给开发者的Ruby on Rails
============================

![GeneralAssemb.ly](https://github.com/generalassembly/ga-ruby-on-rails-for-devs/raw/master/images/ga.png "GeneralAssemb.ly")

本课程教授有经验的开发者[Ruby](http://www.ruby-lang.org) 和 [Ruby on Rails](http://rubyonrails.org/)。课程的设计理念是由一位实践中的Ruby爱好者和一个教学助理来进行教学。这两位都需要对Ruby, Rack以及Ruby on Rails有专家级的理解。 一个理想的班级大概有12到15名具有应用开发经验的学生。 教学计划的构想， 是上12节课，每节课两个小时，前面的六节课每一节课后会给出家庭作业。作业的指派在[Pivotal Tracker](http://pivotaltracker.com)进行跟踪。接下来的六节课给出带有代码的教学材料。最后课程结束后会有一个八小时的最终项目来获得认证。

开发这些材料是用于General Assembly的课程：给开发者的Ruby on Rails。访问GA申请下一期的课程: [Rails for Dev @ GA](https://generalassemb.ly/ruby-on-rails-for-devs)

课 程 材 料
--------------

我们由介绍学生Ruby开发环境和展示基础Ruby代码开始，学生也会通过[Github](http://github.com)学习怎么使用Git和练习开发流程，包括pull request和topic branches。 我们深入Ruby基础也含括了面向对象的特性，mixins（混入）和异常处理。


等到课程对语言特性足够熟悉之后，我们开始教授[Rack](http://rack.github.com/)，是任何Ruby on Rails知识的必要基础。该教程建立一个基础的web应用，利用Rack和文件系统来提供静态文件服务。还有一个从头做起，不用Rails generator来构造的Rails应用。测试代码开始用默认的单元测试基础写的，接着开始使用[RSpec](http://rspec.info/)进行行为驱动开发。应用会被部署到[Heroku](http://www.heroku.com/)。

我们接着会在开始ActiveRecord, ERB, HAML and SASS的课程前，教Ruby的元编程。然后不用顺手拈来的库来构建授权系统。这样的技术知识组合会给学生们必要的工具来构建一个完整的项目，在第六节课会重点介绍。等到我们要求学生们开发的材料准备好了，我们就开始克隆一个流行的[Stashboard](http://www.stashboard.org/)应用。

最后的课程的内容会包括，介绍Rails的RESTful APIs，学习[Grape](https://github.com/intridea/grape)，以及一个NoSQL数据库[MongoDB](http://mongodb.org)的介绍。我们也推荐你提供学生一些机会能够重新去学习那些不够清楚或者他们比较感兴趣的主题。

* [Introduction: Getting Started](https://github.com/generalassembly/ga-ruby-on-rails-for-devs/blob/master/lectures/00-getting-started/README.md)
* [Lecture 1: Developer Workflow](https://github.com/generalassembly/ga-ruby-on-rails-for-devs/blob/master/lectures/01-developer-workflow/README.md)
* [Lecture 2: Ruby 基础](https://github.com/generalassembly/ga-ruby-on-rails-for-devs/blob/master/lectures/02-ruby-basics/README.md)
* [Lecture 3: Rack](https://github.com/generalassembly/ga-ruby-on-rails-for-devs/blob/master/lectures/03-rack/README.md)
* [Lecture 4: Rails MVC](https://github.com/generalassembly/ga-ruby-on-rails-for-devs/blob/master/lectures/04-rails-mvc/README.md)
* [Lecture 5: RSpec](https://github.com/generalassembly/ga-ruby-on-rails-for-devs/blob/master/lectures/05-rspec/README.md)
* [Lecture 6: Ruby Meta-Programming](https://github.com/generalassembly/ga-ruby-on-rails-for-devs/blob/master/lectures/06-ruby-meta-programming/README.md)
* [Lecture 7: ActiveRecord](https://github.com/generalassembly/ga-ruby-on-rails-for-devs/blob/master/lectures/07-active-record/README.md)
* [Lecture 8: Rendering in Rails](https://github.com/generalassembly/ga-ruby-on-rails-for-devs/blob/master/lectures/08-erb-haml-sass/README.md)
* [Lecture 9: Authentication](https://github.com/generalassembly/ga-ruby-on-rails-for-devs/blob/master/lectures/09-authentication/README.md)
* [Lecture 10: RESTful API](https://github.com/generalassembly/ga-ruby-on-rails-for-devs/blob/master/lectures/10-restful-api/README.md)
* [Lecture 11: NoSQL with MongoDB](https://github.com/generalassembly/ga-ruby-on-rails-for-devs/blob/master/lectures/11-nosql-with-mongodb/README.md)
* [Lecture 12: Caching](https://github.com/generalassembly/ga-ruby-on-rails-for-devs/blob/master/lectures/12-caching/README.md)

练 习
---------

* [Exercises](https://github.com/generalassembly/ga-ruby-on-rails-for-devs/tree/master/class)

License
-------

This course is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 3.0 United States License](http://creativecommons.org/licenses/by-nc-sa/3.0/us/). It may be reused and adapted for non-commercial purposes. Please contact [Matthew Owens at GeneralAssemb.ly](mailto:mowens@generalassemb.ly) for commercial licensing.

![Creative Commons Attribution-NonCommercial-ShareAlike 3.0 United States License](http://i.creativecommons.org/l/by-nc-sa/3.0/us/88x31.png "Creative Commons Attribution-NonCommercial-ShareAlike 3.0 United States License")

Sponsors
--------

This course has been produced in partnership with [Pivotal Labs](http://pivotallabs.com/) and [Engine Yard](http://www.engineyard.com/).

![PivotalLabs](https://github.com/generalassembly/ga-ruby-on-rails-for-devs/raw/master/images/pivotal-labs.png "PivotalLabs")

![EngineYard](https://github.com/generalassembly/ga-ruby-on-rails-for-devs/raw/master/images/engine-yard.png "EngineYard")

翻 译
---------
[simsicon](http://github.com/simsicon)

Copyright
---------

(c) 2012 [GeneralAssemb.ly](https://generalassemb.ly/ruby-on-rails-for-devs), [Daniel Doubrovkine](http://github.com/dblock) and [contributors](https://github.com/generalassembly/ga-ruby-on-rails-for-devs/blob/master/CONTRIBUTORS.md).

