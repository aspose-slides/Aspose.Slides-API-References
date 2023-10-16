---
title: RowCollection
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/rowcollection/
---

## RowCollection class

 Represents table row collection.
 
### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Row](../row), boolean) | Creates a copy of the specified template row and inserts it at the bottom of a table. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| templ | [Row](../row) | Row which is used as a template. |
| withAttachedRows | boolean | True to copy also all rows attached to the template row. |

 **Returns:**
[Row](../row)


---


### getSyncRoot {#getSyncRoot}

| Name | Description |
| --- | --- |
| getSyncRoot () | Returns a synchronization root. Read-only Object. |

 **Returns:**
Object


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | Returns the row at the specified index. Read-only Row. |

 **Returns:**
[Row](../row)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Row](../row), boolean) | Creates a copy of the specified template row and insert it at the specified position in a table. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of a new row. |
| templ | [Row](../row) | Row which is used as a template. |
| withAttachedRows | boolean | True to copy also all rows attached to the template row. |

 **Returns:**
[Row](../row)


---


### isSynchronized {#isSynchronized}

| Name | Description |
| --- | --- |
| isSynchronized () | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

 **Returns:**
boolean


---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () | Returns an enumerator that iterates through the collection. |

 **Returns:**



---


### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava () | Returns a java iterator for the entire collection. |

 **Returns:**



---


### removeAt {#removeAt}

| Name | Description |
| --- | --- |
| removeAt (int, boolean) | Removes a row at the specified position from a table. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| firstRowIndex | int | Index of a row to delete. |
| withAttachedRows | boolean | True to delete also all attached rows. |

 **Returns:**
void


---


### size {#size}

| Name | Description |
| --- | --- |
| size () | Gets the number of rows actually contained in the collection. Read-only int. |

 **Returns:**
int


---


