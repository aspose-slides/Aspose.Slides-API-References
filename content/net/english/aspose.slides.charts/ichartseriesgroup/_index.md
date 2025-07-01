---
title: IChartSeriesGroup
second_title: Aspose.Sildes for .NET API Reference
description: Represents group of series.
type: docs
weight: 1930
url: /aspose.slides.charts/ichartseriesgroup/
---

## IChartSeriesGroup interface

Represents group of series.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Properties

| Name | Description |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Allows to get base IChartComponent interface. Read-only [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Specifies how the bubble size values are represented on the bubble chart. Read/write [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). Read/write Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Specifies the size of the hole in a doughnut chart (can be between 10 and 90 percents of the size of the plot area.). Read/write Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Gets or sets the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). Read/write UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart. Read/write UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Specifies the space between bar or column clusters, as a percentage of the bar or column width. Read/write UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | True if chart has series lines. Applied to stacked bar and OfPie charts. Read/write Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Specifies HiLowLines format. HiLowLines applied with HiLowClose, OpenHiLowClose, VolumeHiLowClose and VolumeOpenHiLowClose chart types. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Specifies that each data marker in the series has a different color. Read/write Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Gets the element at the specified index. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Specifies how much bars and columns shall overlap on 2-D charts, as a percentage (from -100% to 100%). - -100%: Maximum spacing (bars are completely separated). - 0%: Bars are placed side by side without overlap or spacing. - 100%: Maximum overlap (bars completely overlap each other). This property is read/write SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Read/write [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | The custom split information for a pie-of-pie or bar-of-pie chart with a custom split. Contains data points that shall be drawn in the second pie or bar in a pie-of-pie or bar-of-pie chart. Read-only [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. Read/write Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Indicates if series of this group is plotted on secondary axis. Read-only Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). Read/write UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Returns a readonly collection of chart series. Read-only [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Returns a type of this series group. Read-only [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Provede access to up/down bars of Line- or Stock-chart. Read-only [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Remarks

1) See summary and remarks for ChartSeriesGroupCollection class and CombinableSeriesTypesGroup enum. 2) Group of series contains some series properies whitch is common for each series in group ("series group properties"). "Series group properties" in ChartSeriesGroup class is read/write. Each of "series group properties" can have a read-only projection in ChartSeries class.

### See Also

* interface [IChartComponent](../ichartcomponent)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
