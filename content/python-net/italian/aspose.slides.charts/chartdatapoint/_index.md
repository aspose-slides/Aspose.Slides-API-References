---
title: ChartDataPoint class
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint classe

Rappresenta il punto dati della serie.

Il tipo ChartDataPoint espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`x_value`](/slides/python-net/it/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            Sola lettura [`IStringOrDoubleChartValue`](/slides/python-net/it/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/it/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            Sola lettura [`IDoubleChartValue`](/slides/python-net/it/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/it/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            Sola lettura [`IDoubleChartValue`](/slides/python-net/it/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/it/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            Sola lettura [`IDoubleChartValue`](/slides/python-net/it/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/it/aspose.slides.charts/chartdatapoint/size_value/) | Restituisce il valore di dimensione del punto dati del grafico.<br/>            Usato con i grafici Treemap e Sunburst. <br/>            Sola lettura [`IDoubleChartValue`](/slides/python-net/it/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/it/aspose.slides.charts/chartdatapoint/color_value/) | Restituisce il valore di colore del punto dati del grafico.<br/>            Usato con i grafici Map. <br/>            Sola lettura [`IDoubleChartValue`](/slides/python-net/it/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/it/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | Rappresenta i valori delle barre di errore della serie nel caso di tipo di valore Custom.<br/>            Sola lettura [`IErrorBarsCustomValues`](/slides/python-net/it/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/it/aspose.slides.charts/chartdatapoint/label/) | Label.<br/>            Sola lettura [`IDataLabel`](/slides/python-net/it/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/it/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | Specifica che le bolle hanno un effetto 3-D applicato.<br/>            Lettura/scrittura **bool**. |
| [`explosion`](/slides/python-net/it/aspose.slides.charts/chartdatapoint/explosion/) | Specifica la quantità di cui il punto dati deve essere spostato dal centro della torta.<br/>            Lettura/scrittura **int**. |
| [`format`](/slides/python-net/it/aspose.slides.charts/chartdatapoint/format/) | Rappresenta le proprietà di formattazione.<br/>            Lettura/scrittura [`IFormat`](/slides/python-net/it/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/it/aspose.slides.charts/chartdatapoint/marker/) | Specifica un marcatore di dati.<br/>            Sola lettura [`IMarker`](/slides/python-net/it/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/it/aspose.slides.charts/chartdatapoint/set_as_total/) | Imposta il punto dati come totale. Applicato solo per il tipo di serie Waterfall. |
| [`related_legend_entry`](/slides/python-net/it/aspose.slides.charts/chartdatapoint/related_legend_entry/) | Proprietà dell'elemento legenda corrispondente nel caso di tipo di grafico da questa lista:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Sola lettura [`ILegendEntryProperties`](/slides/python-net/it/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/it/aspose.slides.charts/chartdatapoint/data_point_levels/) | Restituisce il contenitore dei livelli del punto dati. Applicato per le serie Treeamp e Sunburst.<br/>            L'indicizzazione dei livelli del punto dati parte da zero. |
| [`index`](/slides/python-net/it/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/it/aspose.slides.charts/chartdatapoint/invert_if_negative/) | Specifica che il punto dati inverte i suoi colori se il valore è negativo.<br/>            Lettura/scrittura **bool**. |
| [`actual_x`](/slides/python-net/it/aspose.slides.charts/chartdatapoint/actual_x/) | Specifica la posizione x reale (sinistra) dell'elemento del grafico rispetto all'angolo in alto a sinistra del grafico.<br/>            Chiamare il metodo IChart.ValidateChartLayout() prima per ottenere i valori reali. <br/>            Lettura **float**. |
| [`actual_y`](/slides/python-net/it/aspose.slides.charts/chartdatapoint/actual_y/) | Specifica la parte superiore reale dell'elemento del grafico rispetto all'angolo in alto a sinistra del grafico.<br/>            Chiamare il metodo IChart.ValidateChartLayout() prima per ottenere i valori reali. <br/>            Lettura **float**. |
| [`actual_width`](/slides/python-net/it/aspose.slides.charts/chartdatapoint/actual_width/) | Specifica la larghezza reale dell'elemento del grafico. Chiamare il metodo IChart.ValidateChartLayout() prima per ottenere i valori reali. <br/>            Lettura **float**. |
| [`actual_height`](/slides/python-net/it/aspose.slides.charts/chartdatapoint/actual_height/) | Specifica l'altezza reale dell'elemento del grafico. Chiamare il metodo IChart.ValidateChartLayout() prima per ottenere i valori reali. <br/>            Lettura **float**. |

## Metodi

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/it/aspose.slides.charts/chartdatapoint/remove/#) | Rimuove DataPoint dalla serie del grafico. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/it/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | Restituisce un colore automatico del punto dati basato sull'indice della serie, sull'indice del punto dati, sulla proprietà ParentSeriesGroup.IsColorVaried e sullo stile del grafico.<br/>            Questo colore è usato per impostazione predefinita se FillType è uguale a NotDefined. |

### Vedi anche
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)