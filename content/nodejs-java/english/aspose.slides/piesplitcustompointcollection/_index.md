---
title: PieSplitCustomPointCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/piesplitcustompointcollection/
---

## PieSplitCustomPointCollection class

 Represents a collection of points for splitting point in a bar-of-pie or pie-of-pie chart with a custom split.
 
| Name | Description |
| --- | --- |
| add (int) | Adds data point by its index in parent series points collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| dataPointIndex | int | Index of data point in parent series points collection. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Point with the given index was not found". |


---


| Name | Description |
| --- | --- |
| addItem (ChartDataPoint(../chartdatapoint)) | Adds data point to collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| dataPoint | ChartDataPoint(../../chartdatapoint) | Data point add to. |


---


| Name | Description |
| --- | --- |
| clear () | Removes all items from the IGenericCollection. |


---


| Name | Description |
| --- | --- |
| containsItem (ChartDataPoint(../chartdatapoint)) | Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | ChartDataPoint(../../chartdatapoint) | The object to locate in the IGenericCollection. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| copyToTArray (com.aspose.slides.IChartDataPoint[], int) | Copies the elements of the IGenericCollection to an Array, starting at a particular Array index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| array | com.aspose.slides.IChartDataPoint[] | The one-dimensional Array that is the destination of the elements copied from IGenericCollection. The Array must have zero-based indexing. |
| arrayIndex | int | The zero-based index in array at which copying begins. |

### Error

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | The number of elements in the source IGenericCollection is greater than the available space from arrayIndex to the end of the destination array. |


---


| Name | Description |
| --- | --- |
| getSyncRoot () | Returns a synchronization root. Read-only Object. |

### Result
Object


---


| Name | Description |
| --- | --- |
| get_Item (int) | Returns chart data point for specified index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index. |

### Result
ChartDataPoint(../../chartdatapoint)


---


| Name | Description |
| --- | --- |
| isReadOnly () | Gets a value indicating whether the IGenericCollection is read-only. Read-only boolean. |

### Result
boolean


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
| remove (int) | Removes item from collection by it index in parent series points collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| dataPointIndex | int | Index of data point in parent series points collection. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | dataPointIndex is negative. |


---


| Name | Description |
| --- | --- |
| removeItem (ChartDataPoint(../chartdatapoint)) | Removes item from collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| dataPoint | ChartDataPoint(../../chartdatapoint) | Data point remove to. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| size () | Returns or sets the count of chart data points. Read-only int. |

### Result
int


---


