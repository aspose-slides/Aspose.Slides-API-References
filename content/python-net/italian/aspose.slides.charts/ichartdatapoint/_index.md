---
title: IChartDataPoint class
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint classe

Rappresenta il punto dati della serie.

Il tipo IChartDataPoint espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`x_value`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint/x_value/) | Restituisce il valore x del punto dati del grafico.<br/>            Solo lettura [`IStringOrDoubleChartValue`](/slides/python-net/it/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint/y_value/) | Restituisce il valore y del punto dati del grafico.<br/>            Solo lettura [`IDoubleChartValue`](/slides/python-net/it/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint/bubble_size/) | Restituisce la dimensione della bolla del punto dati del grafico.<br/>            Solo lettura [`IDoubleChartValue`](/slides/python-net/it/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint/value/) | Restituisce il valore del punto dati del grafico.<br/>            Solo lettura [`IDoubleChartValue`](/slides/python-net/it/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint/size_value/) | Restituisce il valore della dimensione del punto dati del grafico.<br/>            Utilizzato con i grafici Treemap e Sunburst. <br/>            Solo lettura [`IDoubleChartValue`](/slides/python-net/it/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint/color_value/) | Restituisce il valore colore del punto dati del grafico.<br/>            Utilizzato con i grafici della mappa. <br/>            Solo lettura [`IDoubleChartValue`](/slides/python-net/it/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | Rappresenta i valori delle barre di errore della serie nel caso di tipo di valore Personalizzato.<br/>            Solo lettura [`IErrorBarsCustomValues`](/slides/python-net/it/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint/label/) | Rappresenta l'etichetta del punto dati del grafico.<br/>            Solo lettura [`IDataLabel`](/slides/python-net/it/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | Specifica che le bolle hanno un effetto 3-D applicato.<br/>            Lettura/scrittura **bool**. |
| [`explosion`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint/explosion/) | Specifica l'ammontare di spostamento del punto dati dal centro della torta.<br/>            Lettura/scrittura **int**. |
| [`format`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint/format/) | Rappresenta le proprietà di formattazione.<br/>            Lettura/scrittura [`IFormat`](/slides/python-net/it/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint/marker/) | Specifica un marcatore di dati.<br/>            Solo lettura [`IMarker`](/slides/python-net/it/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | Proprietà della voce della legenda corrispondente nel caso di tipo di grafico da questa lista:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Solo lettura [`ILegendEntryProperties`](/slides/python-net/it/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint/set_as_total/) | Imposta il punto dati come totale. Applicato solo per il tipo di serie Waterfall. |
| [`invert_if_negative`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | Specifica che il punto dati inverte i suoi colori se il valore è negativo.<br/>            Lettura/scrittura **bool**. |
| [`data_point_levels`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint/data_point_levels/) | Restituisce il contenitore dei livelli del punto dati. Applicato per le serie Treeamp e Sunburst.<br/>            L'indicizzazione dei livelli del punto dati parte da zero. |
| [`index`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint/index/) | Determina a quale collezione dei figli del genitore si applica questo punto dati.<br/>            Lettura **int**. |
| [`actual_x`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## Metodi

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint/remove/#) | Rimuove il DataPoint dalla serie del grafico. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | Restituisce un colore automatico del punto dati basato sull'indice della serie, sull'indice del punto dati, sulla proprietà ParentSeriesGroup.IsColorVaried e sullo stile del grafico. <br/>            Questo colore è usato per impostazione predefinita se FillType è uguale a NotDefined. |


### Vedi anche
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)