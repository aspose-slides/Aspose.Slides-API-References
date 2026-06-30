---
title: ChartDataPoint
second_title: Aspose.Sildes dla .NET – dokumentacja API
description: Reprezentuje punkt danych serii.
type: docs
weight: 1310
url: /pl/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint klasa

Represents series data point.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Określa rzeczywistą wysokość elementu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed uzyskaniem rzeczywistych wartości. Tylko odczyt Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Określa rzeczywistą szerokość elementu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed uzyskaniem rzeczywistych wartości. Tylko odczyt Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Określa rzeczywistą pozycję x (lewa) elementu wykresu względem lewego górnego rogu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed uzyskaniem rzeczywistych wartości. Tylko odczyt Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Określa rzeczywistą górną pozycję elementu wykresu względem lewego górnego rogu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed uzyskaniem rzeczywistych wartości. Tylko odczyt Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Tylko do odczytu [`IDoubleChartValue`](../idoublechartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Zwraca wartość koloru punktu danych wykresu. Używane z wykresami mapowymi. Tylko do odczytu [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Zwraca kontener poziomów punktu danych. Stosowane dla serii Treeamp i Sunburst. Indeksowanie poziomów punktu danych zaczyna się od zera. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Reprezentuje wartości słupków błędów serii w przypadku typu wartości Custom. Tylko do odczytu [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Określa ilość, o którą punkt danych ma być przesunięty od środka wykresu kołowego. Odczyt/zapis Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Reprezentuje właściwości formatowania. Odczyt/zapis [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Określa, że punkt danych odwróci swoje kolory, jeśli wartość jest ujemna. Odczyt/zapis Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Określa, że bąbelki mają zastosowany efekt 3D. Odczyt/zapis Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Label. Tylko do odczytu [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Określa znacznik danych. Tylko do odczytu [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Właściwości odpowiadającego wpisu legendy w przypadku typu wykresu z tej listy: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Tylko do odczytu [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Ustawia punkt danych jako sumę. Stosowane wyłącznie dla typu serii Waterfall. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Zwraca wartość rozmiaru punktu danych wykresu. Używane z wykresami Treemap i Sunburst. Tylko do odczytu [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Value. Tylko do odczytu [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Tylko do odczytu [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Tylko do odczytu [`IDoubleChartValue`](../idoublechartvalue). |

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