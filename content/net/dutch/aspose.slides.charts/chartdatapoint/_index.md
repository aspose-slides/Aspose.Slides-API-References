---
title: ChartDataPoint
second_title: Aspose.Sildes voor .NET API-referentie
description: Vertegenwoordigt een serie-datumpunt.
type: docs
weight: 1330
url: /nl/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint klasse

Represents series data point.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Eigenschappen

| Name | Description |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Specificeert de werkelijke hoogte van het grafiekelement. Roep methode IChart.ValidateChartLayout() aan vóór om de werkelijke waarden te verkrijgen. Lezen Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Specificeert de werkelijke breedte van het grafiekelement. Roep methode IChart.ValidateChartLayout() aan vóór om de werkelijke waarden te verkrijgen. Lezen Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Specificeert de werkelijke x-locatie (links) van het grafiekelement ten opzichte van de linkerbovenhoek van de grafiek. Roep methode IChart.ValidateChartLayout() aan vóór om de werkelijke waarden te verkrijgen. Lezen Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Specificeert de werkelijke bovenkant van het grafiekelement ten opzichte van de linkerbovenhoek van de grafiek. Roep methode IChart.ValidateChartLayout() aan vóór om de werkelijke waarden te verkrijgen. Lezen Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Alleen-lezen [`IDoubleChartValue`](../idoublechartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Retourneert de kleurwaarde van het grafiekdatumpunt. Gebruikt met Kaart-grafieken. Alleen-lezen [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Retourneert de container van datumpunt-niveaus. Toegepast voor Treeamp- en Sunburst-reeksen. Indexering van datumpunt-niveaus is nul-gebaseerd. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Stelt waarden voor foutbalken van de reeks voor in het geval van Custom-waarde type. Alleen-lezen [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Specificeert de hoeveelheid waarmee het datumpunt moet worden verschoven vanaf het midden van de taart. Lezen/schrijven Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Stelt de opmaak-eigenschappen voor. Lezen/schrijven [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Specificeert dat het datumpunt zijn kleuren moet inverteren als de waarde negatief is. Lezen/schrijven Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Specificeert dat de bubbels een 3-D-effect hebben toegepast. Lezen/schrijven Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Label. Alleen-lezen [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Specificeert een datummarker. Alleen-lezen [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Eigenschappen van het overeenkomstige legenda-item in het geval van een grafiektype uit deze lijst: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Alleen-lezen [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Stelt het datumpunt in als totaal. Alleen toegepast voor Waterfall-reeks type. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Retourneert de grootte-waarde van het grafiekdatumpunt. Gebruikt met Treemap- en Sunburst-grafieken. Alleen-lezen [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Waarde. Alleen-lezen [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Alleen-lezen [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Alleen-lezen [`IDoubleChartValue`](../idoublechartvalue). |

## Methoden

| Name | Description |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Retourneert een automatische kleur van het datumpunt op basis van reeksen-index, datumpunt-index, ParentSeriesGroup.IsColorVaried-eigenschap en grafiekstijl. Deze kleur wordt standaard gebruikt als FillType gelijk is aan NotDefined. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Verwijdert DataPoint uit de grafiekreeks. |

### Zie ook

* interface [IChartDataPoint](../ichartdatapoint)
* naamruimte [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->