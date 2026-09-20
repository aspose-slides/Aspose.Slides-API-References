---
title: PptOptions class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.export/pptoptions/
---
## PptOptions classe

Fornisce opzioni che controllano come una presentazione viene salvata in formato PPT.

**Eredita da:**[`PptOptions`](/slides/python-net/it/aspose.slides.export/pptoptions) → [`SaveOptions`](/slides/python-net/it/aspose.slides.export/saveoptions)

Il tipo PptOptions espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self)`](/slides/python-net/it/aspose.slides.export/pptoptions/__init__/#) |  |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`warning_callback`](/slides/python-net/it/aspose.slides.export/pptoptions/warning_callback/) | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o verrà interrotto.<br/>            Lettura/scrittura [`IWarningCallback`](/slides/python-net/it/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/it/aspose.slides.export/pptoptions/progress_callback/) | Rappresenta un oggetto di callback per gli aggiornamenti di avanzamento del salvataggio in percentuale.<br/>            Vedi [`IProgressCallback`](/slides/python-net/it/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/it/aspose.slides.export/pptoptions/default_regular_font/) | Restituisce o imposta il carattere usato nel caso il carattere sorgente non sia trovato.<br/>            Lettura/scrittura **str**. |
| [`gradient_style`](/slides/python-net/it/aspose.slides.export/pptoptions/gradient_style/) | Restituisce o imposta lo stile visivo del gradiente.<br/>            Lettura/scrittura [`GradientStyle`](/slides/python-net/it/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/it/aspose.slides.export/pptoptions/skip_java_script_links/) | Specificare se saltare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione.<br/>            Lettura/scrittura **bool**. Il valore predefinito è **false**. |
| [`root_directory_clsid`](/slides/python-net/it/aspose.slides.export/pptoptions/root_directory_clsid/) | Rappresenta il GUID della classe oggetto (CLSID) che è memorizzato nella voce della directory radice. Può essere usato per l'attivazione COM dell'applicazione del documento.<br/>            Il valore predefinito è '64818D11-4F9B-11CF-86EA-00AA00B929E8' che corrisponde a 'Microsoft Powerpoint.Slide.8'. |

### Vedi anche
* classe [`PptOptions`](/slides/python-net/it/aspose.slides.export/pptoptions)
* classe [`SaveOptions`](/slides/python-net/it/aspose.slides.export/saveoptions)
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)