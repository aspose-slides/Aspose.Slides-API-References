---
title: DataLabel class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/datalabel/
---
## DataLabel classe

Rappresenta le etichette di una serie.

Il tipo DataLabel espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/it/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | Crea una nuova istanza della classe DataLabel. |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`chart`](/slides/python-net/it/aspose.slides.charts/datalabel/chart/) | Restituisce il grafico genitore.<br/>            Solo lettura [`IChart`](/slides/python-net/it/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/it/aspose.slides.charts/datalabel/is_visible/) | False significa che l'etichetta dati non è visibile (e quindi tutti i flag Show* (ShowValue, ...) sono false).<br/>            Solo lettura **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/it/aspose.slides.charts/datalabel/text_frame_for_overriding/) | Può contenere un testo riccamente formattato. Se questa proprietà non è None, allora questo <br/>            valore di testo formattato sovrascrive il testo auto-generato dell'etichetta dati.<br/>            Il testo auto-generato dell'etichetta dati è il testo gestito dalle proprietà ShowSeriesName, <br/>            ShowValue, ... e formattato con la proprietà TextFormatManager.TextFormat.<br/>            Solo lettura [`ITextFrame`](/slides/python-net/it/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/it/aspose.slides.charts/datalabel/text_format/) | Restituisce il formato del testo.<br/>            Solo lettura [`IChartTextFormat`](/slides/python-net/it/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/it/aspose.slides.charts/datalabel/x/) | Restituisce o imposta la coordinata x di un titolo come frazione della larghezza del grafico.<br/>            Lettura/scrittura **float**. |
| [`y`](/slides/python-net/it/aspose.slides.charts/datalabel/y/) | Restituisce o imposta la coordinata y di un titolo come frazione dell'altezza del grafico.<br/>            Lettura/scrittura **float**. |
| [`width`](/slides/python-net/it/aspose.slides.charts/datalabel/width/) | Restituisce o imposta la larghezza di un titolo come frazione della larghezza del grafico.<br/>            Lettura/scrittura **float**. |
| [`height`](/slides/python-net/it/aspose.slides.charts/datalabel/height/) | Restituisce o imposta l'altezza di un titolo come frazione dell'altezza del grafico.<br/>            Lettura/scrittura **float**. |
| [`right`](/slides/python-net/it/aspose.slides.charts/datalabel/right/) | Destra.<br/>            Solo lettura **float**. |
| [`bottom`](/slides/python-net/it/aspose.slides.charts/datalabel/bottom/) | Inferiore.<br/>            Solo lettura **float**. |
| [`data_label_format`](/slides/python-net/it/aspose.slides.charts/datalabel/data_label_format/) | Restituisce il formato dell'etichetta dati.<br/>            Solo lettura [`IDataLabelFormat`](/slides/python-net/it/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/it/aspose.slides.charts/datalabel/value_from_cell/) | Ottiene o imposta la cella dati della cartella di lavoro. Applicato se la proprietà IDataLabelFormat.ShowLabelValueFromCell è true. |
| [`actual_x`](/slides/python-net/it/aspose.slides.charts/datalabel/actual_x/) | Specifica la posizione x reale (sinistra) dell'elemento del grafico rispetto all'angolo superiore sinistro del grafico.<br/>            Chiama il metodo IChart.ValidateChartLayout() prima per ottenere i valori reali. <br/>            Lettura **float**. |
| [`actual_y`](/slides/python-net/it/aspose.slides.charts/datalabel/actual_y/) | Specifica la parte superiore reale dell'elemento del grafico rispetto all'angolo superiore sinistro del grafico.<br/>            Chiama il metodo IChart.ValidateChartLayout() prima per ottenere i valori reali. <br/>            Lettura **float**. |
| [`actual_width`](/slides/python-net/it/aspose.slides.charts/datalabel/actual_width/) | Specifica la larghezza reale dell'elemento del grafico. Chiama il metodo IChart.ValidateChartLayout() prima per ottenere i valori reali. <br/>            Lettura **float**. |
| [`actual_height`](/slides/python-net/it/aspose.slides.charts/datalabel/actual_height/) | Specifica l'altezza reale dell'elemento del grafico. Chiama il metodo IChart.ValidateChartLayout() prima per ottenere i valori reali. <br/>            Lettura **float**. |
| [`slide`](/slides/python-net/it/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides.charts/datalabel/presentation/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`hide(self)`](/slides/python-net/it/aspose.slides.charts/datalabel/hide/#) | Nasconde l'etichetta dati impostando tutti i flag Show* (ShowValue, ...) in stato false.<br/>            IsVisible sarà false dopo questa operazione. |
| [`get_actual_label_text(self)`](/slides/python-net/it/aspose.slides.charts/datalabel/get_actual_label_text/#) | Restituisce il testo effettivo dell'etichetta basato sulle impostazioni di DataLabelFormat o sul valore TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/it/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | Inizializza TextFrameForOverriding con il testo nel parametro "text".<br/>            Se TextFrameForOverriding è già inizializzato, cambia semplicemente il suo testo. |

### Vedi anche
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)