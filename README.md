# joqular
JavaScript Object Query Language Representation - Funny, it's just JSON.

- Serializable pattern and predicate based object matching for JavaScript.
- More built-in predicates/operators than most other other data query mechanisms, currently 30.
- Extensible with just one line of code per predicate/query operator.
- Just-in-time, fully indexed in-memory database, 2x to 10x faster than linear search, faster than IndexedDB and PouchDB for insert and search.
- Data and indexes represent the live state of JavaScript objects.
- Extensive Date and Time comparisons with precision at the year, month, day, hour, second, millisecond
- Automatic index configuration and optional persistence.
- 3 Way Single Function You Choose API ... callbacks, Promises, synchronous return values.

See the Wiki for detailed documentation: https://github.com/anywhichway/joqular/wiki

Issues log and milestones when available: https://github.com/anywhichway/joqular/issues

Let us know what features you would like us to work on by Starring any enhancement issues. (Obviously, we will work on bugs.)

npm install joqular

# updates

2015-04-25 v0.0.92 Initial public release (626 Unit tests and growing ...)

2015-04-25 v0.0.93 corrected typos in npm package  (626 Unit tests and growing ...)

2015-04-26 v0.0.93 Added patterns example, fixed recursion matching issue, added the $$ operator (628 Unit tests and growing ...)

2015-04-26 v0.0.95 Added missing predicate declaration for String.prototype.match (632 Unit tests and growing ...)
