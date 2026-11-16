---
title: IChartSeries
second_title: Aspose.Sildes 的 .NET API 參考文件
description: 表示圖表系列。
type: docs
weight: 1950
url: /zh-hant/aspose.slides.charts/ichartseries/
---
## IChartSeries 介面

表示圖表系列。

```csharp
public interface IChartSeries : IChartComponent
```

## 屬性

| Name | Description |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | 允許取得基礎 IChartComponent 介面。唯讀 [`IChartComponent`](../ichartcomponent)。 |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | 指定 3-D 條形圖系列的形狀。更改此屬性的值可能會自動變更系列的 Type。可讀寫 [`ChartShapeType`](../chartshapetype)。 |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | 指定在氣泡圖上如何呈現氣泡大小值。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列──屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.BubbleSizeRepresentation 可讀寫屬性以變更值。 |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | 指定氣泡圖的比例係數（可介於預設大小的 0% 到 300% 之間）。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列──屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.BubbleSizeScale 可讀寫屬性以變更值。 |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | 傳回本系列的資料點集合。唯讀 [`IChartDataPointCollection`](../ichartdatapointcollection)。 |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | 指定甜甜圈圖中孔的大小（可介於繪圖區大小的 10% 到 90% 之間）。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列──屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.DoughnutHoleSize 可讀寫屬性以變更值。唯讀 Byte。 |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | 表示方向為 X 的系列誤差棒。方向為 X 的誤差棒適用於類型為 area、bar、scatter 和 bubble 的系列。對於其他類型的圖表（包括 3D 圖表），此屬性返回 null。若使用自訂值，請使用 DataPoints 集合指定值（使用 [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) 屬性）。唯讀 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | 表示方向為 Y 的系列誤差棒。方向為 Y 的誤差棒適用於類型為 area、bar、line、scatter 和 bubble 的系列。對於其他類型的圖表（包括 3D 圖表），此屬性返回 null。若使用自訂值，請使用 DataPoints 集合指定值（使用 [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) 屬性）。唯讀 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | 開放的餅圖切片與餅圖中心的距離以餅圖直徑的百分比表示。可讀寫 Int32。 |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | 指定第一個餅圖或甜甜圈圖切片的角度（以度數表示，從上方順時針，0 到 360 度）。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列──屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.FirstSliceAngle 可讀寫屬性以變更值。唯讀 UInt16。 |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | 傳回系列的格式。唯讀 [`IFormat`](../iformat)。 |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | 傳回或設定 3D 圖表中資料系列之間的距離（以標記寬度的百分比表示）。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列──屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.GapDepth 可讀寫屬性以變更值。唯讀 Int32。 |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | 指定條形或柱狀叢集之間的間距，以條形或柱狀寬度的百分比表示。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列──屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.GapWidth 可讀寫屬性以變更值。唯讀 Int32。 |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | 決定此系列及相關系列是否具有系列線。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列──屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.HasSeriesLines 可讀寫屬性以變更值。使用 ParentSeriesGroup.SeriesLinesFormat 屬性設定系列線的格式。唯讀 Boolean。 |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | 決定折線圖或股票圖是否具有上下條。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列──屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.UpDownBars.HasUpDownBars 可讀寫屬性以變更值。使用 ParentSeriesGroup.UpDownBars 屬性設定上下條的格式。唯讀 Boolean。 |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | 指定系列的反轉實色。若要套用顏色設定，將系列格式的 FillType 設為 FillType.Solid。可讀寫 [`IColorFormat`](../../aspose.slides/icolorformat)。 |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | 指定當值為負時，條形、柱形或氣泡系列應反轉其顏色。可讀寫 Boolean。 |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | 指定系列中的每個資料標記具有不同的顏色。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列──屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.IsColorVaried 可讀寫屬性以變更值。唯讀 Boolean。 |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | 傳回系列的標籤。唯讀 [`IDataLabelCollection`](../idatalabelcollection)。 |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | 傳回系列的標記。唯讀 [`IMarker`](../imarker)。 |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | 傳回系列名稱。唯讀 [`IStringChartValue`](../istringchartvalue)。 |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | 傳回或設定系列氣泡大小的數字格式。可讀寫 String。 |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | 傳回或設定系列值的數字格式。可讀寫 String。 |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | 傳回或設定系列 X 值的數字格式。可讀寫 String。 |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | 傳回或設定系列 Y 值的數字格式。可讀寫 String。 |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | 傳回系列的順序。可讀寫 Int32。 |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | 指定 2-D 圖表中條形與柱形的重疊程度，以百分比表示（從 -100% 到 100%）。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列──屬於父系列群組中相應屬性的投影，因此此屬性為唯讀。若要變更值，請使用 ParentSeriesGroup.Overlap 可讀寫屬性。唯讀 SByte。 |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | 表示父類別標籤的版面配置。僅適用於 Treemap 圖表。 |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | 傳回父系列群組。唯讀 [`IChartSeriesGroup`](../ichartseriesgroup)。 |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | 指定如何判斷哪些資料點位於 pie-of-pie 或 bar-of-pie 圖表的第二個餅或條中。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列──屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.PieSplitBy 可讀寫屬性以變更值。唯讀 [`PieSplitType`](../piesplittype)。 |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | 為具有自訂切分的 pie-of-pie 或 bar-of-pie 圖表提供自訂切分資訊。包含應在第二個餅或條中繪製的資料點。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列──屬於相應群組屬性的投影。唯讀 [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection)。 |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | 指定用於判斷哪些資料點位於 pie-of-pie 或 bar-of-pie 圖表的第二個餅或條的值。與 PieSplitBy 屬性共同使用。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列──屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.PieSplitPosition 可讀寫屬性以變更值。唯讀 Double。 |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | 指示此系列是否繪製於第二個值軸上。可讀寫 Boolean。 |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | 表示四分位方法。僅適用於 BoxAndWhisker 圖表。 |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | 表示與此系列相關的圖例項目。唯讀 [`ILegendEntryProperties`](../ilegendentryproperties)。 |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | 指定 pie-of-pie 或 bar-of-pie 圖表中第二個餅或條的大小，以第一個餅的大小百分比表示（可介於 5% 到 200% 之間）。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列──屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.SecondPieSize 可讀寫屬性以變更值。唯讀 UInt16。 |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | 表示連接線。僅適用於 Waterfall 圖表。 |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | 表示內部點。若在 BoxAndWhisker 圖表上顯示內部點則為 true。僅適用於 BoxAndWhisker 圖表。可讀寫 Boolean。 |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | 表示平均標記。若在 BoxAndWhisker 圖表上顯示平均線則為 true。僅適用於 BoxAndWhisker 圖表。可讀寫 Boolean。 |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | 表示平均標記。若在 BoxAndWhisker 圖表上顯示平均標記則為 true。僅適用於 BoxAndWhisker 圖表。可讀寫 Boolean。 |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | 表示離群點。若在 BoxAndWhisker 圖表上顯示離群點則為 true。僅適用於 BoxAndWhisker 圖表。可讀寫 Boolean。 |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | 表示曲線平滑。若對折線圖或散佈圖啟用曲線平滑則為 true。僅適用於由線條連接的折線圖與散佈圖。可讀寫 Boolean。 |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | 系列趨勢線的集合。唯讀 [`ITrendlineCollection`](../itrendlinecollection)。 |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | 傳回此系列的類型。可讀寫 [`ChartType`](../charttype)。 |

## 方法

| 名稱 | 描述 |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | 傳回基於系列索引和圖表樣式的自動系列顏色。如果 FillType 等於 NotDefined，則預設使用此顏色。 |

### 參見

* 介面 [IChartComponent](../ichartcomponent)
* 命名空間 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 程式集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->