# Functional Concepts in Ruby Land

* What is functional programming?
* contrast Turing Machine vs Lambda Calculus vs Smalltalk OOP
* Brief intro to lambda calculus
* currying
* function composition
* Difference between classical OOP composition and functional composition
* Currying makes composition easy!
* ducks as types, like, really
* Introduce financial analysis example
* Very simple interfaces/types!
  1. Aggregation of records (reduce)
  2. Drop-in aggregator classes instantiated per database field
  3. Add a filter class that composes with the aggregator
  4. Add requirement for multiple filters (demonstrate ease of repeated composition via reduce)
  5. Add requirement for customizing filters (use currying!)
  6. Add requirement for aggregating aggregations (composing our compositions!)
