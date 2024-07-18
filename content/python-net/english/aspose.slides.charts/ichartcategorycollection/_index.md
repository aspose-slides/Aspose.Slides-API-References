---
title: IChartCategoryCollection class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/ichartcategorycollection/
---


## IChartCategoryCollection class

Represents collection of [`IChartCategory`](/slides/python-net/aspose.slides.charts/ichartcategory)

The IChartCategoryCollection type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`use_cells`](/slides/python-net/aspose.slides.charts/ichartcategorycollection/use_cells/) | If true then worksheet is used for storing categories (this case supports a multi-level categories).<br/>            If false then worksheet is NOT used for storing values (and this case doesn't support a <br/>            multi-level categories).<br/>            Read/write **bool**. |
| [`grouping_level_count`](/slides/python-net/aspose.slides.charts/ichartcategorycollection/grouping_level_count/) | Returns count of category grouping levels used.<br/>            Is more then one for multilevel categories.<br/>            Read-only **int**. |

Gets the element at the specified index.

## Indexer

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/aspose.slides.charts/ichartcategorycollection/__getitem__/) |  |

## Methods

| Method | Description |
| :- | :- |
| [`add`](/slides/python-net/aspose.slides.charts/ichartcategorycollection/add/#ichartdatacell) | If category exists in collection, return it. Else creates new chart category from<br/>[`IChartDataCell`](/slides/python-net/aspose.slides.charts/ichartdatacell) and adds it to the collection. |
| [`add`](/slides/python-net/aspose.slides.charts/ichartcategorycollection/add/#any) | Creates new [`IChartCategory`](/slides/python-net/aspose.slides.charts/ichartcategory) from value and adds it to the collection. |
| [`index_of`](/slides/python-net/aspose.slides.charts/ichartcategorycollection/index_of/#ichartcategory) | Searches for the specified [`IChartCategory`](/slides/python-net/aspose.slides.charts/ichartcategory) and returns the zero-based index of the first occurrence within the entire Collection |
| [`remove`](/slides/python-net/aspose.slides.charts/ichartcategorycollection/remove/#ichartcategory) | Removes the specified value. |
| [`remove_at`](/slides/python-net/aspose.slides.charts/ichartcategorycollection/remove_at/#int) | Removes the element at the given index. |
| [`clear`](/slides/python-net/aspose.slides.charts/ichartcategorycollection/clear/#) | Removes all elements from the collection. |


### See Also
* class [`IChartCategory`](/slides/python-net/aspose.slides.charts/ichartcategory)
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)

