ajax_example
============


## Minimal working example of using AJAX with django

* Very simple data model, with sqlite database of fruits, vegetables and animals.
* simple template with a select box and a results div, plus a simple modelform
* 3 views (one home view to render template and one ajax query, and one ajax post view)
* uses jQuery .load() to update the results when the selector changes state
* uses jQuery .ajax() to format and execute POST request
