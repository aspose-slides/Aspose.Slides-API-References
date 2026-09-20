---
title: RenderingOptions class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.export/renderingoptions/
---
## RenderingOptions classe

Fornisce opzioni che controllano come viene renderizzata una presentazione/diapositiva.

**Ereditarietà:**[`RenderingOptions`](/slides/python-net/it/aspose.slides.export/renderingoptions) → [`SaveOptions`](/slides/python-net/it/aspose.slides.export/saveoptions)

Il tipo RenderingOptions espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self)`](/slides/python-net/it/aspose.slides.export/renderingoptions/__init__/#) | Costruttore predefinito. |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`warning_callback`](/slides/python-net/it/aspose.slides.export/renderingoptions/warning_callback/) | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o verrà annullato.<br/> Lettura/scrittura [`IWarningCallback`](/slides/python-net/it/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/it/aspose.slides.export/renderingoptions/progress_callback/) | Rappresenta un oggetto di callback per il salvataggio degli aggiornamenti di avanzamento in percentuale.<br/> Vedi [`IProgressCallback`](/slides/python-net/it/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/it/aspose.slides.export/renderingoptions/default_regular_font/) | Restituisce o imposta il font usato nel caso in cui il font di origine non sia trovato.<br/> Lettura-scrittura **str**. |
| [`gradient_style`](/slides/python-net/it/aspose.slides.export/renderingoptions/gradient_style/) | Restituisce o imposta lo stile visivo del gradiente.<br/> Lettura/scrittura [`GradientStyle`](/slides/python-net/it/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/it/aspose.slides.export/renderingoptions/skip_java_script_links/) | Specifica se saltare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione.<br/> Lettura/scrittura **bool**. Il valore predefinito è **false**. |
| [`slides_layout_options`](/slides/python-net/it/aspose.slides.export/renderingoptions/slides_layout_options/) | Ottiene o imposta la modalità in cui le diapositive sono collocate nella pagina durante l'esportazione di una presentazione [`ISlidesLayoutOptions`](/slides/python-net/it/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/it/aspose.slides.export/renderingoptions/ink_options/) | Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato.<br/> Solo lettura [`IInkOptions`](/slides/python-net/it/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/it/aspose.slides.export/renderingoptions/disable_font_ligatures/) | Ottiene o imposta un valore che indica se il testo è renderizzato senza utilizzare le legature.<br/> Quando impostato su `true`, le legature saranno disabilitate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata su `false`. |


### Vedi anche
* classe [`RenderingOptions`](/slides/python-net/it/aspose.slides.export/renderingoptions)
* classe [`SaveOptions`](/slides/python-net/it/aspose.slides.export/saveoptions)
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)