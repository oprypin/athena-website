This section includes a set of common types that many projects may find useful, but are not generic enough to be included within Athena itself.  For example, a param converter that looks up an object from a DB based on an `id` path parameter and sets the object within the requests' attributes.  This is a useful converter, but the exact implementation would depend on which ORM you are using.