---
title: PdfOptions class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.export/pdfoptions/
---
## PdfOptions classe

Fornisce opzioni che controllano come una presentazione viene salvata in formato Pdf.

**Eredità:**[`PdfOptions`](/slides/python-net/it/aspose.slides.export/pdfoptions) → [`SaveOptions`](/slides/python-net/it/aspose.slides.export/saveoptions)

Il tipo PdfOptions espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self)`](/slides/python-net/it/aspose.slides.export/pdfoptions/__init__/#) | Costruttore predefinito. |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`warning_callback`](/slides/python-net/it/aspose.slides.export/pdfoptions/warning_callback/) | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o verrà interrotto.<br/>            Lettura/scrittura [`IWarningCallback`](/slides/python-net/it/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/it/aspose.slides.export/pdfoptions/progress_callback/) | Rappresenta un oggetto di callback per gli aggiornamenti di avanzamento del salvataggio in percentuale.<br/>            Vedi [`IProgressCallback`](/slides/python-net/it/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/it/aspose.slides.export/pdfoptions/default_regular_font/) | Restituisce o imposta il carattere usato nel caso il carattere sorgente non sia trovato.<br/>            Lettura-scrittura **str**. |
| [`gradient_style`](/slides/python-net/it/aspose.slides.export/pdfoptions/gradient_style/) | Restituisce o imposta lo stile visivo del gradiente.<br/>            Lettura/scrittura [`GradientStyle`](/slides/python-net/it/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/it/aspose.slides.export/pdfoptions/skip_java_script_links/) | Specifica se saltare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione. <br/>            Lettura/scrittura **bool**. Il valore predefinito è **false**. |
| [`slides_layout_options`](/slides/python-net/it/aspose.slides.export/pdfoptions/slides_layout_options/) | Ottiene o imposta la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [`ISlidesLayoutOptions`](/slides/python-net/it/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/it/aspose.slides.export/pdfoptions/ink_options/) | Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato.<br/>            Sola lettura [`IInkOptions`](/slides/python-net/it/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/it/aspose.slides.export/pdfoptions/show_hidden_slides/) | Specifica se il documento generato deve includere diapositive nascoste o meno.<br/>            Il valore predefinito è `false`. |
| [`text_compression`](/slides/python-net/it/aspose.slides.export/pdfoptions/text_compression/) | Specifica il tipo di compressione da utilizzare per tutti i contenuti testuali nel documento.<br/>            Lettura/scrittura [`PdfTextCompression`](/slides/python-net/it/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/it/aspose.slides.export/pdfoptions/best_images_compression_ratio/) | Indica se la compressione più efficace (invece di quella predefinita) per ogni immagine deve essere selezionata <br/>            automaticamente. Se impostata su **bool**.true, per ogni immagine nella presentazione verrà scelto l'algoritmo di compressione più appropriato, il che porterà a una dimensione più piccola del documento PDF risultante. <br/>            La selezione del miglior rapporto di compressione delle immagini è computazionalmente costosa e richiede <br/>            una quantità aggiuntiva di RAM, e questa opzione è **bool**.false per impostazione predefinita. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/it/aspose.slides.export/pdfoptions/embed_true_type_fonts_for_ascii/) | Determina se Aspose.Slides incorporerà i caratteri comuni per il testo ASCII (intervallo di codice 33..127).<br/>            I caratteri per codici superiori a 127 sono sempre incorporati.<br/>            L'elenco dei caratteri comuni include i 14 caratteri di base del PDF e caratteri aggiuntivi specificati dall'utente.<br/>            Lettura/scrittura **bool**. |
| [`additional_common_font_families`](/slides/python-net/it/aspose.slides.export/pdfoptions/additional_common_font_families/) | Restituisce o imposta un array di nomi di famiglie di caratteri definiti dall'utente che Aspose.Slides dovrebbe considerare comuni.<br/>            Lettura/scrittura **str**[]. |
| [`embed_full_fonts`](/slides/python-net/it/aspose.slides.export/pdfoptions/embed_full_fonts/) | Determina se tutti i caratteri del carattere devono essere incorporati o solo il sottoinsieme utilizzato.<br/>            Lettura/scrittura **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/it/aspose.slides.export/pdfoptions/rasterize_unsupported_font_styles/) | Indica se il testo dovrebbe essere rasterizzato come bitmap e salvato in PDF quando il carattere non supporta lo stile grassetto.<br/>            Questo approccio può migliorare la qualità del testo nel PDF risultante per alcuni caratteri.<br/>            Lettura/scrittura **bool**. |
| [`jpeg_quality`](/slides/python-net/it/aspose.slides.export/pdfoptions/jpeg_quality/) | Restituisce o imposta un valore che determina la qualità delle immagini JPEG nel documento PDF.<br/>            Lettura/scrittura **int**. |
| [`compliance`](/slides/python-net/it/aspose.slides.export/pdfoptions/compliance/) | Livello di conformità desiderato per il documento PDF generato.<br/>            Lettura/scrittura [`PdfCompliance`](/slides/python-net/it/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/it/aspose.slides.export/pdfoptions/password/) | Impostazione della password utente per proteggere il documento PDF. <br/>            Lettura/scrittura **str**. |
| [`access_permissions`](/slides/python-net/it/aspose.slides.export/pdfoptions/access_permissions/) | Contiene un insieme di flag che specificano quali permessi di accesso devono essere concessi quando il documento è aperto<br/>            con accesso utente. Vedi [`PdfAccessPermissions`](/slides/python-net/it/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/it/aspose.slides.export/pdfoptions/save_metafiles_as_png/) | Vero per convertire tutti i metafili utilizzati in una presentazione in immagini PNG.<br/>            Lettura/scrittura **bool**. |
| [`sufficient_resolution`](/slides/python-net/it/aspose.slides.export/pdfoptions/sufficient_resolution/) | Restituisce o imposta un valore che determina la risoluzione delle immagini nel documento PDF.<br/>            <br/>La proprietà influisce sulla dimensione del file, sul tempo di esportazione e sulla qualità dell'immagine.<br/><br/><br/>Il valore predefinito è **96** .<br/><br/><br/>            Lettura/scrittura **float**. |
| [`draw_slides_frame`](/slides/python-net/it/aspose.slides.export/pdfoptions/draw_slides_frame/) | Vero per disegnare una cornice nera attorno a ogni diapositiva.<br/>             Lettura/scrittura **bool**. |
| [`image_transparent_color`](/slides/python-net/it/aspose.slides.export/pdfoptions/image_transparent_color/) | Ottiene o imposta il colore trasparente dell'immagine. |
| [`apply_image_transparent`](/slides/python-net/it/aspose.slides.export/pdfoptions/apply_image_transparent/) | Applica il colore trasparente specificato a un'immagine se `true`. |
| [`include_ole_data`](/slides/python-net/it/aspose.slides.export/pdfoptions/include_ole_data/) | Vero per convertire tutti i dati OLE dalla presentazione in file incorporati nel PDF risultante.<br/>            Lettura/scrittura **bool**. |


### Vedi anche
* classe [`PdfOptions`](/slides/python-net/it/aspose.slides.export/pdfoptions)
* classe [`SaveOptions`](/slides/python-net/it/aspose.slides.export/saveoptions)
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)