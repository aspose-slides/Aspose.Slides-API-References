---
title: SaveOptions class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.export/saveoptions/
---
## Classe SaveOptions

Classe astratta con opzioni che controllano come una presentazione viene salvata.

Il tipo SaveOptions espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`warning_callback`](/slides/python-net/it/aspose.slides.export/saveoptions/warning_callback/) | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o sarà interrotto.<br/>            Lettura/scrittura [`IWarningCallback`](/slides/python-net/it/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/it/aspose.slides.export/saveoptions/progress_callback/) | Rappresenta un oggetto di callback per gli aggiornamenti di avanzamento del salvataggio in percentuale.<br/>            Vedi [`IProgressCallback`](/slides/python-net/it/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/it/aspose.slides.export/saveoptions/default_regular_font/) | Restituisce o imposta il carattere usato nel caso in cui il carattere sorgente non sia trovato.<br/>            Lettura-scrittura **str**. |
| [`gradient_style`](/slides/python-net/it/aspose.slides.export/saveoptions/gradient_style/) | Restituisce o imposta lo stile visivo del gradiente.<br/>            Lettura/scrittura [`GradientStyle`](/slides/python-net/it/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/it/aspose.slides.export/saveoptions/skip_java_script_links/) | Specifica se saltare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione. <br/>            Lettura/scrittura **bool**. Il valore predefinito è **false** . |

### Vedi anche
* module [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)