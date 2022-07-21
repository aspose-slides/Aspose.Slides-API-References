---
title: ChartSeriesGroupCollection
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/chartseriesgroupcollection/
---

## ChartSeriesGroupCollection class

 Represents the collection of groups of combinable series.
 
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
 

## Methods

| Name | Description |
| --- | --- |
| [copyTo](copyto)(Array, int) |  |
| [getParent_Immediate](getparent_immediate)() |  |
| [getSyncRoot](getsyncroot)() | Returns a synchronization root. Read-only Object. |
| [get_Item](get_item)([ChartSeries](../chartseries)) | Gets the series group by series. |
| [get_Item](get_item)(int) | Gets the series group by index. |
| [isSynchronized](issynchronized)() | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |
| [iterator](iterator)() | Returns an enumerator that iterates through the collection. |
| [iteratorJava](iteratorjava)() | Returns a java iterator for the entire collection. |
| [size](size)() | Returns count. Read-only int. |
