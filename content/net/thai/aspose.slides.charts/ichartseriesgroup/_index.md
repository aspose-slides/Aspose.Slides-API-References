---
title: IChartSeriesGroup
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แสดงถึงกลุ่มของชุดข้อมูล.
type: docs
weight: 1950
url: /th/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup อินเทอร์เฟซ

Represents group of series.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Allows to get base IChartComponent interface. อ่านอย่างเดียว [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Specifies how the bubble size values are represented on the bubble chart. อ่าน/เขียน [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). อ่าน/เขียน Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Specifies the size of the hole in a doughnut chart (can be between 10 and 90 percents of the size of the plot area.). อ่าน/เขียน Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Gets or sets the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). อ่าน/เขียน UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart. อ่าน/เขียน UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Specifies the space between bar or column clusters, as a percentage of the bar or column width. อ่าน/เขียน UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | True if chart has series lines. Applied to stacked bar and OfPie charts. อ่าน/เขียน Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Specifies HiLowLines format. HiLowLines applied with HiLowClose, OpenHiLowClose, VolumeHiLowClose and VolumeOpenHiLowClose chart types. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Specifies that each data marker in the series has a different color. อ่าน/เขียน Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Gets the element at the specified index. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Specifies how much bars and columns shall overlap on 2-D charts, as a percentage (from -100% to 100%). -100%: Maximum spacing (bars are completely separated). 0%: Bars are placed side by side without overlap or spacing. 100%: Maximum overlap (bars completely overlap each other). This property is read/write SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. อ่าน/เขียน [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | The custom split information for a pie-of-pie or bar-of-pie chart with a custom split. Contains data points that shall be drawn in the second pie or bar in a pie-of-pie or bar-of-pie chart. อ่านอย่างเดียว [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. อ่าน/เขียน Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Indicates if series of this group is plotted on secondary axis. อ่านอย่างเดียว Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). อ่าน/เขียน UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Returns a readonly collection of chart series. อ่านอย่างเดียว [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Returns a type of this series group. อ่านอย่างเดียว [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Provede access to up/down bars of Line- or Stock-chart. อ่านอย่างเดียว [`IUpDownBarsManager`](../iupdownbarsmanager). |

### หมายเหตุ

1) ดูสรุปและหมายเหตุสำหรับคลาส ChartSeriesGroupCollection และ enum CombinableSeriesTypesGroup. 2) กลุ่มของชุดข้อมูลมีคุณสมบัติบางอย่างของชุดข้อมูลที่เป็นสากลสำหรับแต่ละชุดในกลุ่ม ("series group properties"). "Series group properties" ในคลาส ChartSeriesGroup เป็นอ่าน/เขียน. แต่ละ "series group properties" สามารถมีการฉายออกเป็นอ่านอย่างเดียวในคลาส ChartSeries.

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IChartComponent](../ichartcomponent)
* เนมสเปซ [Aspose.Slides.Charts](../../aspose.slides.charts)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->