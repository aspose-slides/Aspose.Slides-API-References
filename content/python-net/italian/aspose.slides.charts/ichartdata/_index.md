---
title: IChartData class
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/ichartdata/
---
## IChartData classe

Rappresenta i dati utilizzati per la creazione di un grafico.

Il tipo IChartData espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/it/aspose.slides.charts/ichartdata/chart_data_workbook/) | Ottiene la factory delle celle per creare celle utilizzate per le serie o le categorie del grafico.<br/>Sola lettura [`IChartDataWorkbook`](/slides/python-net/it/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/it/aspose.slides.charts/ichartdata/series/) | Ottiene le serie.<br/>Sola lettura [`IChartSeriesCollection`](/slides/python-net/it/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/it/aspose.slides.charts/ichartdata/series_groups/) | Ottiene i gruppi di serie.<br/>Sola lettura [`IChartSeriesGroupCollection`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/it/aspose.slides.charts/ichartdata/categories/) | Ottiene le categorie primarie (o sia le categorie primarie che secondarie <br/>se la proprietà [`IChartData.use_secondary_categories`](/slides/python-net/it/aspose.slides.charts/ichartdata/use_secondary_categories) è false).<br/>Sola lettura [`IChartCategoryCollection`](/slides/python-net/it/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/it/aspose.slides.charts/ichartdata/use_secondary_categories/) | Se false, allora la proprietà [`IChartData.secondary_categories`](/slides/python-net/it/aspose.slides.charts/ichartdata/secondary_categories) restituisce None e i dati <br/>nella proprietà [`IChartData.categories`](/slides/python-net/it/aspose.slides.charts/ichartdata/categories) viene utilizzato sia per le serie primarie che secondarie.<br/>Se true, allora i dati nella proprietà [`IChartData.secondary_categories`](/slides/python-net/it/aspose.slides.charts/ichartdata/secondary_categories) vengono utilizzati per le serie secondarie e i dati <br/>nella proprietà [`IChartData.categories`](/slides/python-net/it/aspose.slides.charts/ichartdata/categories) vengono utilizzati per le serie primarie.<br/>Lettura/scrittura **bool**. |
| [`secondary_categories`](/slides/python-net/it/aspose.slides.charts/ichartdata/secondary_categories/) | Ottiene le categorie secondarie se la proprietà [`IChartData.use_secondary_categories`](/slides/python-net/it/aspose.slides.charts/ichartdata/use_secondary_categories) è true.<br/>Sola lettura [`IChartCategoryCollection`](/slides/python-net/it/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/it/aspose.slides.charts/ichartdata/data_source_type/) | Rappresenta la fonte dati del grafico |
| [`external_workbook_path`](/slides/python-net/it/aspose.slides.charts/ichartdata/external_workbook_path/) | Rappresenta il percorso della cartella di lavoro esterna se la fonte dati è esterna, None altrimenti |
| [`embedded_workbook_type`](/slides/python-net/it/aspose.slides.charts/ichartdata/embedded_workbook_type/) | Ottiene il tipo della cartella di lavoro incorporata.<br/>Restituisce [`WorkbookType.NOT_DEFINED`](/slides/python-net/it/aspose.slides.charts/workbooktype/NOT_DEFINED) se [`IChartData.data_source_type`](/slides/python-net/it/aspose.slides.charts/ichartdata/data_source_type) è <br/>[`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/it/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>Sola lettura [`WorkbookType`](/slides/python-net/it/aspose.slides.charts/workbooktype). |

## Metodi

| Method | Description |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/it/aspose.slides.charts/ichartdata/set_external_workbook/#str) | Imposta la cartella di lavoro esterna come fonte dati per il grafico. I dati del grafico saranno aggiornati dalla cartella di lavoro di destinazione. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/it/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | Imposta la cartella di lavoro esterna come fonte dati per il grafico. |
| [`read_workbook_stream(self)`](/slides/python-net/it/aspose.slides.charts/ichartdata/read_workbook_stream/#) | Scrive la cartella di lavoro Excel contenuta internamente in un flusso in memoria. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/it/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | Inizializza la cartella di lavoro Excel contenuta internamente con il valore specificato dall'utente. |
| [`set_range(self, formula)`](/slides/python-net/it/aspose.slides.charts/ichartdata/set_range/#str) | Imposta l'intervallo dei dati del grafico. Le serie e le categorie saranno aggiornate in base al nuovo intervallo di dati.<br/>Se il numero di serie nell'intervallo dati è maggiore del conteggio delle serie nei dati del grafico, allora verranno aggiunte serie aggiuntive con lo stesso tipo dell'ultima serie nella collezione corrente alla fine della collezione. |
| [`get_range(self)`](/slides/python-net/it/aspose.slides.charts/ichartdata/get_range/#) | Ottiene l'intervallo dei dati del grafico. |
| [`switch_row_column(self)`](/slides/python-net/it/aspose.slides.charts/ichartdata/switch_row_column/#) | Scambia i dati sull'asse.<br/>I dati tracciati sull'asse X verranno spostati sull'asse Y e viceversa. |
| [`refresh_data(self)`](/slides/python-net/it/aspose.slides.charts/ichartdata/refresh_data/#) | Aggiorna i dati del grafico ricaricandoli dalla cartella di lavoro sorgente. |

### Vedi anche
* module [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)