---
title: ChartDataPoint
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een gegevenspunt van een reeks voor.
type: docs
weight: 1340
url: /nl/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint klasse

Represents series data point.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Specificeert de werkelijke hoogte van het grafiekelement. Roep eerst de methode IChart.ValidateChartLayout() aan om de werkelijke waarden te krijgen. Lezen Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Specificeert de werkelijke breedte van het grafiekelement. Roep eerst de methode IChart.ValidateChartLayout() aan om de werkelijke waarden te krijgen. Lezen Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Specificeert de werkelijke x-locatie (links) van het grafiekelement ten opzichte van de linkerbovenhoek van het diagram. Roep eerst de methode IChart.ValidateChartLayout() aan om de werkelijke waarden te krijgen. Lezen Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Specificeert de werkelijke bovenkant van het grafiekelement ten opzichte van de linkerbovenhoek van het diagram. Roep eerst de methode IChart.ValidateChartLayout() aan om de werkelijke waarden te krijgen. Lezen Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Alleen-lezen [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/chartdatapoint/cachedbubblesize) { get; } | Haalt de gecachte bubbelgrootte van een grafiekgegevenspunt op. Alleen-lezen [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/chartdatapoint/cachedvalue) { get; } | Haalt de gecachte waarde van een grafiekgegevenspunt op. Alleen-lezen [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/chartdatapoint/cachedxvalue) { get; } | Haalt de gecachte X-waarde van een grafiekgegevenspunt op. Alleen-lezen [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/chartdatapoint/cachedyvalue) { get; } | Haalt de gecachte Y-waarde van een grafiekgegevenspunt op. Alleen-lezen [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Retourneert de kleuraanwijzing van een grafiekgegevenspunt. Wordt gebruikt bij kaartgrafieken. Alleen-lezen [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Retourneert de container van gegevenspuntniveaus. Toegepast voor Treeamp- en Sunburst-reeksen. Indexering van gegevenspuntniveaus begint bij nul. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Stelt de foutbalkwaarden van de reeks voor in het geval van een aangepast waardetype. Alleen-lezen [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Specificeert de hoeveelheid waarmee het gegevenspunt van het midden van de taartdiagram moet worden verplaatst. Lezen/schrijven Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Stelt de opmaak-eigenschappen voor. Lezen/schrijven [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Specificeert dat het gegevenspunt zijn kleuren moet omkeren als de waarde negatief is. Lezen/schrijven Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Specificeert dat de bubbels een 3-D-effect hebben. Lezen/schrijven Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Label. Alleen-lezen [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Specificeert een gegevensmarkering. Alleen-lezen [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Eigenschappen van de overeenkomende legenda-item in het geval van een grafiektype uit deze lijst: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Alleen-lezen [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Stelt het gegevenspunt in als totaal. Alleen van toepassing op Waterfall-reeksen. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Retourneert de maatwaarde van een grafiekgegevenspunt. Wordt gebruikt bij Treemap- en Sunburst-grafieken. Alleen-lezen [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Waarde. Alleen-lezen [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Alleen-lezen [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Alleen-lezen [`IDoubleChartValue`](../idoublechartvalue). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Retourneert een automatische kleur van het gegevenspunt op basis van reeksenindex, gegevenspuntindex, de eigenschap ParentSeriesGroup.IsColorVaried en de grafiekstijl. Deze kleur wordt standaard gebruikt als FillType gelijk is aan NotDefined. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Verwijdert DataPoint uit de grafiekreeks. |

### Zie ook

* interface [IChartDataPoint](../ichartdatapoint)
* naamruimte [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->