---
title: IChartSeriesGroupCollection class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/
---


## IChartSeriesGroupCollection class

Represents the collection of groups of combinable series.

The IChartSeriesGroupCollection type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [as_i_collection](/slides/python-net/aspose.slides.charts/as_i_collection) |  |
| [as_i_enumerable](/slides/python-net/aspose.slides.charts/as_i_enumerable) |  |

## Indexer

| Name | Description |
| :- | :- |
| [index] |  |


### Remarks


            1) Each group of series contains series with combinable types. Groups of 
            combinable series types defined and described with CombinableSeriesTypesGroup 
            enum.
            Also each group of series contains series witch is plotted whether 
            on primary axes or on secondary axes (not both cases in one group).
            So, principle of series grouping is a grouping by type groups mentioned 
            above and by primary/secondary plotting type.
            
            2) Group of series contains some series properties which is common for 
            each series in group ("series group properties").
            "Series group properties" in ChartSeriesGroup class is read/write.
            Each of "series group properties" can have a read-only projection in ChartSeries class.
            


