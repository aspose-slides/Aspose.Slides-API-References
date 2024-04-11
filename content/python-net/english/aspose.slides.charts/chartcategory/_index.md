---
title: ChartCategory
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/chartcategory/
---


ChartCategory class

Represents chart categories.

The ChartCategory type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [use_cell](/slides/python-net/aspose.slides.charts/chartcategory/use_cell/) | If true then AsCell property is actual. In other words, worksheet is used for <br/>            storing category (this case supports a multi-level category).<br/>            If false then AsLiteral property is actual. In other words, worksheet is NOT used <br/>            for storing category (and this case doesn't support a multi-level categories).<br/>            Read-only <br/>.NET type System.Boolean<br/>. |
| [as_cell](/slides/python-net/aspose.slides.charts/chartcategory/as_cell/) | Returns or sets IChartDataCell object.<br/>            If category is multi-level then used IChartDataCell object for level "0".<br/>            Read/write <br/>[`IChartDataCell`](/slides/python-net/aspose.slides.charts/ichartdatacell)<br/>. |
| [as_literal](/slides/python-net/aspose.slides.charts/chartcategory/as_literal/) | Returns or sets AsLiteral object.<br/>            Read/write <br/>.NET type System.Object<br/>. |
| [value](/slides/python-net/aspose.slides.charts/chartcategory/value/) | If UseCell is true then this property represents AsCell.Value property.<br/>            If UseCell is false then this property represents AsLiteral property.<br/>            Read/write <br/>.NET type System.Object<br/>. |
| [grouping_levels](/slides/python-net/aspose.slides.charts/chartcategory/grouping_levels/) | Managed container of the values of the chart category grouping levels.<br/>            Multi-level category contain more then one grouping level.<br/>            Grouping levels indexing is zero-based.<br/>            Read-only <br/>[`IChartCategoryLevelsManager`](/slides/python-net/aspose.slides.charts/ichartcategorylevelsmanager)<br/>. |

## Methods

| Method | Description |
| :- | :- |
| [remove](/slides/python-net/aspose.slides.charts/chartcategory/chartcategory/#/) | Removes category from chart. |

