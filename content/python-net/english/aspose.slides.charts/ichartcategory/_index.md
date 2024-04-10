---
title: IChartCategory
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/ichartcategory/
---


IChartCategory class

Represents chart categories.

The IChartCategory type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [use_cell](/slides/python-net/aspose.slides.charts/ichartcategory/use_cell/) | If true then AsCell property is actual. In other words, worksheet is used for <br/>            storing category (this case supports a multi-level category).<br/>            If false then AsLiteral property is actual. In other words, worksheet is NOT used <br/>            for storing category (and this case doesn't support a multi-level categories).<br/>            Read-only :py:class:`bool`. |
| [as_cell](/slides/python-net/aspose.slides.charts/ichartcategory/as_cell/) | Returns or sets IChartDataCell object.<br/>            If category is multi-level then used IChartDataCell object for level "0".<br/>            Read/write :py:class:`aspose.slides.charts.IChartDataCell`. |
| [as_literal](/slides/python-net/aspose.slides.charts/ichartcategory/as_literal/) | Returns or sets AsLiteral if UseCell is false.<br/>            Read/write :py:class:`any`. |
| [value](/slides/python-net/aspose.slides.charts/ichartcategory/value/) | If UseCell is true then this property represents AsCell.Value property.<br/>            If UseCell is false then this property represents AsLiteral property.<br/>            Read/write :py:class:`any`. |
| [grouping_levels](/slides/python-net/aspose.slides.charts/ichartcategory/grouping_levels/) | Managed container of the values of the chart category grouping levels.<br/>            Multi-level category contain more then one grouping level.<br/>            Grouping levels indexing is zero-based.<br/>            Read-only :py:class:`aspose.slides.charts.IChartCategoryLevelsManager`. |

## Methods

| Method | Description |
| :- | :- |
| [remove](/slides/python-net/aspose.slides.charts/ichartcategory/ichartcategory/#/) | Removes category from chart. |

