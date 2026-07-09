---
title: ChartSeries
second_title: Aspose.Sildes for .NET API 參考
description: 表示圖表系列。
type: docs
weight: 1440
url: /zh-hant/aspose.slides.charts/chartseries/
---
## ChartSeries 類別

表示圖表系列。

```csharp
public class ChartSeries : IChartSeries
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | 指定 3-D 柱狀圖 系列的形狀。變更此屬性的值可能會自動變更系列的類型。讀/寫 [`ChartShapeType`](../chartshapetype)。 |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | 指定在氣泡圖上如何呈現氣泡大小值。此屬性不僅屬於此系列，還屬於父系列群組的所有系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.BubbleSizeRepresentation 讀/寫 屬性以變更值。 |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | 指定氣泡圖的比例因子（可在預設大小的 0% 到 300% 之間）。此屬性不僅屬於此系列，還屬於父系列群組的所有系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.BubbleSizeScale 讀/寫 屬性以變更值。 |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | 返回父圖表。唯讀 [`IChart`](../ichart)。 |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | 返回此系列的資料點集合。唯讀 [`IChartDataPointCollection`](../ichartdatapointcollection)。 |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | 指定甜甜圈圖中孔的大小（可在繪圖區大小的 10% 到 90% 之間）。此屬性不僅屬於此系列，還屬於父系列群組的所有系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.DoughnutHoleSize 讀/寫 屬性以變更值。唯讀 Byte。 |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | 表示方向為 X 的系列誤差棒。X 方向的誤差棒適用於 area、bar、scatter 和 bubble 類型的系列。對於其他圖表類型，此屬性返回 null（包括 3D 圖表）。若使用自訂值，請利用 DataPoints 集合搭配 [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) 屬性指定值。唯讀 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | 表示方向為 Y 的系列誤差棒。Y 方向的誤差棒適用於 area、bar、line、scatter 和 bubble 類型的系列。對於其他圖表類型，此屬性返回 null（包括 3D 圖表）。若使用自訂值，請利用 DataPoints 集合搭配 [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) 屬性指定值。唯讀 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | 開啟的餅圖切片與餅圖中心的距離以餅圖直徑的百分比表示。讀/寫 Int32。 |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | 指定第一個餅圖或甜甜圈圖切片的角度（以度為單位，從上方順時針，範圍 0 到 360 度）。此屬性不僅屬於此系列，還屬於父系列群組的所有系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup.FirstSliceAngle 讀/寫 屬性以變更值。唯讀 UInt16。 |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | 返回系列的格式。唯讀 [`IFormat`](../iformat)。 |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | 返回或設定 3D 圖表中資料系列之間的距離（以標記寬度的百分比表示）。此屬性不僅屬於此系列，還屬於父系列群組的所有系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup.GapDepth 讀/寫 屬性以變更值。唯讀 Int32。 |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | 指定條形或柱形叢集之間的間距（以條形或柱形寬度的百分比表示）。此屬性不僅屬於此系列，還屬於父系列群組的所有系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup.GapWidth 讀/寫 屬性以變更值。唯讀 Int32。 |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | 決定此系列及相關系列是否具有系列線。此屬性不僅屬於此系列，還屬於父系列群組的所有系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup.HasSeriesLines 讀/寫 屬性以變更值。使用 ParentSeriesGroup.SeriesLinesFormat 屬性設定系列線格式。唯讀 Boolean。 |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | 決定折線圖或股票圖是否具有上下條。此屬性不僅屬於此系列，還屬於父系列群組的所有系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup.UpDownBars.HasUpDownBars 讀/寫 屬性以變更值。使用 ParentSeriesGroup.UpDownBars 屬性設定上下條的格式。唯讀 Boolean。 |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | 指定系列的反轉實心顏色。若要套用顏色設定，請將系列格式的 FillType 設為 FillType.Solid。讀/寫 [`ColorFormat`](../../aspose.slides/colorformat)。 |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | 指定當值為負時，條形、柱形或氣泡系列應反轉其顏色。讀/寫 Boolean。 |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | 指定系列中的每個資料標記使用不同的顏色。此屬性不僅屬於此系列，還屬於父系列群組的所有系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup.IsColorVaried 讀/寫 屬性以變更值。唯讀 Boolean。 |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | 返回系列的標籤。唯讀 [`IDataLabelCollection`](../idatalabelcollection)。 |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | 標記。唯讀 [`IMarker`](../imarker)。 |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | 返回系列名稱。唯讀 [`IStringChartValue`](../istringchartvalue)。 |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | BubbleSizes 的數字格式。讀/寫 String。 |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | Values 的數字格式。讀/寫 String。 |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | XValues 的數字格式。讀/寫 String。 |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | YValues 的數字格式。讀/寫 String。 |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | 返回系列的順序。讀/寫 Int32。 |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | 指定 2D 圖表中條形與柱形的重疊程度（以百分比表示，範圍 -100% 到 100%）。此屬性不僅屬於此系列，還屬於父系列群組的所有系列——此為相應群組屬性的投影。因此此屬性為唯讀。要變更值，請使用 ParentSeriesGroup.Overlap 讀/寫 屬性。唯讀 SByte。 |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | 表示父類別標籤的版面配置。僅適用於 Treemap 圖表。 |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup。唯讀 [`IChartSeriesGroup`](../ichartseriesgroup)。 |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | 指定如何決定在 pie-of-pie 或 bar-of-pie 圖表中哪些資料點位於第二個餅或條上。此屬性不僅屬於此系列，還屬於父系列群組的所有系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup.PieSplitBy 讀/寫 屬性以變更值。唯讀 [`PieSplitType`](../piesplittype)。 |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | 具有自訂分割的 pie-of-pie 或 bar-of-pie 圖表的自訂分割資訊。包含應在第二個餅或條中繪製的資料點。此屬性不僅屬於此系列，還屬於父系列群組的所有系列——此為相應群組屬性。唯讀 [`PieSplitCustomPointCollection`](../piesplitcustompointcollection)。 |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | 指定用於決定在 pie-of-pie 或 bar-of-pie 圖表中哪些資料點位於第二個餅或條的值。與 PieSplitBy 屬性一起使用。此屬性不僅屬於此系列，還屬於父系列群組的所有系列——此為相應群組屬性。因此此屬性為唯讀。使用 ParentSeriesGroup.PieSplitPosition 讀/寫 屬性以變更值。唯讀 Double。 |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | 指示此系列是否繪製於次要坐標軸上。讀/寫 Boolean。 |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | 表示四分位數方法。僅適用於 BoxAndWhisker 圖表。 |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | 表示與此系列相關的圖例項目。唯讀 [`ILegendEntryProperties`](../ilegendentryproperties)。 |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | 指定 pie-of-pie 或 bar-of-pie 圖表中第二個餅或條的大小（以第一個餅的大小百分比表示，可在 5% 到 200% 之間）。此屬性不僅屬於此系列，還屬於父系列群組的所有系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup.SecondPieSize 讀/寫 屬性以變更值。唯讀 UInt16。 |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | 表示連接線。僅適用於 Waterfall 圖表。 |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | 表示內部點。若在 BoxAndWhisker 圖表上顯示內部點則為 true。僅適用於 BoxAndWhisker 圖表。讀/寫 Boolean。 |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | 表示平均線。若在 BoxAndWhisker 圖表上顯示平均線則為 true。僅適用於 BoxAndWhisker 圖表。讀/寫 Boolean。 |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | 表示平均標記。若在 BoxAndWhisker 圖表上顯示平均標記則為 true。僅適用於 BoxAndWhisker 圖表。讀/寫 Boolean。 |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | 表示異常值點。若在 BoxAndWhisker 圖表上顯示異常值點則為 true。僅適用於 BoxAndWhisker 圖表。讀/寫 Boolean。 |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | 表示曲線平滑。若對折線圖或散點圖啟用曲線平滑則為 true。僅適用於折線圖與以線連接的散點圖。讀/寫 Boolean。 |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | 系列趨勢線的集合。唯讀 [`ITrendlineCollection`](../itrendlinecollection)。 |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | 返回此系列的類型。讀/寫 [`ChartType`](../charttype)。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | 根據系列索引和圖表樣式返回系列的自動顏色。如果 FillType 等於 NotDefined，則預設使用此顏色。 |

### 另見

* 介面 [IChartSeries](../ichartseries)
* 命名空間 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 程式集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->