---
title: StringChartValue
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/stringchartvalue/
---

## StringChartValue class

 Represent string value which can be stored in pptx presentation document in two ways:
 1) in cell/cells of workbook related to chart;
 2) as literal value.
 
| [getAsCells] () Null value assigning is not allowed. Returning value always is not null. Read/write IChartCellCollection. |

### Result
[ChartCellCollection]


---


| [getAsLiteralString] () Returns or sets value as literal string. Read/write String. |

### Result
String


---


| [getCellsAddressInWorkbook] () If DataSourceType property is DataSourceType.Worksheet then this function returns address of the cells in workbook which represent the string data. Otherwise return empty string. |

### Result
String


---


| [getData] () Returns or sets Data object. Read/write Object. |

### Result
Object


---


| [setAsCells] ([ChartCellCollection]) Null value assigning is not allowed. Returning value always is not null. Read/write IChartCellCollection. |


---


| [setAsLiteralString] ([String]) Returns or sets value as literal string. Read/write String. |


---


| [setData] ([Object]) Returns or sets Data object. Read/write Object. |


---


| [setFromOneCell] ([ChartDataCell]) Sets value from specified cell. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| cell | [ChartDataCell] | Cell. |


---


| [toString] () Returns string value data. Return null if DataSourceType is false and no string value was assigned. |

### Result
String


---


