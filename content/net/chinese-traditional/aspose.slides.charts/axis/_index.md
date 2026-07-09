---
title: Axis
second_title: Aspose.Sildes for .NET API 參考文件
description: 封裝代表圖表軸的物件。
type: docs
weight: 1180
url: /zh-hant/aspose.slides.charts/axis/
---
## Axis 類別

封裝代表圖表軸的物件。

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | 指定軸的實際主要單位。先前呼叫 IChart.ValidateChartLayout() 方法以取得實際值。 |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | 指定軸的實際主要單位比例。先前呼叫 IChart.ValidateChartLayout() 方法以取得實際值。 |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | 指定軸上的實際最大值。先前呼叫 IChart.ValidateChartLayout() 方法以取得實際值。 |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | 指定軸的實際次要單位。先前呼叫 IChart.ValidateChartLayout() 方法以取得實際值。 |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | 指定軸的實際次要單位比例。先前呼叫 IChart.ValidateChartLayout() 方法以取得實際值。 |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | 指定軸上的實際最小值。先前呼叫 IChart.ValidateChartLayout() 方法以取得實際值。 |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | 代表類別軸的彙總類型（分箱）。套用於類別。僅用於 Histogram 或 HistogramPareto 系列。 |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | 代表數值軸是否在類別之間穿過類別軸。此屬性僅適用於類別軸，且不適用於 3D 圖表。可讀寫 Boolean。 |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | 指定日期軸上所表示的最小時間單位。可讀寫 [`TimeUnitType`](../timeunittype)。 |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | 在 AggregationType 屬性值設定為 AxisAggregationType.ByBinWidth 時指定分箱寬度。套用於類別軸。僅用於 Histogram 或 HistogramPareto 系列。 |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | 指定類別軸的類型。可讀寫 [`CategoryAxisType`](../categoryaxistype)。 |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | 傳回父圖表。唯讀 [`IChart`](../ichart)。 |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | 代表垂直軸與該軸交叉的點。可讀寫 Single。 |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | 代表在指定軸上另一軸交叉時的 CrossType。可讀寫 [`CrossesType`](../crossestype)。 |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | 指定數值軸顯示單位的縮放值。可讀寫 [`DisplayUnitType`](../displayunittype)。 |
| [Format](../../aspose.slides.charts/axis/format) { get; } | 代表軸的格式。唯讀 [`IAxisFormat`](../iaxisformat)。 |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | 決定軸是否具有可見標題。可讀寫 Boolean。 |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | 指示軸的主要單位是否自動指派。可讀寫 Boolean。 |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | 指示最大值是否自動指派。可讀寫 Boolean。 |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | 指示軸的次要單位是否自動指派。可讀寫 Boolean。 |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | 指示最小值是否自動指派。可讀寫 Boolean。 |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | 指定自動溢位分箱值。若為 false：使用 OverflowBin 屬性。 |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | 指定自動刻度標籤間距值。若為 false：使用 TickLabelSpacing 屬性。可讀寫 Boolean。 |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | 指定自動刻度線間距值。若為 false：使用 TickMarksSpacing 屬性。可讀寫 Boolean。 |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | 指定自動下溢分箱值。若為 false：使用 UnderflowBin 屬性。 |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | 代表數值軸的比例類型是否為對數。可讀寫 Boolean。 |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | 指示格式是否連結至來源資料。可讀寫 Boolean。 |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | 指定是否套用溢位分箱。使用 IsAutomaticOverflowBin 與 OverflowBin 來調整溢位分箱值。 |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | 代表 MS PowerPoint 是否從最後到最前繪製資料點。可讀寫 Boolean。 |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | 指定是否套用下溢分箱。使用 IsAutomaticUnderflowBin 與 UnderflowBin 來調整下溢分箱值。 |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | 代表軸是否可見。可讀寫 Boolean。 |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | 指定標籤距離軸的距離。套用於類別或日期軸。值必須介於 0% 與 1000% 之間。可讀寫 UInt16。 |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | 代表對數底。預設值為 10。可讀寫 Double。 |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | 代表圖表軸上主要格線的格式。唯讀 [`IChartLinesFormat`](../ichartlinesformat)。 |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | 代表指定軸上主要刻度標記的類型。可讀寫 [`TickMarkType`](../tickmarktype)。 |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | 代表日期或數值軸的主要單位。可讀寫 Double。 |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | 代表日期軸的主要單位比例。可讀寫 [`TimeUnitType`](../timeunittype)。 |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | 代表數值軸的最大值。可讀寫 Double。 |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | 代表圖表軸上次要格線的格式。唯讀 [`IChartLinesFormat`](../ichartlinesformat)。 |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | 代表指定軸上次要刻度標記的類型。可讀寫 [`TickMarkType`](../tickmarktype)。 |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | 代表日期或數值軸的次要單位。可讀寫 Double。 |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | 代表日期軸的主要單位比例。可讀寫 [`TimeUnitType`](../timeunittype)。 |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | 代表數值軸的最小值。可讀寫 Double。 |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | 代表軸標籤的格式字串。可讀寫 String。 |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | 在 AggregationType 屬性值設定為 AxisAggregationType.ByNumberOfBins 時指定分箱數量。套用於類別軸。僅用於 Histogram 或 HistogramPareto 系列。 |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | 指定溢位分箱的自訂值。當 IsAutomaticOverflowBin 屬性設定為 false 且 IsOverflowBin 屬性為 true 時套用。 |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | 代表軸的位置。可讀寫 [`AxisPositionType`](../axispositiontype)。 |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | 若要隱藏主要格線，將 MajorGridLinesFormat.Line.FillFormat.FillType 設為 FillType.NoFill。唯讀 Boolean。 |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | 若要隱藏次要格線，將 MinorGridLinesFormat.Line.FillFormat.FillType 設為 FillType.NoFill。唯讀 Boolean。 |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | 代表文字的格式。唯讀 [`IChartTextFormat`](../icharttextformat)。 |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | 代表指定軸上刻度標籤的位置。可讀寫 [`TickLabelPositionType`](../ticklabelpositiontype)。 |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | 代表刻度標籤的旋轉角度。可讀寫 Single。 |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | 指定在已繪製的標籤之間要跳過的刻度標籤數量。套用於類別或系列軸。可讀寫 UInt32。 |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | 指定在繪製下一個刻度線前要跳過的刻度線數量。套用於類別或系列軸。可讀寫 UInt16。 |
| [Title](../../aspose.slides.charts/axis/title) { get; } | 取得軸的標題。唯讀 [`IChartTitle`](../icharttitle)。 |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | 指定下溢分箱的自訂值。當 IsAutomaticUnderflowBin 屬性設定為 false 且 IsUnderflowBin 屬性為 true 時套用。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | 設定 IAxis.CategoryAxisType 屬性，使用根據軸資料自動決定的值。 |

### 相關參考

* 類別 [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* 類別 [AxesManager](../axesmanager)
* 介面 [IAxis](../iaxis)
* 命名空間 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->