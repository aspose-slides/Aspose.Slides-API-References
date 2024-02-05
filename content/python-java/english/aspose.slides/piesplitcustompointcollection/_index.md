---
title: PieSplitCustomPointCollection
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/piesplitcustompointcollection/
---

## PieSplitCustomPointCollection class

 Represents a collection of points for splitting point in a bar-of-pie or pie-of-pie chart with a custom split.
 
### add {#add}

| Name | Description |
| --- | --- |
| add(int) | Adds data point by its index in parent series points collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| dataPointIndex | int | Index of data point in parent series points collection. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Point with the given index was not found". |


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem([ChartDataPoint](../chartdatapoint)) | Adds data point to collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| dataPoint | [ChartDataPoint](../chartdatapoint) | Data point add to. |


---


### clear {#clear}

| Name | Description |
| --- | --- |
| clear() | Removes all items from the IGenericCollection. |


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem([ChartDataPoint](../chartdatapoint)) | Determines whether the IGenericCollection contains a specific value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [ChartDataPoint](../chartdatapoint) | The object to locate in the IGenericCollection. |

 **Result:**
boolean


---


### copyToTArray {#copyToTArray}

| Name | Description |
| --- | --- |
| copyToTArray(com.aspose.slides.IChartDataPoint[], int) | Copies the elements of the IGenericCollection to an Array, starting at a particular Array index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| array | com.aspose.slides.IChartDataPoint[] | The one-dimensional Array that is the destination of the elements copied from IGenericCollection. The Array must have zero-based indexing. |
| arrayIndex | int | The zero-based index in array at which copying begins. |

 **Error**

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | The number of elements in the source IGenericCollection is greater than the available space from arrayIndex to the end of the destination array. |


---


### getSyncRoot {#getSyncRoot}

| Name | Description |
| --- | --- |
| getSyncRoot() | Returns a synchronization root. Read-only Object. |

 **Result:**
Object


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item(int) | Returns chart data point for specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index. |

 **Result:**
[ChartDataPoint](../chartdatapoint)


---


### isReadOnly {#isReadOnly}

| Name | Description |
| --- | --- |
| isReadOnly() | Gets a value indicating whether the IGenericCollection is read-only. Read-only boolean. |

 **Result:**
boolean


---


### isSynchronized {#isSynchronized}

| Name | Description |
| --- | --- |
| isSynchronized() | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

 **Result:**
boolean


---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator() | Returns an enumerator that iterates through the collection. |

 **Result:**



---


### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava() | Returns a java iterator for the entire collection. |

 **Result:**



---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove(int) | Removes item from collection by it index in parent series points collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| dataPointIndex | int | Index of data point in parent series points collection. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | dataPointIndex is negative. |


---


### removeItem {#removeItem}

| Name | Description |
| --- | --- |
| removeItem([ChartDataPoint](../chartdatapoint)) | Removes item from collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| dataPoint | [ChartDataPoint](../chartdatapoint) | Data point remove to. |

 **Result:**
boolean


---


### size {#size}

| Name | Description |
| --- | --- |
| size() | Returns or sets the count of chart data points. Read-only int. |

 **Result:**
int


---


