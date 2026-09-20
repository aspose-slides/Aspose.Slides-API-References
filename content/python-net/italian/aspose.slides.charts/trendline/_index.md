---
title: Trendline class
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/trendline/
---
## Classe Trendline

La classe rappresenta la linea di tendenza di una serie di grafico

Il tipo Trendline espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`trendline_name`](/slides/python-net/it/aspose.slides.charts/trendline/trendline_name/) | Ottiene o imposta il nome della linea di tendenza.<br/>            Lettura/scrittura **str**. |
| [`trendline_type`](/slides/python-net/it/aspose.slides.charts/trendline/trendline_type/) | Ottiene o imposta il tipo della linea di tendenza.<br/>            Lettura/scrittura [`TrendlineType`](/slides/python-net/it/aspose.slides.charts/trendlinetype). |
| [`format`](/slides/python-net/it/aspose.slides.charts/trendline/format/) | Rappresenta il formato della linea di tendenza.<br/>            Lettura/scrittura [`IFormat`](/slides/python-net/it/aspose.slides.charts/iformat). |
| [`backward`](/slides/python-net/it/aspose.slides.charts/trendline/backward/) | Specifica il numero di categorie (o unità su un grafico a dispersione) che la linea di tendenza si estende prima<br/>            dei dati per la serie in esame. Su grafici a dispersione e non a dispersione, il valore deve essere un valore non negativo.<br/>            Lettura/scrittura **float**. |
| [`forward`](/slides/python-net/it/aspose.slides.charts/trendline/forward/) | Specifica il numero di categorie (o unità su un grafico a dispersione) che la linea di tendenza si estende dopo<br/>            i dati per la serie in esame. Su grafici a dispersione e non a dispersione, il valore deve essere un valore non negativo.<br/>            Lettura/scrittura **float**. |
| [`intercept`](/slides/python-net/it/aspose.slides.charts/trendline/intercept/) | Specifica il valore in cui la linea di tendenza deve attraversare l'asse y. Questa proprietà è supportata solo<br/>            quando il tipo di linea di tendenza è exp, linear o poly.<br/>            Lettura/scrittura **float**. |
| [`display_equation`](/slides/python-net/it/aspose.slides.charts/trendline/display_equation/) | Specifica che l'equazione della linea di tendenza è visualizzata sul grafico (nella stessa etichetta del valore R²).<br/>            Lettura/scrittura **bool**. |
| [`order`](/slides/python-net/it/aspose.slides.charts/trendline/order/) | Specifica l'ordine della linea di tendenza polinomiale. È ignorato per altri tipi di linea di tendenza. Il valore deve essere compreso tra 2 e 6.<br/>            Lettura/scrittura **int**. |
| [`period`](/slides/python-net/it/aspose.slides.charts/trendline/period/) | Specifica il periodo della linea di tendenza per una linea di tendenza a media mobile. È ignorato per altre varianti di linea di tendenza. Il valore deve essere compreso tra 2 e 255.<br/>            Lettura/scrittura **int**. |
| [`display_r_squared_value`](/slides/python-net/it/aspose.slides.charts/trendline/display_r_squared_value/) | Specifica che il valore R² della linea di tendenza è visualizzato sul grafico (nella stessa etichetta dell'equazione).<br/>            Lettura/scrittura **bool**. |
| [`related_legend_entry`](/slides/python-net/it/aspose.slides.charts/trendline/related_legend_entry/) | Rappresenta la voce di legenda relativa a questa linea di tendenza<br/>            Solo lettura [`ILegendEntryProperties`](/slides/python-net/it/aspose.slides.charts/ilegendentryproperties). |
| [`text_frame_for_overriding`](/slides/python-net/it/aspose.slides.charts/trendline/text_frame_for_overriding/) | Può contenere testo formattato riccamente. Se questa proprietà non è None, il valore di testo formattato sovrascrive il testo generato automaticamente dell'etichetta dati.<br/>            Il testo generato automaticamente dell'etichetta dati è il testo gestito dalle proprietà ShowSeriesName,<br/>            ShowValue, ... e formattato con la proprietà TextFormatManager.TextFormat.<br/>            Solo lettura [`ITextFrame`](/slides/python-net/it/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/it/aspose.slides.charts/trendline/text_format/) | Restituisce il formato del testo.<br/>            Solo lettura [`IChartTextFormat`](/slides/python-net/it/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/it/aspose.slides.charts/trendline/chart/) | Restituisce il grafico genitore.<br/>            Solo lettura [`IChart`](/slides/python-net/it/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/it/aspose.slides.charts/trendline/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides.charts/trendline/presentation/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/it/aspose.slides.charts/trendline/add_text_frame_for_overriding/#str) | Inizializza TextFrameForOverriding con il testo nel parametro "text".<br/>Se TextFrameForOverriding è già stato inizializzato, cambia semplicemente il suo testo. |

### Vedi anche
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)