---
title: MarkdownSaveOptions class
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions classe

Rappresenta le opzioni che controllano come la presentazione deve essere salvata in markdown.

**Eredità:**[`MarkdownSaveOptions`](/slides/python-net/it/aspose.slides.export/markdownsaveoptions) → [`SaveOptions`](/slides/python-net/it/aspose.slides.export/saveoptions)

Il tipo MarkdownSaveOptions espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self)`](/slides/python-net/it/aspose.slides.export/markdownsaveoptions/__init__/#) | Costruttore. |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`warning_callback`](/slides/python-net/it/aspose.slides.export/markdownsaveoptions/warning_callback/) | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o verrà interrotto.<br/>            Lettura/Scrittura [`IWarningCallback`](/slides/python-net/it/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/it/aspose.slides.export/markdownsaveoptions/progress_callback/) | Rappresenta un oggetto di callback per gli aggiornamenti di avanzamento del salvataggio in percentuale.<br/>            Vedi [`IProgressCallback`](/slides/python-net/it/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/it/aspose.slides.export/markdownsaveoptions/default_regular_font/) | Restituisce o imposta il font usato nel caso in cui il font sorgente non sia trovato.<br/>            Lettura-scrittura **str**. |
| [`gradient_style`](/slides/python-net/it/aspose.slides.export/markdownsaveoptions/gradient_style/) | Restituisce o imposta lo stile visivo del gradiente.<br/>            Lettura/Scrittura [`GradientStyle`](/slides/python-net/it/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/it/aspose.slides.export/markdownsaveoptions/skip_java_script_links/) | Specifica se ignorare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione.<br/>            Lettura/Scrittura **bool**. Il valore predefinito è **false**. |
| [`export_type`](/slides/python-net/it/aspose.slides.export/markdownsaveoptions/export_type/) | Specifica la specifica markdown per convertire la presentazione.<br/>            Il valore predefinito è `TextOnly`. |
| [`base_path`](/slides/python-net/it/aspose.slides.export/markdownsaveoptions/base_path/) | Specifica il percorso base dove verrà salvato il documento con le risorse.<br/>            Il valore predefinito è la directory corrente dell'applicazione. |
| [`images_save_folder_name`](/slides/python-net/it/aspose.slides.export/markdownsaveoptions/images_save_folder_name/) | Specifica il nome della cartella in cui salvare le immagini.<br/>            Il valore predefinito è `Images`. |
| [`new_line_type`](/slides/python-net/it/aspose.slides.export/markdownsaveoptions/new_line_type/) | Specifica se il documento generato deve avere nuove linee \\r(Macintosh), \\n(Unix) o \\r\\n(Windows).<br/>            Il valore predefinito è `Unix`. |
| [`show_comments`](/slides/python-net/it/aspose.slides.export/markdownsaveoptions/show_comments/) | Specifica se il documento generato deve mostrare i commenti o meno.<br/>            Il valore predefinito è `false`. |
| [`show_hidden_slides`](/slides/python-net/it/aspose.slides.export/markdownsaveoptions/show_hidden_slides/) | Specifica se il documento generato deve includere le diapositive nascoste o meno.<br/>            Il valore predefinito è `false`. |
| [`show_slide_number`](/slides/python-net/it/aspose.slides.export/markdownsaveoptions/show_slide_number/) | Specifica se il documento generato deve mostrare il numero di ciascuna diapositiva o meno.<br/>            Il valore predefinito è `false`. |
| [`flavor`](/slides/python-net/it/aspose.slides.export/markdownsaveoptions/flavor/) | Specifica la specifica markdown per convertire la presentazione.<br/>            Il valore predefinito è `Multi-markdown`. |
| [`slide_number_format`](/slides/python-net/it/aspose.slides.export/markdownsaveoptions/slide_number_format/) | Ottiene o imposta la stringa di formato usata per le intestazioni del numero di diapositiva nell'output Markdown.<br/>            Il formato deve includere il segnaposto \"{0}\", che verrà sostituito con l'indice della diapositiva durante l'esportazione.<br/>            Esempio: \"# Slide {0}\" produce \"# Slide 1\", \"# Slide 2\", ecc. |
| [`handle_repeated_spaces`](/slides/python-net/it/aspose.slides.export/markdownsaveoptions/handle_repeated_spaces/) |  |
| [`remove_empty_lines`](/slides/python-net/it/aspose.slides.export/markdownsaveoptions/remove_empty_lines/) | Se impostato su `true`, rimuove le righe vuote o composte solo da spazi bianchi dall'output Markdown finale.<br/>            Il valore predefinito è `false`. |

### Vedi anche
* classe [`MarkdownSaveOptions`](/slides/python-net/it/aspose.slides.export/markdownsaveoptions)
* classe [`SaveOptions`](/slides/python-net/it/aspose.slides.export/saveoptions)
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)