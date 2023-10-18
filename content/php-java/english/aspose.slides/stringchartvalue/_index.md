---
title: StringChartValue
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/stringchartvalue/
---

## StringChartValue class

 Represent string value which can be stored in pptx presentation document in two ways:
 1) in cell/cells of workbook related to chart;
 2) as literal value.
 
### getAsCells {#getAsCells}

| Name | Description |
| --- | --- |
| getAsCells () | Null value assigning is not allowed. Returning value always is not null. Read/write IChartCellCollection. |

 **Returns:**
[ChartCellCollection](../chartcellcollection)


---


### getAsLiteralString {#getAsLiteralString}

| Name | Description |
| --- | --- |
| getAsLiteralString () | Returns or sets value as literal string. Read/write String. |

 **Returns:**
String


---


### getCellsAddressInWorkbook {#getCellsAddressInWorkbook}

| Name | Description |
| --- | --- |
| getCellsAddressInWorkbook () | If DataSourceType property is DataSourceType.Worksheet then this method returns address of the cells in workbook which represent the string data. Otherwise return empty string. |

 **Returns:**
String


---


### getData {#getData}

| Name | Description |
| --- | --- |
| getData () | Returns or sets Data object. Read/write Object. |

 **Returns:**
Object


---


### setAsCells {#setAsCells}

| Name | Description |
| --- | --- |
| setAsCells ([ChartCellCollection](../chartcellcollection)) | Null value assigning is not allowed. Returning value always is not null. Read/write IChartCellCollection. |

 **Returns:**
void


---


### setAsLiteralString {#setAsLiteralString}

| Name | Description |
| --- | --- |
| setAsLiteralString (String) | Returns or sets value as literal string. Read/write String. |

 **Returns:**
void


---


### setData {#setData}

| Name | Description |
| --- | --- |
| setData (Object) | Returns or sets Data object. Read/write Object. |

 **Returns:**
void


---


### setFromOneCell {#setFromOneCell}

| Name | Description |
| --- | --- |
| setFromOneCell ([ChartDataCell](../chartdatacell)) | Sets value from specified cell. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| cell | [ChartDataCell](../chartdatacell) | Cell. |

 **Returns:**
void


---


### toString {#toString}

| Name | Description |
| --- | --- |
| toString () | Returns string value data. Return null if DataSourceType is false and no string value was assigned. |

 **Returns:**
String


---


