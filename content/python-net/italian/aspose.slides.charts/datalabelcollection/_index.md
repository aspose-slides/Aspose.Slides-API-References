---
title: DataLabelCollection class
second_title: Aspose.Slides per Python tramite .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.charts/datalabelcollection/
---
## DataLabelCollection classe

Rappresenta le etichette di una serie.

Il tipo DataLabelCollection espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`chart`](/slides/python-net/it/aspose.slides.charts/datalabelcollection/chart/) | Restituisce il grafico padre.<br/>            Solo lettura [`IChart`](/slides/python-net/it/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/it/aspose.slides.charts/datalabelcollection/is_visible/) | False significa che l'etichetta dati non è visibile per impostazione predefinita (e quindi tutti i <br/>            flag Show* (ShowValue, ...) della proprietà DefaultDataLabelFormat sono false).<br/>            Solo lettura **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/it/aspose.slides.charts/datalabelcollection/count_of_visible_data_labels/) | Restituisce il numero di etichette dati visibili nella raccolta.<br/>            Solo lettura **int**. |
| [`count`](/slides/python-net/it/aspose.slides.charts/datalabelcollection/count/) | Restituisce il numero di tutte le etichette dati nella raccolta.<br/>            Solo lettura **int**. |
| [`default_data_label_format`](/slides/python-net/it/aspose.slides.charts/datalabelcollection/default_data_label_format/) | Restituisce il formato predefinito dell'etichetta dati.<br/>            Solo lettura [`IDataLabelFormat`](/slides/python-net/it/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/it/aspose.slides.charts/datalabelcollection/leader_lines_format/) | Rappresenta il formato delle linee guida delle etichette dati.<br/>             Solo lettura [`IChartLinesFormat`](/slides/python-net/it/aspose.slides.charts/ichartlinesformat). |
| [`parent_series`](/slides/python-net/it/aspose.slides.charts/datalabelcollection/parent_series/) | Restituisce la serie padre.<br/>            Solo lettura [`IChartSeries`](/slides/python-net/it/aspose.slides.charts/ichartseries). |
| [`slide`](/slides/python-net/it/aspose.slides.charts/datalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides.charts/datalabelcollection/presentation/) |  |

Restituisce l'etichetta dati per il punto dati con l'indice specificato.

## Indicizzatore

| Nome | Descrizione |
| :- | :- |
| [`[index]`](/slides/python-net/it/aspose.slides.charts/datalabelcollection/__getitem__/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`hide(self)`](/slides/python-net/it/aspose.slides.charts/datalabelcollection/hide/#) | Rendi l'etichetta dati nascosta per impostazione predefinita impostando tutti i flag Show* (ShowValue, ...) della proprietà <br/>            DefaultDataLabelFormat allo stato false.<br/>            IsVisible sarà false dopo questa operazione. |
| [`index_of(self, value)`](/slides/python-net/it/aspose.slides.charts/datalabelcollection/index_of/#idatalabel) | Restituisce un indice del DataLabel specificato nella raccolta. |


### Vedi anche
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)