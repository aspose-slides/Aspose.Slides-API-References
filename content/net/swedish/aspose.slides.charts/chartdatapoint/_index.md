---
title: ChartDataPoint
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en datapunkt i en serie.
type: docs
weight: 1310
url: /sv/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint klass

Representerar en serie datapunkt.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Anger den faktiska höjden för diagrammets element. Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden. Läs Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Anger den faktiska bredden för diagrammets element. Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden. Läs Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Anger den faktiska x-platsen (vänster) för diagrammets element relativt det övre vänstra hörnet av diagrammet. Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden. Läs Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Anger den faktiska toppen för diagrammets element relativt det övre vänstra hörnet av diagrammet. Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden. Läs Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Skrivskyddad [`IDoubleChartValue`](../idoublechartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Returnerar färgvärdet för diagrammets datapunkt. Används med kartdiagram. Skrivskyddad [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Returnerar behållaren för datapunktsnivåer. Används för TreeMap- och Sunburst-serier. Indexeringen av datapunktsnivåer är nollbaserad. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Representerar seriens felstaplarvärden för anpassad värdetyp. Skrivskyddad [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Anger hur mycket datapunkten ska flyttas från mitten av cirkeldiagrammet. Läs/skriv Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Representerar formateringsegenskaperna. Läs/skriv [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Anger att datapunkten ska invertera sina färger om värdet är negativt. Läs/skriv Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Anger att bubblorna har en 3-D-effekt tillämpad. Läs/skriv Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Etikett. Skrivskyddad [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Anger en datamarkör. Skrivskyddad [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Egenskaper för motsvarande förklaringspost om diagramtypen är någon av följande: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Skrivskyddad [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Anger datapunkten som total. Används endast för Waterfall-serietyp. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Returnerar storleksvärdet för diagrammets datapunkt. Används med Treemap- och Sunburst-diagram. Skrivskyddad [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Värde. Skrivskyddad [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Skrivskyddad [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Skrivskyddad [`IDoubleChartValue`](../idoublechartvalue). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Returnerar en automatisk färg för datapunkten baserat på seriens index, datapunktsindex, egenskapen ParentSeriesGroup.IsColorVaried och diagramstilen. Denna färg används som standard om FillType är lika med NotDefined. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Tar bort DataPoint från diagramserien. |

### Se även

* gränssnitt [IChartDataPoint](../ichartdatapoint)
* namnrymd [Aspose.Slides.Charts](../../aspose.slides.charts)
* sammanställning [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->