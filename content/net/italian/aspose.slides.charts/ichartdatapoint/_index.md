---
title: IChartDataPoint
second_title: Riferimento API Aspose.Sildes per .NET
description: Rappresenta un punto dati della serie.
type: docs
weight: 1840
url: /it/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint interfaccia

Represents series data point.

```csharp
public interface IChartDataPoint : IActualLayout
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AsIActualLayout](../../aspose.slides.charts/ichartdatapoint/asiactuallayout) { get; } | Restituisce l'interfaccia IActualLayout. |
| [BubbleSize](../../aspose.slides.charts/ichartdatapoint/bubblesize) { get; } | Ottiene la dimensione della bolla di un punto dati del grafico. Sola lettura [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/ichartdatapoint/cachedbubblesize) { get; } | Ottiene la dimensione della bolla memorizzata di un punto dati del grafico. Sola lettura [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/ichartdatapoint/cachedvalue) { get; } | Ottiene il valore memorizzato di un punto dati del grafico. Sola lettura [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/ichartdatapoint/cachedxvalue) { get; } | Ottiene il valore X memorizzato di un punto dati del grafico. Sola lettura [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/ichartdatapoint/cachedyvalue) { get; } | Ottiene il valore Y memorizzato di un punto dati del grafico. Sola lettura [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/ichartdatapoint/colorvalue) { get; } | Ottiene il valore di colore di un punto dati del grafico. Utilizzato con grafici mappa. Sola lettura [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/ichartdatapoint/datapointlevels) { get; } | Restituisce il contenitore dei livelli del punto dati. Applicato per le serie Treeamp e Sunburst. L'indicizzazione dei livelli del punto dati è a base zero. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/ichartdatapoint/errorbarscustomvalues) { get; } | Rappresenta i valori delle barre di errore della serie nel caso di tipo di valore Personalizzato. Sola lettura [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/ichartdatapoint/explosion) { get; set; } | Specifica la quantità con cui il punto dati deve essere spostato dal centro del diagramma a torta. Lettura/Scrittura Int32. |
| [Format](../../aspose.slides.charts/ichartdatapoint/format) { get; set; } | Rappresenta le proprietà di formattazione. Lettura/Scrittura [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/ichartdatapoint/index) { get; } | Determina a quale raccolta dei figli del genitore si applica questo punto dati. Lettura UInt32. |
| [InvertIfNegative](../../aspose.slides.charts/ichartdatapoint/invertifnegative) { get; set; } | Specifica che il punto dati deve invertire i colori se il valore è negativo. Lettura/Scrittura Boolean. |
| [IsBubble3D](../../aspose.slides.charts/ichartdatapoint/isbubble3d) { get; set; } | Specifica che le bolle hanno un effetto 3-D applicato. Lettura/Scrittura Boolean. |
| [Label](../../aspose.slides.charts/ichartdatapoint/label) { get; } | Rappresenta l'etichetta del punto dati del grafico. Sola lettura [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/ichartdatapoint/marker) { get; } | Specifica un marcatore dati. Sola lettura [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartdatapoint/relatedlegendentry) { get; } | Proprietà della voce della legenda corrispondente nel caso di tipo di grafico dalla seguente lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Sola lettura [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/ichartdatapoint/setastotal) { get; set; } | Imposta il punto dati come totale. Applicato solo per il tipo di serie Waterfall. |
| [SizeValue](../../aspose.slides.charts/ichartdatapoint/sizevalue) { get; } | Ottiene il valore di dimensione di un punto dati del grafico. Utilizzato con grafici Treemap e Sunburst. Sola lettura [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/ichartdatapoint/value) { get; } | Ottiene il valore di un punto dati del grafico. Sola lettura [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/ichartdatapoint/xvalue) { get; } | Ottiene il valore x di un punto dati del grafico. Sola lettura [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/ichartdatapoint/yvalue) { get; } | Ottiene il valore y di un punto dati del grafico. Sola lettura [`IDoubleChartValue`](../idoublechartvalue). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/ichartdatapoint/getautomaticdatapointcolor)() | Restituisce un colore automatico del punto dati basato su indice della serie, indice del punto dati, proprietà ParentSeriesGroup.IsColorVaried e stile del grafico. Questo colore è usato per impostazione predefinita se FillType è uguale a NotDefined. |
| [Remove](../../aspose.slides.charts/ichartdatapoint/remove)() | Rimuove DataPoint dalla serie del grafico. |

### Vedere anche

* interfaccia [IActualLayout](../iactuallayout)
* spazio dei nomi [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->