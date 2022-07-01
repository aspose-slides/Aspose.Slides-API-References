---
title: ChartCategory
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/chartcategory/
---

## ChartCategory class

 Represents chart categories.
 

## Methods

| Name | Description |
| --- | --- |
| [getAsCell](getascell)() | Returns or sets IChartDataCell object. If category is multi-level then used IChartDataCell object for level "0". Read/write IChartDataCell. |
| [getAsLiteral](getasliteral)() | Returns or sets AsLiteral object. Read/write Object. |
| [getGroupingLevels](getgroupinglevels)() | Managed container of the values of the chart category grouping levels. Multi-level category contain more then one grouping level. Grouping levels indexing is zero-based. Read-only IChartCategoryLevelsManager. |
| [getUseCell](getusecell)() | If true then AsCell property is actual. In other words, worksheet is used for storing category (this case supports a multi-level category). If false then AsLiteral property is actual. In other words, worksheet is NOT used for storing category (and this case doesn't support a multi-level categories). Read-only boolean. For change value of this property (for all categories in collection) set new value to ChartCategoryCollection.UseCells property. |
| [getValue](getvalue)() | If UseCell is true then this property represents AsCell.Value property. If UseCell is false then this property represents AsLiteral property. Read/write Object. |
| [remove](remove)() | Removes category from chart. |
| [setAsCell](setascell)(ChartDataCell) | Returns or sets IChartDataCell object. If category is multi-level then used IChartDataCell object for level "0". Read/write IChartDataCell. |
| [setAsLiteral](setasliteral)(Object) | Returns or sets AsLiteral object. Read/write Object. |
| [setValue](setvalue)(Object) | If UseCell is true then this property represents AsCell.Value property. If UseCell is false then this property represents AsLiteral property. Read/write Object. |
