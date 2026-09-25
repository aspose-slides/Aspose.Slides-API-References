---
title: TiffOptions class
second_title: Aspose.Slides per Python tramite .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.export/tiffoptions/
---
## TiffOptions classe

Fornisce opzioni che controllano come una presentazione viene salvata nel formato TIFF.

**Inheritance:**[`TiffOptions`](/slides/python-net/it/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/it/aspose.slides.export/saveoptions)

Il tipo TiffOptions espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self)`](/slides/python-net/it/aspose.slides.export/tiffoptions/__init__/#) | Costruttore predefinito. |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`warning_callback`](/slides/python-net/it/aspose.slides.export/tiffoptions/warning_callback/) | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o verrà interrotto.<br/>            Lettura/scrittura [`IWarningCallback`](/slides/python-net/it/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/it/aspose.slides.export/tiffoptions/progress_callback/) | Rappresenta un oggetto di callback per il salvataggio degli aggiornamenti di avanzamento in percentuale.<br/>            Vedi [`IProgressCallback`](/slides/python-net/it/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/it/aspose.slides.export/tiffoptions/default_regular_font/) | Restituisce o imposta il carattere usato nel caso il carattere sorgente non venga trovato.<br/>            Lettura-scrittura **str**. |
| [`gradient_style`](/slides/python-net/it/aspose.slides.export/tiffoptions/gradient_style/) | Restituisce o imposta lo stile visivo del gradiente.<br/>            Lettura/scrittura [`GradientStyle`](/slides/python-net/it/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/it/aspose.slides.export/tiffoptions/skip_java_script_links/) | Specifica se saltare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione.<br/>            Lettura/scrittura **bool**. Il valore predefinito è **false**. |
| [`ink_options`](/slides/python-net/it/aspose.slides.export/tiffoptions/ink_options/) | Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato.<br/>            Solo lettura [`IInkOptions`](/slides/python-net/it/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/it/aspose.slides.export/tiffoptions/show_hidden_slides/) | Specifica se il documento generato dovrebbe includere diapositive nascoste o meno.<br/>            Il valore predefinito è `false`. |
| [`image_size`](/slides/python-net/it/aspose.slides.export/tiffoptions/image_size/) | Specifica le dimensioni di un'immagine TIFF generata.<br/>            Il valore predefinito è 0x0, il che significa che le dimensioni dell'immagine generata saranno calcolate in base al valore della dimensione della diapositiva della presentazione.<br/>            Lettura/scrittura [`Size`](/slides/python-net/it/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/it/aspose.slides.export/tiffoptions/dpi_x/) | Specifica la risoluzione orizzontale in punti per pollice.<br/>            Lettura/scrittura **int**. |
| [`dpi_y`](/slides/python-net/it/aspose.slides.export/tiffoptions/dpi_y/) | Specifica la risoluzione verticale in punti per pollice.<br/>            Lettura/scrittura **int**. |
| [`compression_type`](/slides/python-net/it/aspose.slides.export/tiffoptions/compression_type/) | Specifica il tipo di compressione.<br/>            Lettura/scrittura [`TiffCompressionTypes`](/slides/python-net/it/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/it/aspose.slides.export/tiffoptions/pixel_format/) | Specifica il formato pixel per le immagini generate.<br/>            Lettura/scrittura [`ImagePixelFormat`](/slides/python-net/it/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/it/aspose.slides.export/tiffoptions/slides_layout_options/) | Ottiene o imposta la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [`ISlidesLayoutOptions`](/slides/python-net/it/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/it/aspose.slides.export/tiffoptions/bw_conversion_mode/) | Specifica l'algoritmo per la conversione di un'immagine a colori in un'immagine in bianco e nero.<br/>            Questa opzione verrà applicata solo se [`TiffOptions.compression_type`](/slides/python-net/it/aspose.slides.export/tiffoptions/compression_type) <br/>            è impostato su [`TiffCompressionTypes.CCITT4`](/slides/python-net/it/aspose.slides.export/tiffcompressiontypes/CCITT4) o [`TiffCompressionTypes.CCITT3`](/slides/python-net/it/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            Lettura/scrittura [`BlackWhiteConversionMode`](/slides/python-net/it/aspose.slides.export/blackwhiteconversionmode).<br/>            Il valore predefinito è [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/it/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |

### Vedi anche
* classe [`SaveOptions`](/slides/python-net/it/aspose.slides.export/saveoptions)
* classe [`TiffOptions`](/slides/python-net/it/aspose.slides.export/tiffoptions)
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)