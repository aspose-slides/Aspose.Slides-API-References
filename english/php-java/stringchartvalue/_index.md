---
title: StringChartValue
type: docs
weight: 0
url: /php-java/stringchartvalue/
---

# StringChartValue class

 Represent string value which can be stored in pptx presentation document in two ways:
 1) in cell/cells of workbook related to chart;
 2) as literal value.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getAsCells](/php-java/stringchartvalue/getascells/)() | IChartCellCollection | Null value assigning is not allowed. Returning value always is not null. Read/write IChartCellCollection. |
| [getAsLiteralString](/php-java/stringchartvalue/getasliteralstring/)() | String | Returns or sets value as literal string. Read/write String. |
| [getCellsAddressInWorkbook](/php-java/stringchartvalue/getcellsaddressinworkbook/)() | String | If DataSourceType property is DataSourceType.Worksheet then this method returns address of the cells in workbook which represent the string data. Otherwise return empty string. |
| [getData](/php-java/stringchartvalue/getdata/)() | Object | Returns or sets Data object. Read/write Object. |
| [setAsCells](/php-java/stringchartvalue/setascells/)(IChartCellCollection) | void | Null value assigning is not allowed. Returning value always is not null. Read/write IChartCellCollection. |
| [setAsLiteralString](/php-java/stringchartvalue/setasliteralstring/)(String) | void | Returns or sets value as literal string. Read/write String. |
| [setData](/php-java/stringchartvalue/setdata/)(Object) | void | Returns or sets Data object. Read/write Object. |
| [setFromOneCell](/php-java/stringchartvalue/setfromonecell/)(IChartDataCell) | void | Sets value from specified cell. |
| [toString](/php-java/stringchartvalue/tostring/)() | String | Returns string value data. Return null if DataSourceType is false and no string value was assigned. |
