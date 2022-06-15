---
title: ControlCollection
type: docs
weight: 0
url: /php-java/controlcollection/
---

# ControlCollection class

 A collection of ActiveX controls.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [addControl](/slides/php-java/controlcollection/addcontrol/)(int, float, float, float, float) | IControl | Creates and adds a new control to the collection. |
| [clear](/slides/php-java/controlcollection/clear/)() | void | Removes all controls from the collection. |
| [getSyncRoot](/slides/php-java/controlcollection/getsyncroot/)() | Object | Returns a synchronization root. Read-only Object. |
| [get_Item](/slides/php-java/controlcollection/get_item/)(int) | IControl | Returns a control at the specified position. |
| [isSynchronized](/slides/php-java/controlcollection/issynchronized/)() | boolean | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |
| [iterator](/slides/php-java/controlcollection/iterator/)() | IGenericEnumerator | Returns an enumerator that iterates through the collection. |
| [iteratorJava](/slides/php-java/controlcollection/iteratorjava/)() | IGenericEnumerator | Returns a java iterator for the entire collection. |
| [remove](/slides/php-java/controlcollection/remove/)(IControl) | void | Removes an ActiveX control from the collection. |
| [removeAt](/slides/php-java/controlcollection/removeat/)(int) | void | Removes an ActiveX control stored at specified position from the collection. |
| [size](/slides/php-java/controlcollection/size/)() | int | Returns a number of objects in the collection. Read-only int. |
