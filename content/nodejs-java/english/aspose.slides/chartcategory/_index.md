---
title: ChartCategory
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/chartcategory/
---

## ChartCategory class

 Represents chart categories.
 
### getAsCell {#getAsCell}

| Name | Description |
| --- | --- |
| getAsCell () | Returns or sets IChartDataCell object. If category is multi-level then used IChartDataCell object for level "0". Read/write IChartDataCell. |

 **Returns:**
[ChartDataCell](../chartdatacell)


---


### getAsLiteral {#getAsLiteral}

| Name | Description |
| --- | --- |
| getAsLiteral () | Returns or sets AsLiteral object. Read/write Object. |

 **Returns:**
Object


---


### getGroupingLevels {#getGroupingLevels}

| Name | Description |
| --- | --- |
| getGroupingLevels () | Managed container of the values of the chart category grouping levels. Multi-level category contain more then one grouping level. Grouping levels indexing is zero-based. Read-only IChartCategoryLevelsManager. |

 **Returns:**
[ChartCategoryLevelsManager](../chartcategorylevelsmanager)


---


### getUseCell {#getUseCell}

| Name | Description |
| --- | --- |
| getUseCell () | If true then AsCell property is actual. In other words, worksheet is used for storing category (this case supports a multi-level category). If false then AsLiteral property is actual. In other words, worksheet is NOT used for storing category (and this case doesn't support a multi-level categories). Read-only boolean. For change value of this property (for all categories in collection) set new value to ChartCategoryCollection.UseCells property. |

 **Returns:**
boolean


---


### getValue {#getValue}

| Name | Description |
| --- | --- |
| getValue () | If UseCell is true then this property represents AsCell.Value property. If UseCell is false then this property represents AsLiteral property. Read/write Object. |

 **Returns:**
Object


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove () | Removes category from chart. |

 **Error**

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if category is already removed from chart. |


---


### setAsCell {#setAsCell}

| Name | Description |
| --- | --- |
| setAsCell ([ChartDataCell](../chartdatacell)) | Returns or sets IChartDataCell object. If category is multi-level then used IChartDataCell object for level "0". Read/write IChartDataCell. |


---


### setAsLiteral {#setAsLiteral}

| Name | Description |
| --- | --- |
| setAsLiteral (Object) | Returns or sets AsLiteral object. Read/write Object. |


---


### setValue {#setValue}

| Name | Description |
| --- | --- |
| setValue (Object) | If UseCell is true then this property represents AsCell.Value property. If UseCell is false then this property represents AsLiteral property. Read/write Object. |


---


