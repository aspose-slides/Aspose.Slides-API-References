---
title: PptxOptions class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.export/pptxoptions/
---
## PptxOptions classe

Rappresenta le opzioni per il salvataggio delle presentazioni OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).

**Eredità:**[`PptxOptions`](/slides/python-net/it/aspose.slides.export/pptxoptions) → [`SaveOptions`](/slides/python-net/it/aspose.slides.export/saveoptions)

Il tipo PptxOptions espone i seguenti membri:

## Costruttori

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/it/aspose.slides.export/pptxoptions/__init__/#) | Creates new instance of PptxOptions |

## Proprietà

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/it/aspose.slides.export/pptxoptions/warning_callback/) | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o verrà interrotto.<br/>            Lettura/scrittura [`IWarningCallback`](/slides/python-net/it/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/it/aspose.slides.export/pptxoptions/progress_callback/) | Rappresenta un oggetto callback per gli aggiornamenti di avanzamento del salvataggio in percentuale.<br/>            Vedi [`IProgressCallback`](/slides/python-net/it/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/it/aspose.slides.export/pptxoptions/default_regular_font/) | Restituisce o imposta il carattere usato nel caso il carattere sorgente non sia trovato.<br/>            Lettura-scrittura **str**. |
| [`gradient_style`](/slides/python-net/it/aspose.slides.export/pptxoptions/gradient_style/) | Restituisce o imposta lo stile visivo del gradiente.<br/>            Lettura/scrittura [`GradientStyle`](/slides/python-net/it/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/it/aspose.slides.export/pptxoptions/skip_java_script_links/) | Specifica se saltare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione. <br/>            Lettura/scrittura **bool**. Il valore predefinito è **false** . |
| [`conformance`](/slides/python-net/it/aspose.slides.export/pptxoptions/conformance/) | Specifica la classe di conformità a cui il documento Presentation è conforme.<br/>            Il valore predefinito è [`Conformance.ECMA_376_2006`](/slides/python-net/it/aspose.slides.export/conformance/ECMA_376_2006) |
| [`zip_64_mode`](/slides/python-net/it/aspose.slides.export/pptxoptions/zip_64_mode/) | Specifica se il formato ZIP64 è usato per il documento Presentation. <br/>            Il valore predefinito è [`Zip64Mode.IF_NECESSARY`](/slides/python-net/it/aspose.slides.export/zip64mode/IF_NECESSARY) |
| [`refresh_thumbnail`](/slides/python-net/it/aspose.slides.export/pptxoptions/refresh_thumbnail/) | Specifica se la miniatura della presentazione sarà aggiornata. <br/>            Lettura/scrittura **bool**.<br/>            Il valore predefinito è **true** . |
| [`compression_level`](/slides/python-net/it/aspose.slides.export/pptxoptions/compression_level/) | Specifica il livello di compressione usato durante il salvataggio del documento della presentazione.<br/>            Il valore predefinito è [`CompressionLevel.LEVEL6`](/slides/python-net/it/aspose.slides.export/compressionlevel/LEVEL6). |


### Vedi anche
* classe [`PptxOptions`](/slides/python-net/it/aspose.slides.export/pptxoptions)
* classe [`SaveOptions`](/slides/python-net/it/aspose.slides.export/saveoptions)
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)