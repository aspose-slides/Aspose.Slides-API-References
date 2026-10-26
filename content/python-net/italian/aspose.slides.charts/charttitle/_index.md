---
title: ChartTitle class
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/charttitle/
---
## ChartTitle classe

Rappresenta le proprietà del titolo del grafico.

Il tipo ChartTitle espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`x`](/slides/python-net/it/aspose.slides.charts/charttitle/x/) | Restituisce o imposta la coordinata x di un titolo come frazione della larghezza del grafico.<br/>            Read/write **float**. |
| [`y`](/slides/python-net/it/aspose.slides.charts/charttitle/y/) | Restituisce o imposta la coordinata y di un titolo come frazione dell'altezza del grafico.<br/>            Read/write **float**. |
| [`width`](/slides/python-net/it/aspose.slides.charts/charttitle/width/) | Restituisce o imposta la larghezza di un titolo come frazione della larghezza del grafico.<br/>            Read/write **float**. |
| [`height`](/slides/python-net/it/aspose.slides.charts/charttitle/height/) | Restituisce o imposta l'altezza di un titolo come frazione dell'altezza del grafico.<br/>            Read/write **float**. |
| [`right`](/slides/python-net/it/aspose.slides.charts/charttitle/right/) | Destra.<br/>            Read-only **float**. |
| [`bottom`](/slides/python-net/it/aspose.slides.charts/charttitle/bottom/) | Inferiore.<br/>            Read-only **float**. |
| [`overlay`](/slides/python-net/it/aspose.slides.charts/charttitle/overlay/) | Determina se altri elementi del grafico possono sovrapporsi al titolo.<br/>            Read/write **bool**. |
| [`format`](/slides/python-net/it/aspose.slides.charts/charttitle/format/) | Restituisce gli stili di riempimento, linea ed effetto di un titolo.<br/>            Read-only [`IFormat`](/slides/python-net/it/aspose.slides.charts/iformat). |
| [`text_frame_for_overriding`](/slides/python-net/it/aspose.slides.charts/charttitle/text_frame_for_overriding/) | Può contenere un testo formattato ricco. Se questa proprietà non è None, allora questo <br/>            valore di testo formattato sovrascrive il testo generato automaticamente.<br/>            Il testo generato automaticamente è una proprietà implicita dell'etichetta dei dati, dell'etichetta dell'unità di visualizzazione dell'asse dei valori, del titolo dell'asse, del titolo del grafico, dell'etichetta della linea di tendenza.<br/>            Il testo generato automaticamente è formattato con la proprietà IFormattedTextContainer.TextFormat.<br/>            Read-only [`ITextFrame`](/slides/python-net/it/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/it/aspose.slides.charts/charttitle/text_format/) | Restituisce il formato del testo.<br/>            Read-only [`IChartTextFormat`](/slides/python-net/it/aspose.slides.charts/icharttextformat). |
| [`actual_x`](/slides/python-net/it/aspose.slides.charts/charttitle/actual_x/) | Specifica la posizione x reale (sinistra) dell'elemento del grafico rispetto all'angolo in alto a sinistra del grafico.<br/>            Chiama il metodo IChart.ValidateChartLayout() prima per ottenere i valori reali. <br/>            Read **float**. |
| [`actual_y`](/slides/python-net/it/aspose.slides.charts/charttitle/actual_y/) | Specifica la posizione superiore reale dell'elemento del grafico rispetto all'angolo in alto a sinistra del grafico.<br/>            Chiama il metodo IChart.ValidateChartLayout() prima per ottenere i valori reali. <br/>            Read **float**. |
| [`actual_width`](/slides/python-net/it/aspose.slides.charts/charttitle/actual_width/) | Specifica la larghezza reale dell'elemento del grafico. Chiama il metodo IChart.ValidateChartLayout() prima per ottenere i valori reali. <br/>            Read **float**. |
| [`actual_height`](/slides/python-net/it/aspose.slides.charts/charttitle/actual_height/) | Specifica l'altezza reale dell'elemento del grafico. Chiama il metodo IChart.ValidateChartLayout() prima per ottenere i valori reali. <br/>            Read **float**. |
| [`chart`](/slides/python-net/it/aspose.slides.charts/charttitle/chart/) | Restituisce il grafico padre.<br/>            Read-only [`IChart`](/slides/python-net/it/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/it/aspose.slides.charts/charttitle/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides.charts/charttitle/presentation/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/it/aspose.slides.charts/charttitle/add_text_frame_for_overriding/#str) | Inizializza TextFrameForOverriding con il testo nel parametro "text".<br/>            Se TextFrameForOverriding è già inizializzato, allora cambia semplicemente il suo testo. |

### Vedi anche
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)