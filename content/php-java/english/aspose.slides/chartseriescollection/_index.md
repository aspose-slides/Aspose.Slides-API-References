---
title: ChartSeriesCollection
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/chartseriescollection/
---

## ChartSeriesCollection class

 Represents collection of   ChartSeries
 
### add {#add}

| Name | Description |
| --- | --- |
| add (int) | Creates new chart series and adds it to the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| type | int | Type of series |

 **Returns:**
[ChartSeries](../chartseries)


---


### add {#add}

| Name | Description |
| --- | --- |
| add ([ChartDataCell](../chartdatacell), int) | Creates new chart series from ChartDataCell and adds it to the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| cellWithSeriesName | [ChartDataCell](../chartdatacell) | Cell which contain series name. |
| type | int | Type set type of series If chart series careted from same cell already in collection then method adds nothing and returns it's index. |

 **Returns:**
[ChartSeries](../chartseries)


---


### add {#add}

| Name | Description |
| --- | --- |
| add ([ChartCellCollection](../chartcellcollection), int) | Creates new chart series from ChartCellCollection and adds it to the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| cellsWithSeriesName | [ChartCellCollection](../chartcellcollection) | Cells which contain series name. |
| type | int | Type set type of series If chart series careted from same cell already in collection then method adds nothing and returns it's index. |

 **Returns:**
[ChartSeries](../chartseries)


---


### add {#add}

| Name | Description |
| --- | --- |
| add (String, int) | Creates new chart series from value and adds it to the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Series name. |
| type | int | Type set type of series |

 **Returns:**
[ChartSeries](../chartseries)


---


### clear {#clear}

| Name | Description |
| --- | --- |
| clear () | Removes all controls from the collection. |

 **Returns:**
void


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
| get_Item (int) | Gets the element at the specified index. |

 **Returns:**
[ChartSeries](../chartseries)

 **Exception**

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentOutOfRangeException | index is not a valid index in the IList. |


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([ChartSeries](../chartseries)) | Searches for the specified ChartSeries and returns the zero-based index of the first occurrence within the entire Collection |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| value | [ChartSeries](../chartseries) | Chart series value. |

 **Returns:**
int


---


### insert {#insert}

| Name | Description |
| --- | --- |
| insert (int, int) | Creates new chart series and inserts it into the collection. |

 **Returns:**
[ChartSeries](../chartseries)


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


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([ChartSeries](../chartseries)) | Removes the specified value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| value | [ChartSeries](../chartseries) | The value. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | The value parameter was not found in the collection. |


---


### removeAt {#removeAt}

| Name | Description |
| --- | --- |
| removeAt (int) | Removes an ActiveX control stored at specified position from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of a control to remove. |

 **Returns:**
void


---


### size {#size}

| Name | Description |
| --- | --- |
| size () | Returns a number of objects in the collection. Read-only int. |

 **Returns:**
int


---


