---
title: IDataLabelCollection class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection classe

Rappresenta le etichette di una serie.

Il tipo IDataLabelCollection espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/it/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | Restituisce il formato predefinito di tutte le etichette dei dati nella raccolta.<br/>            Solo lettura [`IDataLabelFormat`](/slides/python-net/it/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/it/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | Rappresenta il formato delle linee guida delle etichette dei dati.<br/>            Solo lettura [`IChartLinesFormat`](/slides/python-net/it/aspose.slides.charts/ichartlinesformat). |
| [`is_visible`](/slides/python-net/it/aspose.slides.charts/idatalabelcollection/is_visible/) | False indica che l'etichetta dei dati non è visibile per impostazione predefinita (e quindi tutti i flag Show* (ShowValue, ...) della proprietà DefaultDataLabelFormat sono falsi).<br/>            Solo lettura **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/it/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | Restituisce il numero di etichette dei dati visibili nella raccolta.<br/>            Solo lettura **int**. |
| [`count`](/slides/python-net/it/aspose.slides.charts/idatalabelcollection/count/) | Restituisce il numero di tutte le etichette dei dati nella raccolta.<br/>            Solo lettura **int**. |
| [`parent_series`](/slides/python-net/it/aspose.slides.charts/idatalabelcollection/parent_series/) | Restituisce la serie del grafico padre.<br/>            Solo lettura [`IChartSeries`](/slides/python-net/it/aspose.slides.charts/ichartseries). |
| [`chart`](/slides/python-net/it/aspose.slides.charts/idatalabelcollection/chart/) |  |
| [`slide`](/slides/python-net/it/aspose.slides.charts/idatalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides.charts/idatalabelcollection/presentation/) |  |

Restituisce l'etichetta dei dati per il punto dati con l'indice specificato.

## Indicizzatore

| Nome | Descrizione |
| :- | :- |
| [`[index]`](/slides/python-net/it/aspose.slides.charts/idatalabelcollection/__getitem__/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`hide(self)`](/slides/python-net/it/aspose.slides.charts/idatalabelcollection/hide/#) | Rende l'etichetta dei dati nascosta per impostazione predefinita impostando tutti i flag Show* (ShowValue, ...) della <br/>            proprietà DefaultDataLabelFormat nello stato false.<br/>            IsVisible sarà false dopo questa operazione. |
| [`index_of(self, value)`](/slides/python-net/it/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | Restituisce un indice della DataLabel specificata nella raccolta. |


### Vedi anche
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)