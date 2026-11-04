---
title: IChartDataPoint
second_title: Aspose.Sildes dla .NET – dokumentacja API
description: Reprezentuje punkt danych serii.
type: docs
weight: 1840
url: /pl/aspose.slides.charts/ichartdatapoint/
---
## Interfejs IChartDataPoint

Reprezentuje punkt danych serii.

```csharp
public interface IChartDataPoint : IActualLayout
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [AsIActualLayout](../../aspose.slides.charts/ichartdatapoint/asiactuallayout) { get; } | Zwraca interfejs IActualLayout. |
| [BubbleSize](../../aspose.slides.charts/ichartdatapoint/bubblesize) { get; } | Pobiera rozmiar bąbelka punktu danych wykresu. Tylko do odczytu [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/ichartdatapoint/cachedbubblesize) { get; } | Pobiera buforowany rozmiar bąbelka punktu danych wykresu. Tylko do odczytu [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/ichartdatapoint/cachedvalue) { get; } | Pobiera buforowaną wartość punktu danych wykresu. Tylko do odczytu [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/ichartdatapoint/cachedxvalue) { get; } | Pobiera buforowaną wartość X punktu danych wykresu. Tylko do odczytu [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/ichartdatapoint/cachedyvalue) { get; } | Pobiera buforowaną wartość Y punktu danych wykresu. Tylko do odczytu [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/ichartdatapoint/colorvalue) { get; } | Pobiera wartość koloru punktu danych wykresu. Używane w wykresach mapowych. Tylko do odczytu [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/ichartdatapoint/datapointlevels) { get; } | Zwraca kontener poziomów punktów danych. Stosowane dla serii Treeamp i Sunburst. Indeksowanie poziomów punktów danych zaczyna się od zera. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/ichartdatapoint/errorbarscustomvalues) { get; } | Reprezentuje wartości słupków błędów serii w przypadku typu wartości Custom. Tylko do odczytu [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/ichartdatapoint/explosion) { get; set; } | Określa odległość, o jaką punkt danych ma być przesunięty od środka wykresu kołowego. Odczyt/zapis Int32. |
| [Format](../../aspose.slides.charts/ichartdatapoint/format) { get; set; } | Reprezentuje właściwości formatowania. Odczyt/zapis [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/ichartdatapoint/index) { get; } | Określa, do której kolekcji dzieci rodzica ten punkt danych ma zastosowanie. Odczyt UInt32. |
| [InvertIfNegative](../../aspose.slides.charts/ichartdatapoint/invertifnegative) { get; set; } | Określa, że punkt danych powinien odwrócić swoje kolory, jeśli wartość jest ujemna. Odczyt/zapis Boolean. |
| [IsBubble3D](../../aspose.slides.charts/ichartdatapoint/isbubble3d) { get; set; } | Określa, że bąbelki mają zastosowany efekt 3D. Odczyt/zapis Boolean. |
| [Label](../../aspose.slides.charts/ichartdatapoint/label) { get; } | Reprezentuje etykietę punktu danych wykresu. Tylko do odczytu [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/ichartdatapoint/marker) { get; } | Określa znacznik danych. Tylko do odczytu [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartdatapoint/relatedlegendentry) { get; } | Właściwości odpowiadającego wpisu legendy w przypadku typu wykresu z tej listy: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Tylko do odczytu [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/ichartdatapoint/setastotal) { get; set; } | Ustawia punkt danych jako sumę. Stosowane wyłącznie dla typu serii Waterfall. |
| [SizeValue](../../aspose.slides.charts/ichartdatapoint/sizevalue) { get; } | Pobiera wartość rozmiaru punktu danych wykresu. Używane w wykresach Treemap i Sunburst. Tylko do odczytu [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/ichartdatapoint/value) { get; } | Pobiera wartość punktu danych wykresu. Tylko do odczytu [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/ichartdatapoint/xvalue) { get; } | Pobiera wartość x punktu danych wykresu. Tylko do odczytu [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/ichartdatapoint/yvalue) { get; } | Pobiera wartość y punktu danych wykresu. Tylko do odczytu [`IDoubleChartValue`](../idoublechartvalue). |

## Metody

| Nazwa | Opis |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/ichartdatapoint/getautomaticdatapointcolor)() | Zwraca automatyczny kolor punktu danych w oparciu o indeks serii, indeks punktu danych, właściwość ParentSeriesGroup.IsColorVaried oraz styl wykresu. Ten kolor jest używany domyślnie, jeśli FillType równa się NotDefined. |
| [Remove](../../aspose.slides.charts/ichartdatapoint/remove)() | Usuwa DataPoint z serii wykresu. |

### Zobacz także

* interfejs [IActualLayout](../iactuallayout)
* przestrzeń nazw [Aspose.Slides.Charts](../../aspose.slides.charts)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->