---
title: IChartSeries
second_title: Aspose.Sildes for .NET API 參考
description: 表示圖表系列。
type: docs
weight: 1930
url: /zh-hant/aspose.slides.charts/ichartseries/
---
## IChartSeries 介面

Represents a chart series.

```csharp
public interface IChartSeries : IChartComponent
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | 允許取得基礎 IChartComponent 介面。唯讀 [`IChartComponent`](../ichartcomponent)。 |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | 指定 3-D 條形圖 系列的形狀。變更此屬性的值可能會自動變更系列的類型。讀寫 [`ChartShapeType`](../chartshapetype)。 |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | 指定氣泡圖中氣泡大小值的表示方式。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.BubbleSizeRepresentation 讀寫屬性變更值。 |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | 指定氣泡圖的比例因子（可為預設大小的 0% 到 300% 之間）。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.BubbleSizeScale 讀寫屬性變更值。 |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | 傳回此系列的資料點集合。唯讀 [`IChartDataPointCollection`](../ichartdatapointcollection)。 |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | 指定環形圖中孔洞的大小（可為繪圖區域大小的 10% 到 90% 之間）。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.DoughnutHoleSize 讀寫屬性變更值。唯讀 Byte。 |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | 表示 X 方向的系列誤差線。X 方向的誤差線適用於 area、bar、scatter 和 bubble 類型的系列。對於其他圖表類型，此屬性傳回 null（包括 3D 圖表）。若為自訂值，請使用 DataPoints 集合並搭配 [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) 屬性指定值。唯讀 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | 表示 Y 方向的系列誤差線。Y 方向的誤差線適用於 area、bar、line、scatter 和 bubble 類型的系列。對於其他圖表類型，此屬性傳回 null（包括 3D 圖表）。若為自訂值，請使用 DataPoints 集合並搭配 [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) 屬性指定值。唯讀 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | 開啟的餅圖切片與餅圖中心的距離以餅圖直徑的百分比表示。讀寫 Int32。 |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | 指定第一個餅圖或環形圖切片的角度（以度為單位，順時針方向，從上方向 0 度到 360 度）。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.FirstSliceAngle 讀寫屬性變更值。唯讀 UInt16。 |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | 傳回系列的格式。唯讀 [`IFormat`](../iformat)。 |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | 傳回或設定 3D 圖表中資料系列之間的距離，以標記寬度的百分比表示。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.GapDepth 讀寫屬性變更值。唯讀 Int32。 |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | 指定條形或柱形族群之間的間距，以條形或柱形寬度的百分比表示。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.GapWidth 讀寫屬性變更值。唯讀 Int32。 |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | 判斷此系列及相關系列是否有系列線。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.HasSeriesLines 讀寫屬性變更值。使用 ParentSeriesGroup.SeriesLinesFormat 屬性設定系列線的格式。唯讀 Boolean。 |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | 判斷折線圖或股票圖是否具有上下柱。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.UpDownBars.HasUpDownBars 讀寫屬性變更值。使用 ParentSeriesGroup.UpDownBars 屬性設定上下柱的格式。唯讀 Boolean。 |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | 指定系列的反轉實色。若要套用顏色設定，請將系列格式的 FillType 設為 FillType.Solid。讀寫 [`IColorFormat`](../../aspose.slides/icolorformat)。 |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | 指定若值為負數，條形、柱形或氣泡系列應反轉其顏色。讀寫 Boolean。 |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | 指定系列中的每個資料標記具有不同的顏色。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.IsColorVaried 讀寫屬性變更值。唯讀 Boolean。 |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | 傳回系列的標籤。唯讀 [`IDataLabelCollection`](../idatalabelcollection)。 |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | 傳回系列標記。唯讀 [`IMarker`](../imarker)。 |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | 傳回系列名稱。唯讀 [`IStringChartValue`](../istringchartvalue)。 |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | 傳回或設定系列氣泡大小的數字格式。讀寫 String。 |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | 傳回或設定系列值的數字格式。讀寫 String。 |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | 傳回或設定系列 X 值的數字格式。讀寫 String。 |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | 傳回或設定系列 Y 值的數字格式。讀寫 String。 |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | 傳回系列的順序。讀寫 Int32。 |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | 指定 2D 圖表中條形和柱形的重疊程度，以百分比表示（從 -100% 到 100%）。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列。它是父系列群組中相應屬性的投影，因此此屬性為唯讀。若要變更值，請使用 ParentSeriesGroup.Overlap 讀寫屬性。唯讀 SByte。 |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | 表示父類別標籤的版面配置。僅適用於 Treemap 圖表。 |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | 傳回父系列群組。唯讀 [`IChartSeriesGroup`](../ichartseriesgroup)。 |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | 指定如何決定在 pie-of-pie 或 bar-of-pie 圖表中哪些資料點位於第二個餅圖或條形。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.PieSplitBy 讀寫屬性變更值。唯讀 [`PieSplitType`](../piesplittype)。 |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | 自訂分割資訊，適用於具有自訂分割的 pie-of-pie 或 bar-of-pie 圖表。包含應繪製在第二個餅圖或條形中的資料點。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列——此為相應群組屬性的投影。唯讀 [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection)。 |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | 指定一個值，用於決定在 pie-of-pie 或 bar-of-pie 圖表中哪些資料點位於第二個餅圖或條形。與 PieSplitBy 屬性一起使用。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.PieSplitPosition 讀寫屬性變更值。唯讀 Double。 |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | 指示此系列是否繪製在第二個值軸上。讀寫 Boolean。 |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | 表示四分位數方法。僅適用於 BoxAndWhisker 圖表。 |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | 表示與此系列相關的圖例項目。唯讀 [`ILegendEntryProperties`](../ilegendentryproperties)。 |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | 指定 pie-of-pie 或 bar-of-pie 圖表中第二個餅圖或條形的大小，以第一個餅圖大小的百分比表示（可為 5% 到 200% 之間）。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.SecondPieSize 讀寫屬性變更值。唯讀 UInt16。 |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | 表示連接線。僅適用於 Waterfall 圖表。 |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | 表示內部點。若在 BoxAndWhisker 圖表上顯示內部點則為 true。僅適用於 BoxAndWhisker 圖表。讀寫 Boolean。 |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | 表示平均標記。若在 BoxAndWhisker 圖表上顯示平均線則為 true。僅適用於 BoxAndWhisker 圖表。讀寫 Boolean。 |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | 表示平均標記。若在 BoxAndWhisker 圖表上顯示平均標記則為 true。僅適用於 BoxAndWhisker 圖表。讀寫 Boolean。 |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | 表示離群點。若在 BoxAndWhisker 圖表上顯示離群點則為 true。僅適用於 BoxAndWhisker 圖表。讀寫 Boolean。 |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | 表示曲線平滑。若在折線圖或散佈圖上啟用曲線平滑則為 true。僅適用於折線圖和以線連接的散佈圖。讀寫 Boolean。 |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | 系列趨勢線的集合。唯讀 [`ITrendlineCollection`](../itrendlinecollection)。 |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | 傳回此系列的類型。讀寫 [`ChartType`](../charttype)。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | 根據系列索引和圖表樣式傳回系列的自動顏色。如果 FillType 等於 NotDefined，則預設使用此顏色。 |

### 另請參閱

* 介面 [IChartComponent](../ichartcomponent)
* 命名空間 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->