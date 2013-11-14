Resources
=========

Workflow
--------
* How To Git
* [Git Cheatsheet](https://gist.github.com/metaraine/5128563)
* [Learn Git Branching](http://pcottle.github.io/learnGitBranching/)
* [Fork a Repo](https://help.github.com/articles/fork-a-repo)

Demos
-----
####Javascript Fundamentals
* [Getting Started with Javascript-slides](http://metaraine.github.io/gettingStartedJS)

####Agile 101 (Matt Clinton, Thu 9/19)
* [Main Presentation](http://www.slideshare.net/jaaronfarr/scrum-agile-for-everyone?from_search=1)
* [For large-scale efforts, I think the leading edge of the field for agility-at-scale](http://scaledagileframework.com/)
* http://www.youtube.com/watch?v=XU0llRltyFM
* http://www.slideshare.net/AgilescrumPro/agile-scrum-overview
* http://www.slideshare.net/srogers74/agile-software-development-overview-presentation
* http://www.slideshare.net/jurgenappelo/the-zen-of-scrum-10
* http://www.scrumalliance.org/why-scrum/scrum-for-the-agile-organization
* http://en.wikipedia.org/wiki/Scrum_(software_development)

Articles and Tutorials
----------------------
####HTTP
* [The Definitive Guide to Get vs Post](http://blog.teamtreehouse.com/the-definitive-guide-to-get-vs-post)

####Immediately Invoked Function Expressions
* [What is this construct in javascript?](http://stackoverflow.com/questions/8228281/what-is-this-construct-in-javascript)
* [Decoding Self Invoking Anonymous Functions](http://blog.themeforest.net/tutorials/ask-jw-decoding-self-invoking-anonymous-functions/)
* [Immediately-Invoked Function Expression - IIFE](http://benalman.com/news/2010/11/immediately-invoked-function-expression/)

####Design Patterns
* [Learning JavaScript Design Patterns](http://addyosmani.com/resources/essentialjsdesignpatterns/book/)

####4-Step Process to Using Handlebars
* Retrieve html of handlebars template

```
var templateSource = $('#myhandlebars-template').html();
```

* "Compile" the template- i.e. generate a function that inserts data into the {{placeholders}} of your template

```
var renderTemplate = Handlebars.compile(templateSource);
```

* Insert data into template

```
var rendered = renderTemplate(data);
```

* Add the rendered template to the DOM

```
$('#result').html(rendered);
```

SQL
---
####RDBMS
######General library:
* Wizard-level text: Database Design and Relational Theory - C.J. Date
* [Much more accessible intro](http://www.amazon.com/Manga-Guide-Databases-Mana-Takahashi/dp/1593271905)
A couple of the very many online self-trainings:
* http://sqlzoo.net">sqlzoo.net
* [db-class.org](http://db-class.org)

* [Slideshow about SQL/NoSQL tradeoffs](http://www.slideshare.net/vanuganti/sqlnosql-how-to-choose)

######SQL to MongoDB
* [SQL to MongoDB Mapping Chart](http://docs.mongodb.org/manual/reference/sql-comparison/)
* [SQL to Aggregation Mapping Chart](http://docs.mongodb.org/manual/reference/sql-aggregation-comparison/)

Python
------
* Python vs Javascript Comparison Chart - see resources
* [Python for Javascript Programmers (lecture slides)](http://slid.es/rainelourie/python-for-javascript-programmers/fullscreen)
* [Python 3.1 Quick Ref (PDF)](http://cloud.github.com/downloads/kroger/python-quick-ref/python-quick-ref.pdf)
* [Python on Codecademy](http://www.codecademy.com/tracks/python)
* [Learn Python the Hard Way](http://learnpythonthehardway.org/book/)
