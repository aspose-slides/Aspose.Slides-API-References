---
title: DataLabelCollection class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/datalabelcollection/
---


## DataLabelCollection class

Represents a series labels.

The DataLabelCollection type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`chart`](/slides/python-net/aspose.slides.charts/datalabelcollection/chart/) | Returns the parent chart.<br/>            Read-only [`IChart`](/slides/python-net/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/aspose.slides.charts/datalabelcollection/is_visible/) | False means that data label is not visible by default (and so all <br/>            Show*-flags (ShowValue, ...) of the DefaultDataLabelFormat property are false).<br/>            Read-only **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/aspose.slides.charts/datalabelcollection/count_of_visible_data_labels/) | Gets the number of visible data labels in the collection.<br/>            Read-only **int**. |
| [`count`](/slides/python-net/aspose.slides.charts/datalabelcollection/count/) | Gets the number of all data labels in the collection.<br/>            Read-only **int**. |
| [`default_data_label_format`](/slides/python-net/aspose.slides.charts/datalabelcollection/default_data_label_format/) | Gets the default data label format.<br/>            Read-only [`IDataLabelFormat`](/slides/python-net/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/aspose.slides.charts/datalabelcollection/leader_lines_format/) | Represents data labels leader lines format.<br/>             Read-only [`IChartLinesFormat`](/slides/python-net/aspose.slides.charts/ichartlinesformat). |
| [`parent_series`](/slides/python-net/aspose.slides.charts/datalabelcollection/parent_series/) | Gets the parent series.<br/>            Read-only [`IChartSeries`](/slides/python-net/aspose.slides.charts/ichartseries). |
| [`slide`](/slides/python-net/aspose.slides.charts/datalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/aspose.slides.charts/datalabelcollection/presentation/) |  |

Gets the data label for the data point with the specified index.

## Indexer

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/aspose.slides.charts/datalabelcollection/__getitem__/) |  |

## Methods

| Method | Description |
| :- | :- |
| [`hide`](/slides/python-net/aspose.slides.charts/datalabelcollection/hide/#) | Make data label hidden by default by setting all Show*-flags (ShowValue, ...) of the <br/>            DefaultDataLabelFormat property to false state.<br/>            IsVisible will be false after this. |
| [`index_of`](/slides/python-net/aspose.slides.charts/datalabelcollection/index_of/#idatalabel) | Returns an index of the specified DataLabel in the collection. |


### See Also
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)

