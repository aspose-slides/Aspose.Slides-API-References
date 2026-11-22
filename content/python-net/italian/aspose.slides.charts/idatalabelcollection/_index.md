---
title: IDataLabelCollection class
second_title: Aspose.Slides per Python tramite .NET API Reference
description: 
type: docs
url: /it/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection classe

Rappresenta le etichette di una serie.

Il tipo IDataLabelCollection espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/it/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | Restituisce il formato predefinito di tutte le etichette dati nella collezione.<br/>            Solo lettura [`IDataLabelFormat`](/slides/python-net/it/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/it/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | Rappresenta il formato delle linee guida delle etichette dati.<br/>             Solo lettura [`IChartLinesFormat`](/slides/python-net/it/aspose.slides.charts/ichartlinesformat). |
| [`is_visible`](/slides/python-net/it/aspose.slides.charts/idatalabelcollection/is_visible/) | False indica che l'etichetta dati non è visibile per impostazione predefinita (e quindi tutti i flag Show*- (ShowValue, ...) della proprietà DefaultDataLabelFormat sono falsi).<br/>            Solo lettura **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/it/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | Restituisce il numero di etichette dati visibili nella collezione.<br/>            Solo lettura **int**. |
| [`count`](/slides/python-net/it/aspose.slides.charts/idatalabelcollection/count/) | Restituisce il numero totale di etichette dati nella collezione.<br/>            Solo lettura **int**. |
| [`parent_series`](/slides/python-net/it/aspose.slides.charts/idatalabelcollection/parent_series/) | Restituisce la serie del grafico padre.<br/>            Solo lettura [`IChartSeries`](/slides/python-net/it/aspose.slides.charts/ichartseries). |
| [`default_label_shape_type`](/slides/python-net/it/aspose.slides.charts/idatalabelcollection/default_label_shape_type/) | Ottiene o imposta il tipo di forma predefinito per le etichette dati.<br/>             Restituisce [`ShapeType.NOT_DEFINED`](/slides/python-net/it/aspose.slides/shapetype/NOT_DEFINED) se non è definita alcuna forma. |
| [`chart`](/slides/python-net/it/aspose.slides.charts/idatalabelcollection/chart/) |  |
| [`slide`](/slides/python-net/it/aspose.slides.charts/idatalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides.charts/idatalabelcollection/presentation/) |  |

Ottiene l'etichetta dati per il punto dati con l'indice specificato.

## Indicizzatore

| Nome | Descrizione |
| :- | :- |
| [`[index]`](/slides/python-net/it/aspose.slides.charts/idatalabelcollection/__getitem__/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`hide(self)`](/slides/python-net/it/aspose.slides.charts/idatalabelcollection/hide/#) | Rende l'etichetta dati nascosta per impostazione predefinita impostando tutti i flag Show*- (ShowValue, ...) della <br/>            proprietà DefaultDataLabelFormat allo stato falso.<br/>            IsVisible sarà false dopo questa operazione. |
| [`index_of(self, value)`](/slides/python-net/it/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | Restituisce un indice della DataLabel specificata nella collezione. |


### Vedi anche
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)