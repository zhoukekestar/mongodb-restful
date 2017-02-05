
# mongodb-restful

This is a copy of [crest](http://github.com/cordazar/crest).

You can create a config file named `.mongodb-resful` on your project root to specify params. [more](http://github.com/cordazar/crest)

# Quick Start
* `npm install mongodb-restful -g` to install
* create a `.mongodb-restful` file to config your server
* run `mongodb-restful` to start

# Enhancement
* You can input dynamic json to query as we use `eval` instead of `JSON.parse`. Example: `/db/col?query={"date":{"$gt":new Date("2000-01-01")}}` 
