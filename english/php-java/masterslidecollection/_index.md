---
title: MasterSlideCollection
type: docs
weight: 0
url: /php-java/masterslidecollection/
---

# MasterSlideCollection class

 Represents a collection of master slides.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [addClone](/php-java/masterslidecollection/addclone/)(IMasterSlide) | IMasterSlide | Adds a copy of a specified master slide to the end of the collection. Linked layout slides will be copied too. |
| [getSyncRoot](/php-java/masterslidecollection/getsyncroot/)() | Object | Returns a synchronization root. Read-only Object. |
| [get_Item](/php-java/masterslidecollection/get_item/)(int) | IMasterSlide | Gets the element at the specified index. Read-only MasterSlide. |
| [insertClone](/php-java/masterslidecollection/insertclone/)(int, IMasterSlide) | IMasterSlide | Inserts a copy of a specified master slide to specified position of the collection. Linked layout slides will be copied too. |
| [isSynchronized](/php-java/masterslidecollection/issynchronized/)() | boolean | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |
| [iterator](/php-java/masterslidecollection/iterator/)() | IGenericEnumerator | Returns an enumerator that iterates through the collection. |
| [iteratorJava](/php-java/masterslidecollection/iteratorjava/)() | IGenericEnumerator | Returns a java iterator for the entire collection. |
| [remove](/php-java/masterslidecollection/remove/)(IMasterSlide) | void | Removes the first occurrence of a specific object from the collection. |
| [removeAt](/php-java/masterslidecollection/removeat/)(int) | void | Removes the element at the specified index of the collection. |
| [removeUnused](/php-java/masterslidecollection/removeunused/)(boolean) | void | Removes unused master slides. |
| [size](/php-java/masterslidecollection/size/)() | int | Gets the number of elements actually contained in the collection. Read-only int. |
