---
title: ChartCategoryCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/chartcategorycollection/
---

## ChartCategoryCollection class

 Represents collection of  ChartCategory
 
| Name | Description |
| --- | --- |
| add (ChartDataCell(../chartdatacell)) | If category exists in collection, return it. Else creates new chart category from IChartDataCell and adds it to the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| chartDataCell | ChartDataCell(../../chartdatacell) | Cell used to create chart category. |

### Result
ChartCategory(../../chartcategory)


---


| Name | Description |
| --- | --- |
| add (Object) | Creates new ChartCategory from value and adds it to the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| value | Object | The value. This function adds worksheet with name AUTO_DATA and adds all values there. If you use ChartDataWorkbook to add or edit cell values, be sure that you do not use this worksheet Maximum number of values added using this function must not exceed 16711680 |

### Result
ChartCategory(../../chartcategory)

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | if limit exceeded |


---


| Name | Description |
| --- | --- |
| clear () | Removes all elements from the collection. |


---


| Name | Description |
| --- | --- |
| getGroupingLevelCount () | Returns count of category grouping levels used. Is more then one for multilevel categories. Read-only int. |

### Result
int


---


| Name | Description |
| --- | --- |
| getSyncRoot () | Returns an object that can be used to synchronize access to the collection. Read-only Object. Returns a synchronization root. Read-only Object. |

### Result
Object


---


| Name | Description |
| --- | --- |
| getUseCells () | If true then worksheet is used for storing categories (this case supports a multi-level categories). If false then worksheet is NOT used for storing values (and this case doesn't support a multi-level categories). Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| get_Item (int) | Gets the element at the specified index. |

### Result
ChartCategory(../../chartcategory)

### Error

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | index is not a valid index in the IList. |


---


| Name | Description |
| --- | --- |
| indexOf (ChartCategory(../chartcategory)) | Searches for the specified ChartCategory and returns the zero-based index of the first occurrence within the entire Collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| value | ChartCategory(../../chartcategory) | Chart category. |

### Result
int


---


| Name | Description |
| --- | --- |
| isSynchronized () | Returns a value indicating whether access to the List is synchronized (thread safe). Read-only boolean. |

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
| remove (ChartCategory(../chartcategory)) | Removes the specified value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| value | ChartCategory(../../chartcategory) | The value. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | The value parameter was not found in the collection. |


---


| Name | Description |
| --- | --- |
| removeAt (int) | Removes the element at the given index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of a category to remove. |


---


| Name | Description |
| --- | --- |
| setUseCells (boolean) | If true then worksheet is used for storing categories (this case supports a multi-level categories). If false then worksheet is NOT used for storing values (and this case doesn't support a multi-level categories). Read/write boolean. |


---


| Name | Description |
| --- | --- |
| size () | Returns a number of elements int the collection. Read-only int. |

### Result
int


---


