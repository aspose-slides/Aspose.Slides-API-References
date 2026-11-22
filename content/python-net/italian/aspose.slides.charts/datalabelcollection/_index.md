---
title: DataLabelCollection class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/datalabelcollection/
---
## classe DataLabelCollection

Rappresenta le etichette di una serie.

Il tipo DataLabelCollection espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`chart`](/slides/python-net/it/aspose.slides.charts/datalabelcollection/chart/) | Restituisce il grafico padre.<br/>            Solo lettura [`IChart`](/slides/python-net/it/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/it/aspose.slides.charts/datalabelcollection/is_visible/) | False indica che l'etichetta dati non è visibile per impostazione predefinita (e quindi tutti i flag Show*- (ShowValue, ...) della proprietà DefaultDataLabelFormat sono false).<br/>            Solo lettura **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/it/aspose.slides.charts/datalabelcollection/count_of_visible_data_labels/) | Ottiene il numero di etichette dati visibili nella collezione.<br/>            Solo lettura **int**. |
| [`count`](/slides/python-net/it/aspose.slides.charts/datalabelcollection/count/) | Ottiene il numero di tutte le etichette dati nella collezione.<br/>            Solo lettura **int**. |
| [`default_data_label_format`](/slides/python-net/it/aspose.slides.charts/datalabelcollection/default_data_label_format/) | Ottiene il formato predefinito dell'etichetta dati.<br/>            Solo lettura [`IDataLabelFormat`](/slides/python-net/it/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/it/aspose.slides.charts/datalabelcollection/leader_lines_format/) | Rappresenta il formato delle linee guida delle etichette dati.<br/>             Solo lettura [`IChartLinesFormat`](/slides/python-net/it/aspose.slides.charts/ichartlinesformat). |
| [`parent_series`](/slides/python-net/it/aspose.slides.charts/datalabelcollection/parent_series/) | Ottiene la serie padre.<br/>            Solo lettura [`IChartSeries`](/slides/python-net/it/aspose.slides.charts/ichartseries). |
| [`default_label_shape_type`](/slides/python-net/it/aspose.slides.charts/datalabelcollection/default_label_shape_type/) | Ottiene o imposta il tipo di forma predefinito per le etichette dati.<br/>             Restituisce [`ShapeType.NOT_DEFINED`](/slides/python-net/it/aspose.slides/shapetype/NOT_DEFINED) se non è definita alcuna forma. |
| [`slide`](/slides/python-net/it/aspose.slides.charts/datalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides.charts/datalabelcollection/presentation/) |  |

Ottiene l'etichetta dati per il punto dati con l'indice specificato.

## Indicizzatore

| Nome | Descrizione |
| :- | :- |
| [`[index]`](/slides/python-net/it/aspose.slides.charts/datalabelcollection/__getitem__/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`hide(self)`](/slides/python-net/it/aspose.slides.charts/datalabelcollection/hide/#) | Nasconde l'etichetta dati per impostazione predefinita impostando tutti i flag Show*- (ShowValue, ...) della proprietà DefaultDataLabelFormat allo stato false.<br/>            IsVisible sarà false dopo questa operazione. |
| [`index_of(self, value)`](/slides/python-net/it/aspose.slides.charts/datalabelcollection/index_of/#idatalabel) | Restituisce un indice della DataLabel specificata nella collezione. |


### Vedi anche
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)