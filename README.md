# Awesome RethinkDB [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
 A curated list of RethinkDB resources and libraries.


## Table of Contents

- [Official resources](#official-resources)
- [RethinkDB Horizon](#rethinkdb-horizon)
- [Data modelling](#data-modelling)
- [Node.js packages](#node-js-packages)

## Official resources

While an obvious place to look for help, there are some essential, but often overlooked resources that this list would not be complete without.

* [RethinkDB on Slack](https://rethinkdb.slack.com/messages/general/) - get help, learn tricks, talk to developers, help others.
* [RethinkDB blog](http://rethinkdb.com/blog/) - contains news not only about RethinkDB itself, but also from the app ecosystem.
* [RethinkDB on YouTube](https://www.youtube.com/channel/UC1kJkmSWt_snLDfuXgJnLnQ) - real user stories, presentations, future features.

### Release 2.3 - coming Q1 2016

* An official [Windows build](https://github.com/rethinkdb/rethinkdb/issues/1100)
* [Permissions](https://github.com/rethinkdb/rethinkdb/issues/4519) - a basic user/permission structure (not aimed at browser-to-database connection, see [Horizon section](#rethinkdb-horizon) for that)
* Encrypted connections for [drivers](https://github.com/rethinkdb/rethinkdb/issues/3158) and [clusters](https://github.com/rethinkdb/rethinkdb/issues/3151)

### Subsequent releases

RethinkDB members have not committed to any particular version and date, as features are largely driven by community requests. It's likely that some of them will arrive in 2.4, around Q2/Q3 2016.

* [resumable changefeeds](https://github.com/rethinkdb/rethinkdb/issues/3471) - lets you to continue where you left off
* [GraphQL support](https://github.com/rethinkdb/rethinkdb/issues/3711) - involves discussion around Horizon
* [Changefeeds on joins](https://github.com/rethinkdb/rethinkdb/issues/3997)
* [Filtering by several indexes](https://github.com/rethinkdb/rethinkdb/issues/4150) - letting the server optimise queries
* [Document links](https://github.com/rethinkdb/rethinkdb/issues/4853) - the first step towards graph features, reducing the need for table joins

## RethinkDB Horizon

* [What's coming in 2016](https://youtu.be/zL5_EsF06DM?t=657) - the reasoning behind, and the first public demonstration of Horizon (briefly known as Fusion during pre-alpha).


## Data modelling

* [Why not MongoDB](http://www.sarahmei.com/blog/2013/11/11/why-you-should-never-use-mongodb/) - a dated article with a timeless lesson about potential risks of storing document trees vs relational data.
* [Awesome Big Data](https://github.com/onurakpolat/awesome-bigdata) List - gives you a wider context of the database world.

## Node.js packages

* [rethinkdbdash](https://www.npmjs.com/package/rethinkdbdash) - an alternative driver featuring connecting pooling.
* [JS Data adapter](https://www.npmjs.com/package/js-data-rethinkdb) - allows you to use one API to query RethinkDB from Node.js as you would query REST API from a browser. 

