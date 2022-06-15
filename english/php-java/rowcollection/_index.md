---
title: RowCollection
type: docs
weight: 0
url: /php-java/rowcollection/
---

# RowCollection class

 Represents table row collection.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [addClone](/slides/php-java/rowcollection/addclone/)(IRow, boolean) | IRow | Creates a copy of the specified template row and inserts it at the bottom of a table. |
| [getSyncRoot](/slides/php-java/rowcollection/getsyncroot/)() | Object | Returns a synchronization root. Read-only Object. |
| [get_Item](/slides/php-java/rowcollection/get_item/)(int) | IRow | Returns the row at the specified index. Read-only Row. |
| [insertClone](/slides/php-java/rowcollection/insertclone/)(int, IRow, boolean) | IRow | Creates a copy of the specified template row and insert it at the specified position in a table. |
| [isSynchronized](/slides/php-java/rowcollection/issynchronized/)() | boolean | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |
| [iterator](/slides/php-java/rowcollection/iterator/)() | IGenericEnumerator | Returns an enumerator that iterates through the collection. |
| [iteratorJava](/slides/php-java/rowcollection/iteratorjava/)() | IGenericEnumerator | Returns a java iterator for the entire collection. |
| [removeAt](/slides/php-java/rowcollection/removeat/)(int, boolean) | void | Removes a row at the specified position from a table. |
| [size](/slides/php-java/rowcollection/size/)() | int | Gets the number of rows actually contained in the collection. Read-only int. |
