---
title: ChartCellCollection
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/chartcellcollection/
---

## ChartCellCollection class

 Represents collection of a cells with data.
 
### add {#add}

| Name | Description |
| --- | --- |
| add ([ChartDataCell](../chartdatacell)) | Add new cell to the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| cell | [ChartDataCell](../chartdatacell) | New cell to add. |

 **Returns:**
void


---


### add {#add}

| Name | Description |
| --- | --- |
| add (Object) | Creates ChartDataCell from specified value and adds it to the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| value | Object | The value. This method adds worksheet with name AUTO_DATA and adds all values there. If you use ChartDataWorkbook to add or edit Cell values, be sure that you do not use this worksheet Maximum number of values added using this method must not exceed 16711680 |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.InvalidOperationException | if limit exceeded |


---


### getCellsAddress {#getCellsAddress}

| Name | Description |
| --- | --- |
| getCellsAddress () | Returns address of the set of cells in workbook. |

 **Returns:**
String


---


### getConcatenatedValuesFromCells {#getConcatenatedValuesFromCells}

| Name | Description |
| --- | --- |
| getConcatenatedValuesFromCells () | Concatenation string from all cells string values. |

 **Returns:**
String


---


### getCount {#getCount}

| Name | Description |
| --- | --- |
| getCount () | Gets the count of cells in collection. Read-only int. |

 **Returns:**
int


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | Returns a cell (IChartDataCell) by index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of a cell. |

 **Returns:**
[ChartDataCell](../chartdatacell)


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
| removeAt (int) | Removes a cell from the collection by index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of a cell to remove. |

 **Returns:**
void


---


