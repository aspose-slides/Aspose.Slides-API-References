---
title: GifOptions class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.export/gifoptions/
---
## GifOptions classe

Rappresenta le opzioni di esportazione GIF.

**Eredità:**[`GifOptions`](/slides/python-net/it/aspose.slides.export/gifoptions) → [`SaveOptions`](/slides/python-net/it/aspose.slides.export/saveoptions)

Il tipo GifOptions espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self)`](/slides/python-net/it/aspose.slides.export/gifoptions/__init__/#) | Inizializza una nuova istanza della classe GifOptions. |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`warning_callback`](/slides/python-net/it/aspose.slides.export/gifoptions/warning_callback/) | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o sarà interrotto.<br/>            Lettura/scrittura [`IWarningCallback`](/slides/python-net/it/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/it/aspose.slides.export/gifoptions/progress_callback/) | Rappresenta un oggetto di callback per gli aggiornamenti di avanzamento del salvataggio in percentuale.<br/>            Vedi [`IProgressCallback`](/slides/python-net/it/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/it/aspose.slides.export/gifoptions/default_regular_font/) | Restituisce o imposta il font usato nel caso in cui il font sorgente non sia trovato.<br/>            Lettura-scrittura **str**. |
| [`gradient_style`](/slides/python-net/it/aspose.slides.export/gifoptions/gradient_style/) | Restituisce o imposta lo stile visuale del gradiente.<br/>            Lettura/scrittura [`GradientStyle`](/slides/python-net/it/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/it/aspose.slides.export/gifoptions/skip_java_script_links/) | Specifica se saltare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione.<br/>            Lettura/scrittura **bool**. Il valore predefinito è **false**. |
| [`frame_size`](/slides/python-net/it/aspose.slides.export/gifoptions/frame_size/) | Ottiene o imposta la dimensione del frame. |
| [`export_hidden_slides`](/slides/python-net/it/aspose.slides.export/gifoptions/export_hidden_slides/) | Determina se le diapositive nascoste saranno esportate.<br/>            Il valore predefinito è false. |
| [`transition_fps`](/slides/python-net/it/aspose.slides.export/gifoptions/transition_fps/) | Ottiene o imposta FPS di transizione [frames/sec]<br/>            Il valore predefinito è 25. |
| [`default_delay`](/slides/python-net/it/aspose.slides.export/gifoptions/default_delay/) | Ottiene o imposta il tempo di ritardo predefinito [ms]. Questo valore sarà usato se [`ISlideShowTransition.advance_after_time`](/slides/python-net/it/aspose.slides/islideshowtransition/advance_after_time) non è impostato.<br/>            Il valore predefinito è 1000. |

### Vedi anche
* classe [`GifOptions`](/slides/python-net/it/aspose.slides.export/gifoptions)
* classe [`SaveOptions`](/slides/python-net/it/aspose.slides.export/saveoptions)
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)