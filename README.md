Feed Reader
===========
RSS is a standard protocol that is commonly used to publish updates for resources including blogs, news sites, and many more. It is based in XML and designed to be easily read by programs.

Your task is to create one.

Basics
======
Your program must be able to perform the following basic tasks:

1. Accept user defined feeds.
1. Read those feeds and store the data incrementally (preferrably in a database)
1. Track additional information related to feed items (such as whether they have been read or not)
1. Display a list of feed items
1. Display a detail view for an individual item (and track the view)

This project is designed to be implementable in nearly any programming language; however, it may be easiest to implement it as a web application to leverage knowledge of langauges you already know. If you do not want to write it in PHP then the following languages are suggested:

* Web
  * Node.js - Javascript on the server
  * Ruby (on rails)
  * Hack (a facebook derivative of PHP)
  * Java (Spring, or similar framework)
  * C# (MVC)


* Desktop (difficult to develop a UI for)
  * C/C++
  * Java
  * C# (Windows)


* Mobile - native
  * Android - Java
  * iOS - Objective C / cocoa
  * Windows Phone 8 - C#


* Mobile - cross platform
  * Phone Gap - (HTML, CSS, JavaScript
  * Xamarin - C#

Your application will need to store data, it is reccommended you do it with a database. If you do not want to use MySQL the following database technologies are suggested:

* SQL
  * PostgreSQL
  * MSSQL
  * Oracle


* NoSQL
  * Object - Easiest
    * MongoDB
    * Cassandra
    * CouchDB
  * Key/Value - Hard
    * Redis
    * LevelDB
    * Tokyo Cabinet or Kyoto Cabinet (or their network counterparts)
  * Graph - Harder
    * OrientDB
    * Neo4j
    * VertexDB


* File (not recommended)
  * JSON on disk
  * Flat file


Advanced
========
A project that performs all "Basic" actions will not impress a potential employer, what will is how you expand upon the project core, and make the idea your own. Below are some potential improvements/extensions to the core idea, or you may come up with your own.

###Display
* A clean elegant interface
* Single page app

###Social network integration
This involves adding functionality by leveraging existing networks (facebook, twitter, etc.) to create some functionality
* Share to social networks
* Pull friends and interests

###Discovery
These are all related to how your application can suggest feeds to a user
* Social network (Add friends, recommend feeds your friends like)
* Tag based, categorize different feeds by tags
* Content matching/indexing
* Recommend feeds you don't follow that other users that follow same/similar feeds do

###Organization
These are all related to how you choose to organize and/or filter feed entries
* Natural language analysis
  * Sentiment analysis (do you want to read happy, sad, etc. feed items)
  * Summary analysis
    * Hide similar stories
    * Show the most different stories first
* Vote based
* User interest based (weighted tags on feeds)

License
=======
This document is made available under a [CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/) license, the  full text of which can be fount [online](http://creativecommons.org/licenses/by-sa/4.0/legalcode) or in the [LICENSE](LICENSE) file.

Contributing
============
If you have any additional ideas you wish to share, or any additions/corrections to this document, please open a pull request. Please do not add yourself to the "Authors" section, this will be done by the repository owner. Note that terms of the contribution guidelines apply.

Authors
=======
[Kegan Myers](https://github.com/terribleplan)
