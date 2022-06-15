---
title: ChartCategory
type: docs
weight: 0
url: /php-java/chartcategory/
---

# ChartCategory class

 Represents chart categories.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getAsCell](/slides/php-java/chartcategory/getascell/)() | IChartDataCell | Returns or sets IChartDataCell object. If category is multi-level then used IChartDataCell object for level "0". Read/write IChartDataCell. |
| [getAsLiteral](/slides/php-java/chartcategory/getasliteral/)() | Object | Returns or sets AsLiteral object. Read/write Object. |
| [getGroupingLevels](/slides/php-java/chartcategory/getgroupinglevels/)() | IChartCategoryLevelsManager | Managed container of the values of the chart category grouping levels. Multi-level category contain more then one grouping level. Grouping levels indexing is zero-based. Read-only IChartCategoryLevelsManager. |
| [getUseCell](/slides/php-java/chartcategory/getusecell/)() | boolean | If true then AsCell property is actual. In other words, worksheet is used for storing category (this case supports a multi-level category). If false then AsLiteral property is actual. In other words, worksheet is NOT used for storing category (and this case doesn't support a multi-level categories). Read-only boolean. For change value of this property (for all categories in collection) set new value to ChartCategoryCollection.UseCells property. |
| [getValue](/slides/php-java/chartcategory/getvalue/)() | Object | If UseCell is true then this property represents AsCell.Value property. If UseCell is false then this property represents AsLiteral property. Read/write Object. |
| [remove](/slides/php-java/chartcategory/remove/)() | void | Removes category from chart. |
| [setAsCell](/slides/php-java/chartcategory/setascell/)(IChartDataCell) | void | Returns or sets IChartDataCell object. If category is multi-level then used IChartDataCell object for level "0". Read/write IChartDataCell. |
| [setAsLiteral](/slides/php-java/chartcategory/setasliteral/)(Object) | void | Returns or sets AsLiteral object. Read/write Object. |
| [setValue](/slides/php-java/chartcategory/setvalue/)(Object) | void | If UseCell is true then this property represents AsCell.Value property. If UseCell is false then this property represents AsLiteral property. Read/write Object. |
