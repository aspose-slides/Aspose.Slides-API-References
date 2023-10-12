---
title: RowCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/rowcollection/
---

## RowCollection class

 Represents table row collection.
 
| Name | Description |
| --- | --- |
| addClone (Row(../row), boolean) | Creates a copy of the specified template row and inserts it at the bottom of a table. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| templ | Row(../row) | Row which is used as a template. |
| withAttachedRows | boolean | True to copy also all rows attached to the template row. |

### Result
Row(../../row)


---


| Name | Description |
| --- | --- |
| getSyncRoot () | Returns a synchronization root. Read-only Object. |

### Result
Object


---


| Name | Description |
| --- | --- |
| get_Item (int) | Returns the row at the specified index. Read-only Row. |

### Result
Row(../../row)


---


| Name | Description |
| --- | --- |
| insertClone (int, Row(../row), boolean) | Creates a copy of the specified template row and insert it at the specified position in a table. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of a new row. |
| templ | Row(../row) | Row which is used as a template. |
| withAttachedRows | boolean | True to copy also all rows attached to the template row. |

### Result
Row(../../row)


---


| Name | Description |
| --- | --- |
| isSynchronized () | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| iterator () | Returns an enumerator that iterates through the collection. |

### Result



---


| Name | Description |
| --- | --- |
| iteratorJava () | Returns a java iterator for the entire collection. |

### Result



---


| Name | Description |
| --- | --- |
| removeAt (int, boolean) | Removes a row at the specified position from a table. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| firstRowIndex | int | Index of a row to delete. |
| withAttachedRows | boolean | True to delete also all attached rows. |


---


| Name | Description |
| --- | --- |
| size () | Gets the number of rows actually contained in the collection. Read-only int. |

### Result
int


---


