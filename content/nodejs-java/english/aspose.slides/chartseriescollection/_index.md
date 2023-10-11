---
title: ChartSeriesCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/chartseriescollection/
---

## ChartSeriesCollection class

 Represents collection of   ChartSeries
 
| [add] ([int]) Creates new chart series and adds it to the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| type | [int] | Type of series |

### Result
[ChartSeries]


---


| [add] ([ChartDataCell], [int]) Creates new chart series from ChartDataCell and adds it to the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| cellWithSeriesName | [ChartDataCell] | Cell which contain series name. |
| type | [int] | Type set type of series If chart series careted from same cell already in collection then function adds nothing and returns it's index. |

### Result
[ChartSeries]


---


| [add] ([ChartCellCollection], [int]) Creates new chart series from ChartCellCollection and adds it to the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| cellsWithSeriesName | [ChartCellCollection] | Cells which contain series name. |
| type | [int] | Type set type of series If chart series careted from same cell already in collection then function adds nothing and returns it's index. |

### Result
[ChartSeries]


---


| [add] ([String], [int]) Creates new chart series from value and adds it to the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | [String] | Series name. |
| type | [int] | Type set type of series |

### Result
[ChartSeries]


---


| [clear] () Removes all controls from the collection. |


---


| [getSyncRoot] () Returns a synchronization root. Read-only Object. |

### Result
Object


---


| [get_Item] ([int]) Gets the element at the specified index. |

### Result
[ChartSeries]

### Error

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentOutOfRangeException | index is not a valid index in the IList. |


---


| [indexOf] ([ChartSeries]) Searches for the specified ChartSeries and returns the zero-based index of the first occurrence within the entire Collection |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| value | [ChartSeries] | Chart series value. |

### Result
int


---


| [insert] ([int], [int]) Creates new chart series and inserts it into the collection. |

### Result
[ChartSeries]


---


| [isSynchronized] () Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

### Result
boolean


---


| [iterator] () Returns an enumerator that iterates through the collection. |

### Result



---


| [iteratorJava] () Returns a java iterator for the entire collection. |

### Result



---


| [remove] ([ChartSeries]) Removes the specified value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| value | [ChartSeries] | The value. |

### Error

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | The value parameter was not found in the collection. |


---


| [removeAt] ([int]) Removes an ActiveX control stored at specified position from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of a control to remove. |


---


| [size] () Returns a number of objects in the collection. Read-only int. |

### Result
int


---


