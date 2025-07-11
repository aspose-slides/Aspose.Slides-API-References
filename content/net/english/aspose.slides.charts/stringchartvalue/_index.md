---
title: StringChartValue
second_title: Aspose.Sildes for .NET API Reference
description: Represent string value which can be stored in pptx presentation document in two ways 1 in cell/cells of workbook related to chart 2 as literal value.
type: docs
weight: 2390
url: /aspose.slides.charts/stringchartvalue/
---

## StringChartValue class

Represent string value which can be stored in pptx presentation document in two ways: 1) in cell/cells of workbook related to chart; 2) as literal value.

```csharp
public class StringChartValue : BaseChartValue, IStringChartValue
```

## Properties

| Name | Description |
| --- | --- |
| [AsCells](../../aspose.slides.charts/stringchartvalue/ascells) { get; set; } | Null value assigning is not allowed. Returning value always is not null. Read/write [`IChartCellCollection`](../ichartcellcollection). |
| [AsLiteralString](../../aspose.slides.charts/stringchartvalue/asliteralstring) { get; set; } | Returns or sets value as literal string. Read/write String. |
| override [Data](../../aspose.slides.charts/stringchartvalue/data) { get; set; } | Returns or sets Data object. Read/write Object. |
| [DataSourceType](../../aspose.slides.charts/basechartvalue/datasourcetype) { get; set; } | Specifies whether AsCell, AsCells, AsLiteralString or AsLiteralDouble property is actual in descendants. In other words it specifies the type of value of the Data property. Read/write [`DataSourceType`](../datasourcetype). |

## Methods

| Name | Description |
| --- | --- |
| [GetCellsAddressInWorkbook](../../aspose.slides.charts/stringchartvalue/getcellsaddressinworkbook)() | If DataSourceType property is DataSourceType.Worksheet then this method returns address of the cells in workbook which represent the string data. Otherwise return empty string. |
| [SetFromOneCell](../../aspose.slides.charts/stringchartvalue/setfromonecell)(IChartDataCell) | Sets value from specified cell. |
| override [ToString](../../aspose.slides.charts/stringchartvalue/tostring)() | Returns string value data. Return null if DataSourceType is false and no string value was assigned. |

### See Also

* class [BaseChartValue](../basechartvalue)
* interface [IStringChartValue](../istringchartvalue)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
