---
title: TabCollection
type: docs
weight: 0
url: /php-java/tabcollection/
---

# TabCollection class

 Represents a collection of tabs.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [add](/php-java/tabcollection/add/)(double, int) | ITab | Adds a Tab to the collection. |
| [add](/php-java/tabcollection/add/)(ITab) | int | Adds a Tab to the collection. |
| [clear](/php-java/tabcollection/clear/)() | void | Removes all elements from the collection. |
| [equals](/php-java/tabcollection/equals/)(Object) | boolean | Determines whether two TabsEx instances are equal. |
| [getSyncRoot](/php-java/tabcollection/getsyncroot/)() | Object | Returns a synchronization root. Read-only Object. |
| [get_Item](/php-java/tabcollection/get_item/)(int) | ITab | Gets the element at the specified index. Read-only Tab. |
| [isSynchronized](/php-java/tabcollection/issynchronized/)() | boolean | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |
| [iterator](/php-java/tabcollection/iterator/)() | IGenericEnumerator | Returns an enumerator that iterates through the collection. |
| [iteratorJava](/php-java/tabcollection/iteratorjava/)() | IGenericEnumerator | Returns a java iterator for the entire collection. |
| [removeAt](/php-java/tabcollection/removeat/)(int) | void | Removes the element at the specified index of the collection. |
| [size](/php-java/tabcollection/size/)() | int | Gets the number of elements actually contained in the collection. Read-only int. |