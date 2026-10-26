---
title: SVGOptions class
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.export/svgoptions/
---
## SVGOptions classe

Rappresenta un'opzione SVG.

**Inheritance:**[`SVGOptions`](/slides/python-net/it/aspose.slides.export/svgoptions) → [`SaveOptions`](/slides/python-net/it/aspose.slides.export/saveoptions)

Il tipo SVGOptions espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self)`](/slides/python-net/it/aspose.slides.export/svgoptions/__init__/#) | Inizializza una nuova istanza della classe SVGOptions. |
| [`__init__(self, link_embed_controller)`](/slides/python-net/it/aspose.slides.export/svgoptions/__init__/#ilinkembedcontroller) | Inizializza una nuova istanza della classe SVGOptions specificando l'oggetto controller di incorporamento del collegamento. |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`warning_callback`](/slides/python-net/it/aspose.slides.export/svgoptions/warning_callback/) | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o sarà interrotto.<br/>            Lettura/scrittura [`IWarningCallback`](/slides/python-net/it/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/it/aspose.slides.export/svgoptions/progress_callback/) | Rappresenta un oggetto di callback per gli aggiornamenti di avanzamento del salvataggio in percentuale.<br/>            Vedi [`IProgressCallback`](/slides/python-net/it/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/it/aspose.slides.export/svgoptions/default_regular_font/) | Restituisce o imposta il font usato nel caso il font sorgente non sia trovato.<br/>            Lettura/scrittura **str**. |
| [`gradient_style`](/slides/python-net/it/aspose.slides.export/svgoptions/gradient_style/) | Restituisce o imposta lo stile visivo del gradiente.<br/>            Lettura/scrittura [`GradientStyle`](/slides/python-net/it/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/it/aspose.slides.export/svgoptions/skip_java_script_links/) | Specifica se saltare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione.<br/>            Lettura/scrittura **bool**. Il valore predefinito è **false**. |
| [`ink_options`](/slides/python-net/it/aspose.slides.export/svgoptions/ink_options/) | Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato.<br/>            Sola lettura [`IInkOptions`](/slides/python-net/it/aspose.slides.export/iinkoptions) |
| [`use_frame_size`](/slides/python-net/it/aspose.slides.export/svgoptions/use_frame_size/) | Determina se il frame di testo sarà incluso in un'area di rendering o no.<br/>            Lettura/scrittura **bool**.<br/>            Il valore predefinito è false. |
| [`use_frame_rotation`](/slides/python-net/it/aspose.slides.export/svgoptions/use_frame_rotation/) | Determina se eseguire la rotazione specificata della forma durante il rendering o no.<br/>            Lettura/scrittura **bool**.<br/>            Il valore predefinito è true. |
| [`vectorize_text`](/slides/python-net/it/aspose.slides.export/svgoptions/vectorize_text/) | Determina se il testo su una diapositiva sarà salvato come grafica.<br/>            Lettura/scrittura **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/it/aspose.slides.export/svgoptions/metafile_rasterization_dpi/) | Restituisce o imposta il limite di risoluzione inferiore per la rasterizzazione dei metafile.<br/>            Lettura/scrittura **int**. |
| [`disable_3d_text`](/slides/python-net/it/aspose.slides.export/svgoptions/disable_3d_text/) | Determina se il testo 3D è disabilitato in SVG.<br/>            Lettura/scrittura **bool**. |
| [`disable_gradient_split`](/slides/python-net/it/aspose.slides.export/svgoptions/disable_gradient_split/) | Disabilita la divisione dei gradienti FromCornerX e FromCenter.<br/>            Lettura/scrittura **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/it/aspose.slides.export/svgoptions/disable_line_end_cropping/) | SVG 1.1 non offre la possibilità di definire rientri per i marker.<br/>            Il motore di scrittura SVG di Aspose.Slides ha una soluzione alternativa per questo problema:<br/>            taglia l'estremità della linea con freccia, così la linea non si sovrappone ai marker.<br/>            Questa opzione disattiva tale comportamento.<br/>            Lettura/scrittura **bool**. |
| [`default`](/slides/python-net/it/aspose.slides.export/svgoptions/default/) | Restituisce le impostazioni predefinite.<br/>            Sola lettura [`SVGOptions`](/slides/python-net/it/aspose.slides.export/svgoptions). |
| [`simple`](/slides/python-net/it/aspose.slides.export/svgoptions/simple/) | Restituisce le impostazioni per la generazione del file SVG più semplice e più piccolo.<br/>            Sola lettura [`SVGOptions`](/slides/python-net/it/aspose.slides.export/svgoptions). |
| [`wysiwyg`](/slides/python-net/it/aspose.slides.export/svgoptions/wysiwyg/) | Restituisce le impostazioni per la generazione del file SVG più accurata.<br/>            Sola lettura [`SVGOptions`](/slides/python-net/it/aspose.slides.export/svgoptions). |
| [`jpeg_quality`](/slides/python-net/it/aspose.slides.export/svgoptions/jpeg_quality/) | Determina la qualità di codifica JPEG.<br/>            Lettura/scrittura **int**. |
| [`shape_formatting_controller`](/slides/python-net/it/aspose.slides.export/svgoptions/shape_formatting_controller/) | Restituisce e imposta un'interfaccia di callback che consente all'utente di controllare la conversione delle forme.<br/>            Lettura/scrittura [`ISvgShapeFormattingController`](/slides/python-net/it/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/it/aspose.slides.export/svgoptions/pictures_compression/) | Rappresenta il livello di compressione delle immagini |
| [`delete_pictures_cropped_areas`](/slides/python-net/it/aspose.slides.export/svgoptions/delete_pictures_cropped_areas/) | Un flag booleano indica se le parti ritagliate rimangono come parte del documento. Se true le parti ritagliate <br/>            verranno rimosse, se false saranno serializzate nel documento (il che può eventualmente portare a un <br/>            file più grande) |
| [`external_fonts_handling`](/slides/python-net/it/aspose.slides.export/svgoptions/external_fonts_handling/) | Determina un modo di gestire i font caricati esternamente.<br/>            Lettura/scrittura [`SvgExternalFontsHandling`](/slides/python-net/it/aspose.slides.export/svgexternalfontshandling). |
| [`disable_font_ligatures`](/slides/python-net/it/aspose.slides.export/svgoptions/disable_font_ligatures/) | Ottiene o imposta un valore che indica se il testo è renderizzato senza usare le legature.<br/>            Quando impostato a `true`, le legature saranno disabilitate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata a `false`. |

### Vedi anche
* classe [`SaveOptions`](/slides/python-net/it/aspose.slides.export/saveoptions)
* classe [`SVGOptions`](/slides/python-net/it/aspose.slides.export/svgoptions)
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)