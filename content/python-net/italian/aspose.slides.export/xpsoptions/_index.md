---
title: XpsOptions class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.export/xpsoptions/
---
## XpsOptions classe

Fornisce opzioni che controllano come una presentazione viene salvata in formato Xps.

**Eredità:**[`XpsOptions`](/slides/python-net/it/aspose.slides.export/xpsoptions) → [`SaveOptions`](/slides/python-net/it/aspose.slides.export/saveoptions)

Il tipo XpsOptions espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self)`](/slides/python-net/it/aspose.slides.export/xpsoptions/__init__/#) | Costruttore predefinito. |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`warning_callback`](/slides/python-net/it/aspose.slides.export/xpsoptions/warning_callback/) | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o sarà interrotto.<br/>            Lettura/scrittura [`IWarningCallback`](/slides/python-net/it/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/it/aspose.slides.export/xpsoptions/progress_callback/) | Rappresenta un oggetto di callback per gli aggiornamenti di avanzamento del salvataggio in percentuale.<br/>            Vedi [`IProgressCallback`](/slides/python-net/it/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/it/aspose.slides.export/xpsoptions/default_regular_font/) | Restituisce o imposta il font utilizzato nel caso il font di origine non sia trovato.<br/>            Lettura-scrittura **str**. |
| [`gradient_style`](/slides/python-net/it/aspose.slides.export/xpsoptions/gradient_style/) | Restituisce o imposta lo stile visivo del gradiente.<br/>            Lettura/scrittura [`GradientStyle`](/slides/python-net/it/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/it/aspose.slides.export/xpsoptions/skip_java_script_links/) | Specifica se saltare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione.<br/>            Lettura/scrittura **bool**. Il valore predefinito è **false** . |
| [`show_hidden_slides`](/slides/python-net/it/aspose.slides.export/xpsoptions/show_hidden_slides/) | Specifica se il documento generato deve includere le diapositive nascoste o meno.<br/>            Il valore predefinito è `false`. |
| [`save_metafiles_as_png`](/slides/python-net/it/aspose.slides.export/xpsoptions/save_metafiles_as_png/) | True per convertire tutti i metafile usati in una presentazione in immagini PNG.<br/>            Lettura/scrittura **bool**. |
| [`draw_slides_frame`](/slides/python-net/it/aspose.slides.export/xpsoptions/draw_slides_frame/) | True per disegnare una cornice nera attorno a ogni diapositiva.<br/>             Lettura/scrittura **bool**. |

### Vedi anche
* classe [`SaveOptions`](/slides/python-net/it/aspose.slides.export/saveoptions)
* classe [`XpsOptions`](/slides/python-net/it/aspose.slides.export/xpsoptions)
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)