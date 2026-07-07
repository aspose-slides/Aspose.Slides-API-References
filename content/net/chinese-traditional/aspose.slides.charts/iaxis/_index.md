---
title: IAxis
second_title: Aspose.Sildes 的 .NET API 參考
description: 封裝表示圖表軸的物件。
type: docs
weight: 1710
url: /zh-hant/aspose.slides.charts/iaxis/
---
## IAxis 介面

封裝表示圖表軸的物件。

```csharp
public interface IAxis : IFormattedTextContainer
```

## 屬性

| Name | Description |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | 指定軸的實際主要單位。請先呼叫 IChart.ValidateChartLayout() 方法以取得實際值。 |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | 指定軸的實際主要單位比例。請先呼叫 IChart.ValidateChartLayout() 方法以取得實際值。 |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | 指定軸上的實際最大值。請先呼叫 IChart.ValidateChartLayout() 方法以取得實際值。 |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | 指定軸的實際次要單位。請先呼叫 IChart.ValidateChartLayout() 方法以取得實際值。 |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | 指定軸的實際次要單位比例。請先呼叫 IChart.ValidateChartLayout() 方法以取得實際值。 |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | 指定軸上的實際最小值。請先呼叫 IChart.ValidateChartLayout() 方法以取得實際值。 |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | 表示類別軸（分箱）的彙總類型。適用於類別。僅在 Histogram 或 HistogramPareto 系列中使用。 |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | 允許取得基礎 IFormattedTextContainer 介面。唯讀 [`IFormattedTextContainer`](../iformattedtextcontainer)。 |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | 表示數值軸是否在類別之間交叉類別軸。此屬性僅適用於類別軸，且不適用於 3-D 圖表。可讀寫 Boolean。 |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | 指定日期軸上所表示的最小時間單位。可讀寫 [`TimeUnitType`](../timeunittype)。 |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | 當 AggregationType 屬性值設定為 AxisAggregationType.ByBinWidth 時，指定分箱寬度。適用於類別軸。僅在 Histogram 或 HistogramPareto 系列中使用。 |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | 指定類別軸的類型。可讀寫 [`CategoryAxisType`](./categoryaxistype)。 |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | 表示垂直於該軸的軸交叉點。可讀寫 Single。 |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | 表示在指定軸上另一軸交叉的位置之 CrossType。可讀寫 [`CrossesType`](../crossestype)。 |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | 指定數值軸顯示單位的縮放值。可讀寫 [`DisplayUnitType`](../displayunittype)。 |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | 表示軸的格式。唯讀 [`IAxisFormat`](../iaxisformat)。 |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | 決定軸是否具有可見標題。可讀寫 Boolean。 |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | 表示軸的主要單位是否自動分配。可讀寫 Boolean。 |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | 表示最大值是否自動分配。可讀寫 Boolean。 |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | 表示軸的次要單位是否自動分配。可讀寫 Boolean。 |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | 表示最小值是否自動分配。可讀寫 Boolean。 |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | 指定自動溢出分箱值。若為 false，使用 OverflowBin 屬性。 |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | 指定自動刻度標籤間距值。若為 false，使用 TickLabelSpacing 屬性。可讀寫 Boolean。 |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | 指定自動刻度標記間距值。若為 false，使用 TickMarksSpacing 屬性。可讀寫 Boolean。 |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | 指定自動下溢分箱值。若為 false，使用 UnderflowBin 屬性。 |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | 表示數值軸的比例類型是否為對數。可讀寫 Boolean。 |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | 表示格式是否連結至來源資料。可讀寫 Boolean。 |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | 指定是否套用溢出分箱。使用 IsAutomaticOverflowBin 與 OverflowBin 來調整溢出分箱值。 |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | 表示 MS PowerPoint 是否從最後到第一繪製資料點。可讀寫 Boolean。 |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | 指定是否套用下溢分箱。使用 IsAutomaticUnderflowBin 與 UnderflowBin 來調整下溢分箱值。 |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | 表示軸是否可見。可讀寫 Boolean。 |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | 指定標籤與軸的距離。適用於類別或日期軸。值必須介於 0% 到 1000% 之間。可讀寫 UInt16。 |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | 表示對數底。預設值為 10。可讀寫 Double。 |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | 表示圖表軸上主要格線的格式。唯讀 [`IChartLinesFormat`](../ichartlinesformat)。 |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | 表示指定軸之主要刻度標記的類型。可讀寫 [`TickMarkType`](../tickmarktype)。 |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | 表示日期或數值軸的主要單位。可讀寫 Double。 |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | 表示日期軸的主要單位比例。可讀寫 [`TimeUnitType`](../timeunittype)。 |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | 表示數值軸的最大值。可讀寫 Double。 |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | 表示圖表軸上次要格線的格式。唯讀 [`IChartLinesFormat`](../ichartlinesformat)。 |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | 表示指定軸之次要刻度標記的類型。可讀寫 [`TickMarkType`](../tickmarktype)。 |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | 表示日期或數值軸的次要單位。可讀寫 Double。 |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | 表示日期軸的主要單位比例。可讀寫 [`TimeUnitType`](../timeunittype)。 |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | 表示數值軸的最小值。可讀寫 Double。 |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | 表示軸標籤的格式字串。可讀寫 String。 |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | 當 AggregationType 屬性值設定為 AxisAggregationType.ByNumberOfBins 時，指定分箱數量。適用於類別軸。僅在 Histogram 或 HistogramPareto 系列中使用。 |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | 指定溢出分箱的自訂值。當 IsAutomaticOverflowBin 屬性設定為 false 且 IsOverflowBin 屬性為 true 時套用。 |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | 表示軸的位置。可讀寫 [`AxisPositionType`](../axispositiontype)。 |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | 表示是否顯示主要格線。唯讀 Boolean。 |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | 表示是否顯示次要格線。唯讀 Boolean。 |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | 表示指定軸上刻度標籤的位置。可讀寫 [`TickLabelPositionType`](../ticklabelpositiontype)。 |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | 表示刻度標籤的旋轉角度。可讀寫 Single。 |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | 指定在已繪製的標籤之間要跳過的刻度標籤數量。可讀寫 UInt32。 |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | 指定在繪製下一個刻度標記前要跳過的刻度標記數量。適用於類別或系列軸。可讀寫 UInt16。 |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | 取得軸的標題。唯讀 [`IChartTitle`](../icharttitle)。 |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | 指定下溢分箱的自訂值。當 IsAutomaticUnderflowBin 屬性設定為 false 且 IsUnderflowBin 屬性為 true 時套用。 |

## 方法

| Name | Description |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | 設定 IAxis.CategoryAxisType 屬性，其值會根據軸資料自動決定。 |

### 相關參考

* 介面 [IFormattedTextContainer](../iformattedtextcontainer)
* 命名空間 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->