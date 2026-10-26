---
title: SwfOptions class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.export/swfoptions/
---
## SwfOptions classe

Fornisce opzioni che controllano come una presentazione viene salvata in formato Swf.

**Eredità:**[`SwfOptions`](/slides/python-net/it/aspose.slides.export/swfoptions) → [`SaveOptions`](/slides/python-net/it/aspose.slides.export/saveoptions)

Il tipo SwfOptions espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self)`](/slides/python-net/it/aspose.slides.export/swfoptions/__init__/#) | Costruttore predefinito. |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`warning_callback`](/slides/python-net/it/aspose.slides.export/swfoptions/warning_callback/) | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o sarà interrotto.<br/>            Lettura/scrittura [`IWarningCallback`](/slides/python-net/it/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/it/aspose.slides.export/swfoptions/progress_callback/) | Rappresenta un oggetto di callback per gli aggiornamenti di avanzamento del salvataggio in percentuale.<br/>            Vedi [`IProgressCallback`](/slides/python-net/it/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/it/aspose.slides.export/swfoptions/default_regular_font/) | Restituisce o imposta il carattere usato nel caso in cui il carattere sorgente non sia trovato.<br/>            Lettura-scrittura **str**. |
| [`gradient_style`](/slides/python-net/it/aspose.slides.export/swfoptions/gradient_style/) | Restituisce o imposta lo stile visivo del gradiente.<br/>            Lettura/scrittura [`GradientStyle`](/slides/python-net/it/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/it/aspose.slides.export/swfoptions/skip_java_script_links/) | Specifica se ignorare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione. <br/>            Lettura/scrittura **bool**. Il valore predefinito è **false**. |
| [`show_hidden_slides`](/slides/python-net/it/aspose.slides.export/swfoptions/show_hidden_slides/) | Specifica se il documento generato dovrebbe includere diapositive nascoste o meno.<br/>            Il valore predefinito è `false`. |
| [`compressed`](/slides/python-net/it/aspose.slides.export/swfoptions/compressed/) | Specifica se il documento SWF generato dovrebbe essere compresso o meno.<br/>            Il valore predefinito è `true`. |
| [`viewer_included`](/slides/python-net/it/aspose.slides.export/swfoptions/viewer_included/) | Specifica se il documento SWF generato dovrebbe includere il visualizzatore di documenti integrato o meno.<br/>            Il valore predefinito è `true`. |
| [`show_page_border`](/slides/python-net/it/aspose.slides.export/swfoptions/show_page_border/) | Specifica se mostrare il bordo attorno alle pagine. Il valore predefinito è true. |
| [`show_full_screen`](/slides/python-net/it/aspose.slides.export/swfoptions/show_full_screen/) | Mostra/nascondi il pulsante a schermo intero. Può essere sovrascritto in flashvars. Il valore predefinito è true. |
| [`show_page_stepper`](/slides/python-net/it/aspose.slides.export/swfoptions/show_page_stepper/) | Mostra/nascondi il selettore di pagina. Può essere sovrascritto in flashvars. Il valore predefinito è true. |
| [`show_search`](/slides/python-net/it/aspose.slides.export/swfoptions/show_search/) | Mostra/nascondi la sezione di ricerca. Può essere sovrascritto in flashvars. Il valore predefinito è true. |
| [`show_top_pane`](/slides/python-net/it/aspose.slides.export/swfoptions/show_top_pane/) | Mostra/nascondi l’intero pannello superiore. Può essere sovrascritto in flashvars. Il valore predefinito è true. |
| [`show_bottom_pane`](/slides/python-net/it/aspose.slides.export/swfoptions/show_bottom_pane/) | Mostra/nascondi il pannello inferiore. Può essere sovrascritto in flashvars. Il valore predefinito è true. |
| [`show_left_pane`](/slides/python-net/it/aspose.slides.export/swfoptions/show_left_pane/) | Mostra/nascondi il pannello sinistro. Può essere sovrascritto in flashvars. Il valore predefinito è true. |
| [`start_open_left_pane`](/slides/python-net/it/aspose.slides.export/swfoptions/start_open_left_pane/) | Avvia con il pannello sinistro aperto. Può essere sovrascritto in flashvars. Il valore predefinito è false. |
| [`enable_context_menu`](/slides/python-net/it/aspose.slides.export/swfoptions/enable_context_menu/) | Abilita/disabilita il menu contestuale. Il valore predefinito è true. |
| [`logo_image_bytes`](/slides/python-net/it/aspose.slides.export/swfoptions/logo_image_bytes/) | Immagine che verrà visualizzata come logo nell’angolo in alto a destra del visualizzatore.<br/>            L’immagine deve essere PNG 32x64 pixel, altrimenti il logo potrebbe essere visualizzato in modo errato. |
| [`logo_link`](/slides/python-net/it/aspose.slides.export/swfoptions/logo_link/) | Ottiene o imposta l’indirizzo ipertestuale completo per un logo.<br/>            Ha effetto solo se è specificato un [`SwfOptions.logo_image_bytes`](/slides/python-net/it/aspose.slides.export/swfoptions/logo_image_bytes). |
| [`jpeg_quality`](/slides/python-net/it/aspose.slides.export/swfoptions/jpeg_quality/) | Specifica la qualità delle immagini JPEG.<br/>            Il valore predefinito è 95. |
| [`slides_layout_options`](/slides/python-net/it/aspose.slides.export/swfoptions/slides_layout_options/) | Ottiene o imposta la modalità con cui le diapositive sono posizionate sulla pagina durante l’esportazione di una presentazione [`ISlidesLayoutOptions`](/slides/python-net/it/aspose.slides.export/islideslayoutoptions).<br/>            Questa proprietà non supporta l’assegnazione di oggetti di tipo [`HandoutLayoutingOptions`](/slides/python-net/it/aspose.slides.export/handoutlayoutingoptions). |


### Vedi anche
* classe [`SaveOptions`](/slides/python-net/it/aspose.slides.export/saveoptions)
* classe [`SwfOptions`](/slides/python-net/it/aspose.slides.export/swfoptions)
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)