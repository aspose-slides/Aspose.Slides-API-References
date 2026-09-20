---
title: IPdfOptions class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.export/ipdfoptions/
---
## IPdfOptions classe

Fornisce opzioni che controllano come una presentazione viene salvata in formato Pdf.

Il tipo IPdfOptions espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`text_compression`](/slides/python-net/it/aspose.slides.export/ipdfoptions/text_compression/) | Specifica il tipo di compressione da utilizzare per tutto il contenuto testuale nel documento.<br/>            Lettura/scrittura [`PdfTextCompression`](/slides/python-net/it/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/it/aspose.slides.export/ipdfoptions/best_images_compression_ratio/) | Indica se la compressione più efficace (invece di quella predefinita) per ogni immagine deve essere selezionata <br/>            automaticamente. Se impostata su **bool**.true, per ogni immagine nella presentazione verrà scelto l'algoritmo di compressione più appropriato, il che porterà a una dimensione più piccola del documento PDF risultante. <br/>            La selezione del miglior rapporto di compressione dell'immagine è computazionalmente costosa e richiede <br/>            una quantità aggiuntiva di RAM, e questa opzione è **bool**.false per impostazione predefinita. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/it/aspose.slides.export/ipdfoptions/embed_true_type_fonts_for_ascii/) | True per incorporare i font TrueType per i caratteri ASCII 32-127.<br/>            I font per i codici di carattere maggiori di 127 sono sempre incorporati.<br/>            Lettura/scrittura **bool**. |
| [`show_hidden_slides`](/slides/python-net/it/aspose.slides.export/ipdfoptions/show_hidden_slides/) | Specifica se il documento generato deve includere diapositive nascoste o meno.<br/>            L'impostazione predefinita è `false`. |
| [`additional_common_font_families`](/slides/python-net/it/aspose.slides.export/ipdfoptions/additional_common_font_families/) | Restituisce o imposta un array di nomi di famiglie di font definiti dall'utente che Aspose.Slides dovrebbe considerare comuni.<br/>            Lettura/scrittura **str**[]. |
| [`embed_full_fonts`](/slides/python-net/it/aspose.slides.export/ipdfoptions/embed_full_fonts/) | Determina se tutti i caratteri del font devono essere incorporati o solo il sottoinsieme utilizzato.<br/>            Lettura/scrittura **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/it/aspose.slides.export/ipdfoptions/rasterize_unsupported_font_styles/) | Indica se il testo deve essere rasterizzato come bitmap e salvato in PDF quando il font non supporta lo stile grassetto.<br/>            Questo approccio può migliorare la qualità del testo nel PDF risultante per alcuni font.<br/>            Lettura/scrittura **bool**. |
| [`jpeg_quality`](/slides/python-net/it/aspose.slides.export/ipdfoptions/jpeg_quality/) | Restituisce o imposta un valore che determina la qualità delle immagini JPEG nel documento PDF.<br/>            Lettura/scrittura **int**. |
| [`compliance`](/slides/python-net/it/aspose.slides.export/ipdfoptions/compliance/) | Livello di conformità desiderato per il documento PDF generato.<br/>            Lettura/scrittura [`PdfCompliance`](/slides/python-net/it/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/it/aspose.slides.export/ipdfoptions/password/) | Impostazione della password utente per proteggere il documento PDF. <br/>            Lettura/scrittura **str**. |
| [`access_permissions`](/slides/python-net/it/aspose.slides.export/ipdfoptions/access_permissions/) | Contiene un insieme di flag che specificano quali permessi di accesso devono essere concessi quando il documento è aperto<br/>            con accesso utente. Vedi [`PdfAccessPermissions`](/slides/python-net/it/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/it/aspose.slides.export/ipdfoptions/save_metafiles_as_png/) | True per convertire tutti i metafili usati in una presentazione in immagini PNG.<br/>            Lettura/scrittura **bool**. |
| [`sufficient_resolution`](/slides/python-net/it/aspose.slides.export/ipdfoptions/sufficient_resolution/) | Restituisce o imposta un valore che determina la risoluzione delle immagini nel documento PDF.<br/>            <br/>La proprietà influisce sulla dimensione del file, sul tempo di esportazione e sulla qualità dell'immagine.<br/><br/><br/>Il valore predefinito è **96** .<br/><br/><br/>            Lettura/scrittura **float**. |
| [`draw_slides_frame`](/slides/python-net/it/aspose.slides.export/ipdfoptions/draw_slides_frame/) | True per disegnare una cornice nera attorno a ogni diapositiva.<br/>             Lettura/scrittura **bool**. |
| [`slides_layout_options`](/slides/python-net/it/aspose.slides.export/ipdfoptions/slides_layout_options/) | Ottiene o imposta la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [`ISlidesLayoutOptions`](/slides/python-net/it/aspose.slides.export/islideslayoutoptions). |
| [`image_transparent_color`](/slides/python-net/it/aspose.slides.export/ipdfoptions/image_transparent_color/) | Ottiene o imposta il colore trasparente dell'immagine. |
| [`apply_image_transparent`](/slides/python-net/it/aspose.slides.export/ipdfoptions/apply_image_transparent/) | Applica il colore trasparente specificato a un'immagine se `true`. |
| [`ink_options`](/slides/python-net/it/aspose.slides.export/ipdfoptions/ink_options/) | Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato.<br/>            Sola lettura [`IInkOptions`](/slides/python-net/it/aspose.slides.export/iinkoptions) |
| [`include_ole_data`](/slides/python-net/it/aspose.slides.export/ipdfoptions/include_ole_data/) | True per convertire tutti i dati OLE dalla presentazione in file incorporati nel PDF risultante.<br/>            Lettura/scrittura **bool**. |
| [`warning_callback`](/slides/python-net/it/aspose.slides.export/ipdfoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/it/aspose.slides.export/ipdfoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/it/aspose.slides.export/ipdfoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/it/aspose.slides.export/ipdfoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/it/aspose.slides.export/ipdfoptions/skip_java_script_links/) |  |

### Vedi anche
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)