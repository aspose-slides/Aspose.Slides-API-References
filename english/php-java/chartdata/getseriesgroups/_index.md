---
title: getSeriesGroups
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 80
url: /php-java/chartdata/getseriesgroups/
---

## getSeriesGroups()  method

 Gets the groups of series.
 Read-only  IChartSeriesGroupCollection.
 
 1) Each group of series contains series with combinable types. Groups of 
 combinable series types defined and described with CombinableSeriesTypesGroup 
 enum.
 Also each group of series contains series witch is plotted whether 
 on primary axes or on secondary axes (not both cases in one group).
 So, principle of series grouping is a grouping by type groups mentioned 
 above and by primary/secondary plotting type.
 2) Group of series contains some series properies whitch is common for 
 each series in group ("series group properties").
 "Series group properties" in ChartSeriesGroup class is read/write.
 Each of "series group properties" can have a read-only projection in ChartSeries class.
 

### Returns
ChartSeriesGroupCollection


---


