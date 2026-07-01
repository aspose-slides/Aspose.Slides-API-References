---
title: ChartDataPoint
second_title: Aspose.Sildes per .NET Riferimento API
description: Rappresenta il punto dati della serie.
type: docs
weight: 1310
url: /it/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint classe

Rappresenta il punto dati della serie.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Proprietà

| Name | Description |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Specifica l'altezza effettiva dell'elemento del grafico. Chiamare il metodo IChart.ValidateChartLayout() prima per ottenere i valori effettivi. Sola lettura Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Specifica la larghezza effettiva dell'elemento del grafico. Chiamare il metodo IChart.ValidateChartLayout() prima per ottenere i valori effettivi. Sola lettura Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Specifica la posizione x effettiva (sinistra) dell'elemento del grafico rispetto all'angolo superiore sinistro del grafico. Chiamare il metodo IChart.ValidateChartLayout() prima per ottenere i valori effettivi. Sola lettura Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Specifica la parte superiore effettiva dell'elemento del grafico rispetto all'angolo superiore sinistro del grafico. Chiamare il metodo IChart.ValidateChartLayout() prima per ottenere i valori effettivi. Sola lettura Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Sola lettura [`IDoubleChartValue`](../idoublechartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Restituisce il valore di colore del punto dati del grafico. Usato con grafici Map. Sola lettura [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Restituisce il contenitore dei livelli del punto dati. Applicato per le serie Treeamp e Sunburst. L'indicizzazione dei livelli è a base zero. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Rappresenta i valori delle barre di errore della serie nel caso di tipo di valore Custom. Sola lettura [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Specifica la quantità con cui il punto dati deve essere spostato dal centro della torta. Lettura/scrittura Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Rappresenta le proprietà di formattazione. Lettura/scrittura [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Specifica che il punto dati deve invertire i colori se il valore è negativo. Lettura/scrittura Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Specifica che le bolle hanno un effetto 3-D applicato. Lettura/scrittura Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Etichetta. Sola lettura [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Specifica un marcatore dati. Sola lettura [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Proprietà della voce della legenda corrispondente nei casi di tipo di grafico dalla seguente lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Sola lettura [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Imposta il punto dati come totale. Applicato solo per il tipo di serie Waterfall. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Restituisce il valore di dimensione del punto dati del grafico. Usato con grafici Treemap e Sunburst. Sola lettura [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Valore. Sola lettura [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Sola lettura [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Sola lettura [`IDoubleChartValue`](../idoublechartvalue). |

## Metodi

| Name | Description |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Restituisce un colore automatico del punto dati basato sull'indice della serie, sull'indice del punto dati, sulla proprietà ParentSeriesGroup.IsColorVaried e sullo stile del grafico. Questo colore è utilizzato per impostazione predefinita se FillType è uguale a NotDefined. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Rimuove il DataPoint dalla serie del grafico. |

### Vedi anche

* interfaccia [IChartDataPoint](../ichartdatapoint)
* spazio dei nomi [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->