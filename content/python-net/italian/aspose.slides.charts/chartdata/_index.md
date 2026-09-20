---
title: ChartData class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/chartdata/
---
## ChartData classe

Rappresenta i dati utilizzati per la creazione di un grafico.

Il tipo ChartData espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/it/aspose.slides.charts/chartdata/chart_data_workbook/) | Ottiene la factory delle celle per creare celle utilizzate per le serie o le categorie del grafico.<br/>            Solo lettura [`IChartDataWorkbook`](/slides/python-net/it/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/it/aspose.slides.charts/chartdata/series/) | Ottiene le serie.<br/>            Solo lettura [`IChartSeriesCollection`](/slides/python-net/it/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/it/aspose.slides.charts/chartdata/series_groups/) | Ottiene i gruppi di serie.<br/>            Solo lettura [`IChartSeriesGroupCollection`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/it/aspose.slides.charts/chartdata/categories/) | Ottiene le categorie primarie (o sia primarie che secondarie <br/>            se la proprietà [`ChartData.use_secondary_categories`](/slides/python-net/it/aspose.slides.charts/chartdata/use_secondary_categories) è false).<br/>            Solo lettura [`IChartCategoryCollection`](/slides/python-net/it/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/it/aspose.slides.charts/chartdata/use_secondary_categories/) | Se false la proprietà [`ChartData.secondary_categories`](/slides/python-net/it/aspose.slides.charts/chartdata/secondary_categories) restituisce None e i dati <br/>            nella proprietà [`ChartData.categories`](/slides/python-net/it/aspose.slides.charts/chartdata/categories) sono usati sia per le serie primarie che secondarie.<br/>            Se true i dati nella proprietà [`ChartData.secondary_categories`](/slides/python-net/it/aspose.slides.charts/chartdata/secondary_categories) sono usati per le serie secondarie e i dati <br/>            nella proprietà [`ChartData.categories`](/slides/python-net/it/aspose.slides.charts/chartdata/categories) sono usati per le serie primarie.<br/>            Lettura/scrittura **bool**. |
| [`secondary_categories`](/slides/python-net/it/aspose.slides.charts/chartdata/secondary_categories/) | Ottiene le categorie secondarie se la proprietà [`ChartData.use_secondary_categories`](/slides/python-net/it/aspose.slides.charts/chartdata/use_secondary_categories) è true.<br/>            Solo lettura [`IChartCategoryCollection`](/slides/python-net/it/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/it/aspose.slides.charts/chartdata/data_source_type/) | Rappresenta il percorso del workbook esterno se la sorgente dati è esterna, altrimenti None |
| [`external_workbook_path`](/slides/python-net/it/aspose.slides.charts/chartdata/external_workbook_path/) | Rappresenta la sorgente dati del grafico |
| [`embedded_workbook_type`](/slides/python-net/it/aspose.slides.charts/chartdata/embedded_workbook_type/) | Ottiene il tipo del workbook incorporato.<br/>            Restituisce [`WorkbookType.NOT_DEFINED`](/slides/python-net/it/aspose.slides.charts/workbooktype/NOT_DEFINED) se [`ChartData.data_source_type`](/slides/python-net/it/aspose.slides.charts/chartdata/data_source_type) è <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/it/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            Solo lettura [`WorkbookType`](/slides/python-net/it/aspose.slides.charts/workbooktype). |

## Metodi

| Method | Description |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/it/aspose.slides.charts/chartdata/set_external_workbook/#str) | Imposta il workbook esterno come sorgente dati per il grafico. I dati del grafico saranno aggiornati dal workbook di destinazione. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/it/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | Imposta il workbook esterno come sorgente dati per il grafico. |
| [`read_workbook_stream(self)`](/slides/python-net/it/aspose.slides.charts/chartdata/read_workbook_stream/#) | Scrive il workbook Excel interno in un flusso. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/it/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | Inizializza il workbook Excel interno con il valore specificato dall'utente. |
| [`get_range(self)`](/slides/python-net/it/aspose.slides.charts/chartdata/get_range/#) | Ottiene l'intervallo dei dati del grafico. |
| [`set_range(self, formula)`](/slides/python-net/it/aspose.slides.charts/chartdata/set_range/#str) | Imposta l'intervallo dei dati del grafico. Le serie e le categorie saranno aggiornate in base al nuovo intervallo.<br/>            Se il numero di serie nell'intervallo dati è superiore al conteggio delle serie nei dati del grafico, saranno aggiunte serie aggiuntive dello stesso tipo<br/>            dell'ultima serie nella collezione corrente alla fine della collezione. |
| [`switch_row_column(self)`](/slides/python-net/it/aspose.slides.charts/chartdata/switch_row_column/#) | Scambia i dati sull'asse.<br/>            I dati tracciati sull'asse X saranno spostati sull'asse Y e viceversa. |

### Vedi anche
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)