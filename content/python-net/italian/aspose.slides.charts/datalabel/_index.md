---
title: DataLabel class
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.charts/datalabel/
---
## DataLabel classe

Rappresenta le etichette di una serie.

Il tipo DataLabel espone i seguenti membri:

## Costruttori

| Constructor | Description |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/it/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | Crea una nuova istanza della classe DataLabel. |

## Proprietà

| Property | Description |
| :- | :- |
| [`chart`](/slides/python-net/it/aspose.slides.charts/datalabel/chart/) | Restituisce il grafico padre.<br/>            Sola lettura [`IChart`](/slides/python-net/it/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/it/aspose.slides.charts/datalabel/is_visible/) | False significa che l’etichetta dati non è visibile (e quindi tutti i flag Show* (ShowValue, ...) sono false).<br/>            Sola lettura **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/it/aspose.slides.charts/datalabel/text_frame_for_overriding/) | Può contenere un testo formattato riccamente. Se questa proprietà non è None, allora questo valore di testo formattato sovrascrive il testo auto-generato dell’etichetta dati.<br/>            Il testo auto-generato dell’etichetta dati è il testo gestito dalle proprietà ShowSeriesName, ShowValue, … e formattato con la proprietà TextFormatManager.TextFormat.<br/>            Sola lettura [`ITextFrame`](/slides/python-net/it/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/it/aspose.slides.charts/datalabel/text_format/) | Restituisce il formato del testo.<br/>            Sola lettura [`IChartTextFormat`](/slides/python-net/it/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/it/aspose.slides.charts/datalabel/x/) | Restituisce o imposta la coordinata x di un titolo come frazione della larghezza del grafico.<br/>            Lettura/scrittura **float**. |
| [`y`](/slides/python-net/it/aspose.slides.charts/datalabel/y/) | Restituisce o imposta la coordinata y di un titolo come frazione dell’altezza del grafico.<br/>            Lettura/scrittura **float**. |
| [`width`](/slides/python-net/it/aspose.slides.charts/datalabel/width/) | Restituisce o imposta la larghezza di un titolo come frazione della larghezza del grafico.<br/>            Lettura/scrittura **float**. |
| [`height`](/slides/python-net/it/aspose.slides.charts/datalabel/height/) | Restituisce o imposta l’altezza di un titolo come frazione dell’altezza del grafico.<br/>            Lettura/scrittura **float**. |
| [`right`](/slides/python-net/it/aspose.slides.charts/datalabel/right/) | Destra.<br/>            Sola lettura **float**. |
| [`bottom`](/slides/python-net/it/aspose.slides.charts/datalabel/bottom/) | Fondo.<br/>            Sola lettura **float**. |
| [`data_label_format`](/slides/python-net/it/aspose.slides.charts/datalabel/data_label_format/) | Restituisce il formato dell’etichetta dati.<br/>            Sola lettura [`IDataLabelFormat`](/slides/python-net/it/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/it/aspose.slides.charts/datalabel/value_from_cell/) | Ottiene o imposta la cella dati del workbook. Applicato se la proprietà IDataLabelFormat.ShowLabelValueFromCell è true. |
| [`label_shape_type`](/slides/python-net/it/aspose.slides.charts/datalabel/label_shape_type/) | Ottiene o imposta il tipo di forma dell’etichetta dati.<br/>             Restituisce [`ShapeType.NOT_DEFINED`](/slides/python-net/it/aspose.slides/shapetype/NOT_DEFINED) se non è definita alcuna forma. |
| [`actual_x`](/slides/python-net/it/aspose.slides.charts/datalabel/actual_x/) | Specifica la posizione x reale (sinistra) dell’elemento del grafico rispetto all’angolo superiore sinistro del grafico.<br/>            Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Lettura **float**. |
| [`actual_y`](/slides/python-net/it/aspose.slides.charts/datalabel/actual_y/) | Specifica la parte superiore reale dell’elemento del grafico rispetto all’angolo superiore sinistro del grafico.<br/>            Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Lettura **float**. |
| [`actual_width`](/slides/python-net/it/aspose.slides.charts/datalabel/actual_width/) | Specifica la larghezza reale dell’elemento del grafico. Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Lettura **float**. |
| [`actual_height`](/slides/python-net/it/aspose.slides.charts/datalabel/actual_height/) | Specifica l’altezza reale dell’elemento del grafico. Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Lettura **float**. |
| [`slide`](/slides/python-net/it/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides.charts/datalabel/presentation/) |  |

## Metodi

| Method | Description |
| :- | :- |
| [`hide(self)`](/slides/python-net/it/aspose.slides.charts/datalabel/hide/#) | Nascondi l’etichetta dati impostando tutti i flag Show* (ShowValue, ...) nello stato false.<br/>            IsVisible sarà false dopo questa operazione. |
| [`get_actual_label_text(self)`](/slides/python-net/it/aspose.slides.charts/datalabel/get_actual_label_text/#) | Restituisce il testo reale dell’etichetta in base alle impostazioni di DataLabelFormat o al valore TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/it/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | Inizializza TextFrameForOverriding con il testo nel parametro "text".<br/>            Se TextFrameForOverriding è già inizializzato, cambia semplicemente il suo testo. |


### Vedi anche
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)