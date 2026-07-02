---
title: ChartDataPoint
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een seriedatapunt voor.
type: docs
weight: 1330
url: /nl/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint klasse

Stelt een seriegegevenspunt voor.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Specificeert de werkelijke hoogte van het diagramonderdeel. Roep vóór het ophalen van de werkelijke waarden de methode IChart.ValidateChartLayout() aan. Lezen Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Specificeert de werkelijke breedte van het diagramonderdeel. Roep vóór het ophalen van de werkelijke waarden de methode IChart.ValidateChartLayout() aan. Lezen Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Specificeert de werkelijke x-locatie (links) van het diagramonderdeel ten opzichte van de linkerbovenhoek van het diagram. Roep vóór het ophalen van de werkelijke waarden de methode IChart.ValidateChartLayout() aan. Lezen Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Specificeert de werkelijke bovenkant van het diagramonderdeel ten opzichte van de linkerbovenhoek van het diagram. Roep vóór het ophalen van de werkelijke waarden de methode IChart.ValidateChartLayout() aan. Lezen Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Alleen-lezen [`IDoubleChartValue`](../idoublechartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Geeft de kleurwaarde van het diagramgegevenspunt terug. Wordt gebruikt met kaartdiagrammen. Alleen-lezen [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Geeft de container van gegevenspuntniveaus terug. Toegepast voor Treeamp- en Sunburst-series. De indexering van gegevenspuntniveaus begint bij nul. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Stelt de waarden van foutbalken van de serie voor in het geval van een aangepast waardetype. Alleen-lezen [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Specificeert de hoeveelheid waarmee het gegevenspunt van het midden van de taart moet worden verplaatst. Lezen/Schrijven Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Stelt de opmaak-eigenschappen voor. Lezen/Schrijven [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Specificeert dat het gegevenspunt zijn kleuren moet omkeren als de waarde negatief is. Lezen/Schrijven Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Specificeert dat de bubbels een 3-D-effect hebben. Lezen/Schrijven Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Label. Alleen-lezen [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Specificeert een gegevensmarkeringspunt. Alleen-lezen [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Eigenschappen van het overeenkomstige legende-item in het geval van een diagramtype uit deze lijst: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Alleen-lezen [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Stelt het gegevenspunt in als totaal. Alleen van toepassing op Waterfall-serietype. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Geeft de groottewaarde van het diagramgegevenspunt terug. Wordt gebruikt met treemap- en sunburst-diagrammen. Alleen-lezen [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Waarde. Alleen-lezen [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Alleen-lezen [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Alleen-lezen [`IDoubleChartValue`](../idoublechartvalue). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Geeft een automatische kleur van het gegevenspunt terug op basis van de serie-index, gegevenspunt-index, ParentSeriesGroup.IsColorVaried-eigenschap en diagramstijl. Deze kleur wordt standaard gebruikt als FillType gelijk is aan NotDefined. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Verwijdert DataPoint uit de diagramserie. |

### Zie ook

* interface [IChartDataPoint](../ichartdatapoint)
* naamruimte [Aspose.Slides.Charts](../../aspose.slides.charts)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->