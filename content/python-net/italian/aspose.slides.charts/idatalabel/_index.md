---
title: IDataLabel class
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/idatalabel/
---
## IDataLabel classe

Rappresenta le etichette di una serie.

Il tipo IDataLabel espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`is_visible`](/slides/python-net/it/aspose.slides.charts/idatalabel/is_visible/) | False indica che l'etichetta dei dati non è visibile (e quindi tutti i flag Show*-flags (ShowValue, ...) sono false).<br/>            Sola lettura **bool**. |
| [`data_label_format`](/slides/python-net/it/aspose.slides.charts/idatalabel/data_label_format/) | Restituisce il formato dell'etichetta dei dati.<br/>            Sola lettura [`IDataLabelFormat`](/slides/python-net/it/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/it/aspose.slides.charts/idatalabel/value_from_cell/) | Ottiene o imposta la cella dati della cartella di lavoro. Applicato se la proprietà IDataLabelFormat.ShowLabelValueFromCell è true. |
| [`x`](/slides/python-net/it/aspose.slides.charts/idatalabel/x/) |  |
| [`y`](/slides/python-net/it/aspose.slides.charts/idatalabel/y/) |  |
| [`width`](/slides/python-net/it/aspose.slides.charts/idatalabel/width/) |  |
| [`height`](/slides/python-net/it/aspose.slides.charts/idatalabel/height/) |  |
| [`right`](/slides/python-net/it/aspose.slides.charts/idatalabel/right/) |  |
| [`bottom`](/slides/python-net/it/aspose.slides.charts/idatalabel/bottom/) |  |
| [`chart`](/slides/python-net/it/aspose.slides.charts/idatalabel/chart/) |  |
| [`slide`](/slides/python-net/it/aspose.slides.charts/idatalabel/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides.charts/idatalabel/presentation/) |  |
| [`text_frame_for_overriding`](/slides/python-net/it/aspose.slides.charts/idatalabel/text_frame_for_overriding/) |  |
| [`text_format`](/slides/python-net/it/aspose.slides.charts/idatalabel/text_format/) |  |
| [`actual_x`](/slides/python-net/it/aspose.slides.charts/idatalabel/actual_x/) |  |
| [`actual_y`](/slides/python-net/it/aspose.slides.charts/idatalabel/actual_y/) |  |
| [`actual_width`](/slides/python-net/it/aspose.slides.charts/idatalabel/actual_width/) |  |
| [`actual_height`](/slides/python-net/it/aspose.slides.charts/idatalabel/actual_height/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`hide(self)`](/slides/python-net/it/aspose.slides.charts/idatalabel/hide/#) | Nasconde l'etichetta dei dati impostando tutti i flag Show*-flags (ShowValue, ...) su false.<br/>            IsVisible sarà false dopo questa operazione. |
| [`get_actual_label_text(self)`](/slides/python-net/it/aspose.slides.charts/idatalabel/get_actual_label_text/#) | Restituisce il testo effettivo dell'etichetta basato sulle impostazioni di DataLabelFormat o sul valore TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/it/aspose.slides.charts/idatalabel/add_text_frame_for_overriding/#str) |  |

### Vedi anche
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)