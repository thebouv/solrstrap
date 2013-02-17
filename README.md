#Solrstrap

Solrstrap is a Query-Result interface for Solr. Solrstrap is intended to be a starting point for those building web interfaces that talk to Solr.

##What does Solrstrap do?
Solrstrap takes search queries and displays search results. It also features:
* Instant search
* Restful interface (you can link directly to /solrstrap.html?q=doughnuts)
* Functioning history

##Why is Solrstrap cool?
Solrstrap is cool because it does everything in Javascript, CSS and HTML on the client side. JSON is shot back from the server and interpeted by the web browser.

Solrstrap therefore requires much less server power and bandwidth than standard middleware applications.

This _probably_ makes solrstrap the fastest available rendering engine for Solr.

##Installation, How do I make it work?
Optionally edit SERVERROOT in /js/solrstrap.js to point to the "select" endpoint of your solr instance

Click on /solrstrap.html.

Thats it.

##What is Solrstrap made of?
Solr strap is lovingly crafted from [Bootstrap](http://twitter.github.com/bootstrap/) and [Handlebars](http://handlebarsjs.com).

##Strengths
* Requires _only_ local installation- very easy to set up
* Blazing fast
* Uses very little bandwidth

##Weakenesses
* Is designed for "open" solr instances.
* SEO basically non-existant
* Will (probably) not work on truly ancient browsers (IE 7 and below)

#Future releases
* Support for facets...
* Support for infinite scrolling...
* Some form of arrow key functionality...
