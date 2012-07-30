Changes and TODO


## 2012-????-?? / 0.2.0

* [TODO] ClojureScript support


## 2012-July-?? / 0.1.0

* Template with slots
* Parse/compile and Render are separate
* Pluggable error reporting
* Model
* Filter functions
* Slot features
    * attributes   <% name %>
    * literals     <% "Number" 1 "String" "Joe Walker" "Keyword" :male %>
    * filter calls <% (second name) %>
* Template Groups and "Include"
* JVM specific API for template groups
* Collection literals - vectors, sets, maps
* Cache compiled templates (re-load only if modified)
