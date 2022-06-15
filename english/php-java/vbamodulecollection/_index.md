---
title: VbaModuleCollection
type: docs
weight: 0
url: /php-java/vbamodulecollection/
---

# VbaModuleCollection class

 Represents a collection of a VBA Project modules.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [addEmptyModule](/slides/php-java/vbamodulecollection/addemptymodule/)(String) | IVbaModule | Adds a new empty module to the VBA Project. |
| [getSyncRoot](/slides/php-java/vbamodulecollection/getsyncroot/)() | Object | Returns a synchronization root. Read-only Object. |
| [get_Item](/slides/php-java/vbamodulecollection/get_item/)(int) | IVbaModule | Gets the element at the specified index. |
| [isSynchronized](/slides/php-java/vbamodulecollection/issynchronized/)() | boolean | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |
| [iterator](/slides/php-java/vbamodulecollection/iterator/)() | IGenericEnumerator | Returns an enumerator that iterates through the collection. |
| [iteratorJava](/slides/php-java/vbamodulecollection/iteratorjava/)() | IGenericEnumerator | Returns a java iterator for the entire collection. |
| [remove](/slides/php-java/vbamodulecollection/remove/)(IVbaModule) | void | Removes the first occurrence of a specific object from the collection. |
| [size](/slides/php-java/vbamodulecollection/size/)() | int | Gets the number of elements actually contained in the collection. Read-only int. |
