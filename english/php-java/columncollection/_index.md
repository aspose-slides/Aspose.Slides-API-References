---
title: ColumnCollection
type: docs
weight: 0
url: /php-java/columncollection/
---

# ColumnCollection class

 Represents collection of columns in a table.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [addClone](/slides/php-java/columncollection/addclone/)(IColumn, boolean) | IColumn | Creates a copy of the specified template row and inserts it at the bottom of a table. |
| [getSyncRoot](/slides/php-java/columncollection/getsyncroot/)() | Object | Returns a synchronization root. Read-only Object. |
| [get_Item](/slides/php-java/columncollection/get_item/)(int) | IColumn | Returns the column at the specified index. Read-only Column. |
| [insertClone](/slides/php-java/columncollection/insertclone/)(int, IColumn, boolean) | IColumn | Creates a copy of the specified template column and insert it at the specified position in a table. |
| [isSynchronized](/slides/php-java/columncollection/issynchronized/)() | boolean | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |
| [iterator](/slides/php-java/columncollection/iterator/)() | IGenericEnumerator | Returns an enumerator that iterates through the collection. |
| [iteratorJava](/slides/php-java/columncollection/iteratorjava/)() | IGenericEnumerator | Returns a java iterator for the entire collection. |
| [removeAt](/slides/php-java/columncollection/removeat/)(int, boolean) | void | Removes a column at the specified position from a table. |
| [size](/slides/php-java/columncollection/size/)() | int | Returns the number of columns in a collection. Read-only int. |
