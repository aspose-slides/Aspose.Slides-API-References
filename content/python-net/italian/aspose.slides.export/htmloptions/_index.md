---
title: HtmlOptions class
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.export/htmloptions/
---
## HtmlOptions classe

Rappresenta le opzioni di esportazione HTML.

**Ereditarietà:**[`HtmlOptions`](/slides/python-net/it/aspose.slides.export/htmloptions) → [`SaveOptions`](/slides/python-net/it/aspose.slides.export/saveoptions)

Il tipo HtmlOptions espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self, link_embed_controller)`](/slides/python-net/it/aspose.slides.export/htmloptions/__init__/#ilinkembedcontroller) | Crea un nuovo oggetto HtmlOptions specificando il callback. |
| [`__init__(self)`](/slides/python-net/it/aspose.slides.export/htmloptions/__init__/#) | Crea un nuovo oggetto HtmlOptions per il salvataggio in un singolo file HTML. |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`warning_callback`](/slides/python-net/it/aspose.slides.export/htmloptions/warning_callback/) | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuare o essere interrotto.<br/>            Lettura/scrittura [`IWarningCallback`](/slides/python-net/it/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/it/aspose.slides.export/htmloptions/progress_callback/) | Rappresenta un oggetto callback per gli aggiornamenti di avanzamento del salvataggio in percentuale.<br/>            Vedi [`IProgressCallback`](/slides/python-net/it/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/it/aspose.slides.export/htmloptions/default_regular_font/) | Restituisce o imposta il font utilizzato nel caso il font di origine non venga trovato.<br/>            Lettura/scrittura **str**. |
| [`gradient_style`](/slides/python-net/it/aspose.slides.export/htmloptions/gradient_style/) | Restituisce o imposta lo stile visivo del gradiente.<br/>            Lettura/scrittura [`GradientStyle`](/slides/python-net/it/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/it/aspose.slides.export/htmloptions/skip_java_script_links/) | Specifica se saltare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione.<br/>            Lettura/scrittura **bool**. Il valore predefinito è **false**. |
| [`slides_layout_options`](/slides/python-net/it/aspose.slides.export/htmloptions/slides_layout_options/) | Ottiene o imposta la modalità con cui le diapositive vengono posizionate sulla pagina durante l'esportazione di una presentazione [`ISlidesLayoutOptions`](/slides/python-net/it/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/it/aspose.slides.export/htmloptions/ink_options/) | Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato.<br/>            Sola lettura [`IInkOptions`](/slides/python-net/it/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/it/aspose.slides.export/htmloptions/show_hidden_slides/) | Specifica se il documento generato debba includere diapositive nascoste o meno.<br/>            Il valore predefinito è `false`. |
| [`html_formatter`](/slides/python-net/it/aspose.slides.export/htmloptions/html_formatter/) | Restituisce o imposta il modello HTML.<br/>            Lettura/scrittura [`IHtmlFormatter`](/slides/python-net/it/aspose.slides.export/ihtmlformatter). |
| [`disable_font_ligatures`](/slides/python-net/it/aspose.slides.export/htmloptions/disable_font_ligatures/) | Ottiene o imposta un valore che indica se il testo viene resa senza utilizzare le legature.<br/>            Quando impostato a `true`, le legature saranno disattivate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata a `false`. |
| [`slide_image_format`](/slides/python-net/it/aspose.slides.export/htmloptions/slide_image_format/) | Restituisce o imposta le opzioni del formato immagine della diapositiva.<br/>            Lettura/scrittura [`ISlideImageFormat`](/slides/python-net/it/aspose.slides.export/islideimageformat). |
| [`jpeg_quality`](/slides/python-net/it/aspose.slides.export/htmloptions/jpeg_quality/) | Restituisce o imposta un valore che determina la qualità delle immagini JPEG all'interno del documento PDF.<br/>            Lettura/scrittura **int**. |
| [`pictures_compression`](/slides/python-net/it/aspose.slides.export/htmloptions/pictures_compression/) | Rappresenta il livello di compressione delle immagini |
| [`delete_pictures_cropped_areas`](/slides/python-net/it/aspose.slides.export/htmloptions/delete_pictures_cropped_areas/) | Un flag booleano indica se le parti ritagliate rimangono come parte del documento. Se vero le parti ritagliate saranno rimosse, se falso saranno serializzate nel documento (il che può eventualmente portare a un file più grande) |
| [`svg_responsive_layout`](/slides/python-net/it/aspose.slides.export/htmloptions/svg_responsive_layout/) | Vero per escludere gli attributi width e height dal contenitore svg - questo renderà il layout responsivo. Falso - altrimenti.<br/>            Lettura/scrittura **bool**. |

### Vedi anche
* classe [`HtmlOptions`](/slides/python-net/it/aspose.slides.export/htmloptions)
* classe [`SaveOptions`](/slides/python-net/it/aspose.slides.export/saveoptions)
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)