---
title: ChartDataPoint
second_title: Aspose.Sildes dla .NET API Reference
description: Reprezentuje punkt danych serii.
type: docs
weight: 1340
url: /pl/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint klasa

Reprezentuje punkt danych serii.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Określa rzeczywistą wysokość elementu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed, aby uzyskać rzeczywiste wartości. Odczyt Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Określa rzeczywistą szerokość elementu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed, aby uzyskać rzeczywiste wartości. Odczyt Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Określa rzeczywistą pozycję x (lewy) elementu wykresu względem lewego górnego rogu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed, aby uzyskać rzeczywiste wartości. Odczyt Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Określa rzeczywistą pozycję górną elementu wykresu względem lewego górnego rogu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed, aby uzyskać rzeczywiste wartości. Odczyt Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Tylko odczyt [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/chartdatapoint/cachedbubblesize) { get; } | Pobiera buforowany rozmiar bąbla punktu danych wykresu. Tylko odczyt [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/chartdatapoint/cachedvalue) { get; } | Pobiera buforowaną wartość punktu danych wykresu. Tylko odczyt [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/chartdatapoint/cachedxvalue) { get; } | Pobiera buforowaną wartość X punktu danych wykresu. Tylko odczyt [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/chartdatapoint/cachedyvalue) { get; } | Pobiera buforowaną wartość Y punktu danych wykresu. Tylko odczyt [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Zwraca wartość koloru punktu danych wykresu. Używane w wykresach map. Tylko odczyt [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Zwraca kontener poziomów punktu danych. Stosowane dla serii Treeamp i Sunburst. Indeksowanie poziomów punktu danych zaczyna się od zera. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Reprezentuje wartości słupków błędów serii w przypadku typu wartości Custom. Tylko odczyt [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Określa odległość, o jaką punkt danych ma zostać przesunięty od środka koła. Odczyt/zapis Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Reprezentuje właściwości formatowania. Odczyt/zapis [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Określa, że punkt danych odwróci swoje kolory, jeśli wartość jest ujemna. Odczyt/zapis Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Określa, że bąble mają zastosowany efekt 3-D. Odczyt/zapis Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Etykieta. Tylko odczyt [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Określa znacznik danych. Tylko odczyt [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Właściwości odpowiadającego wpisu legendy w przypadku typu wykresu z tej listy: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Tylko odczyt [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Ustawia punkt danych jako sumę. Stosowane wyłącznie dla serii Waterfall. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Zwraca wartość rozmiaru punktu danych wykresu. Używane w wykresach Treemap i Sunburst. Tylko odczyt [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Value. Tylko odczyt [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Tylko odczyt [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Tylko odczyt [`IDoubleChartValue`](../idoublechartvalue). |

## Metody

| Nazwa | Opis |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Zwraca automatyczny kolor punktu danych na podstawie indeksu serii, indeksu punktu danych, właściwości ParentSeriesGroup.IsColorVaried oraz stylu wykresu. Ten kolor jest używany domyślnie, jeśli FillType równa się NotDefined. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Usuwa DataPoint z serii wykresu. |

### Zobacz także

* interfejs [IChartDataPoint](../ichartdatapoint)
* przestrzeń nazw [Aspose.Slides.Charts](../../aspose.slides.charts)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->