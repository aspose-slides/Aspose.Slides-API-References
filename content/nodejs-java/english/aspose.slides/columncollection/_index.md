---
title: ColumnCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/columncollection/
---

## ColumnCollection class

 Represents collection of columns in a table.
 
| [addClone] ([Column], [boolean]) | Creates a copy of the specified template row and inserts it at the bottom of a table. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| templ | [Column] | Column which is used as a template. |
| withAttachedColumns | [boolean] | True to copy also all columns attached to the template row. |

### Result
[Column]


---


| [getSyncRoot] () | Returns a synchronization root. Read-only Object. |

### Result
Object


---


| [get_Item] ([int]) | Returns the column at the specified index. Read-only Column. |

### Result
[Column]


---


| [insertClone] ([int], [Column], [boolean]) | Creates a copy of the specified template column and insert it at the specified position in a table. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of a new column. |
| templ | [Column] | Column which is used as a template. |
| withAttachedColumns | [boolean] | True to copy also all columns attached to the template column. |

### Result
[Column]


---


| [isSynchronized] () | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

### Result
boolean


---


| [iterator] () | Returns an enumerator that iterates through the collection. |

### Result



---


| [iteratorJava] () | Returns a java iterator for the entire collection. |

### Result



---


| [removeAt] ([int], [boolean]) | Removes a column at the specified position from a table. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| firstColumnIndex | [int] | Index of a column to delete. |
| withAttachedRows | [boolean] | True to delete also all attached columns. |


---


| [size] () | Returns the number of columns in a collection. Read-only int. |

### Result
int


---


