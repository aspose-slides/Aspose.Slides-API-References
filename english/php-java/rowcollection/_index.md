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
| [addClone](/php-java/rowcollection/addclone/)(IRow, boolean) | IRow | Creates a copy of the specified template row and inserts it at the bottom of a table. |
| [getSyncRoot](/php-java/rowcollection/getsyncroot/)() | Object | Returns a synchronization root. Read-only Object. |
| [get_Item](/php-java/rowcollection/get_item/)(int) | IRow | Returns the row at the specified index. Read-only Row. |
| [insertClone](/php-java/rowcollection/insertclone/)(int, IRow, boolean) | IRow | Creates a copy of the specified template row and insert it at the specified position in a table. |
| [isSynchronized](/php-java/rowcollection/issynchronized/)() | boolean | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |
| [iterator](/php-java/rowcollection/iterator/)() | IGenericEnumerator | Returns an enumerator that iterates through the collection. |
| [iteratorJava](/php-java/rowcollection/iteratorjava/)() | IGenericEnumerator | Returns a java iterator for the entire collection. |
| [removeAt](/php-java/rowcollection/removeat/)(int, boolean) | void | Removes a row at the specified position from a table. |
| [size](/php-java/rowcollection/size/)() | int | Gets the number of rows actually contained in the collection. Read-only int. |
