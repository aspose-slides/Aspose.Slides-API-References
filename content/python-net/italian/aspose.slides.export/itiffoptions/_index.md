---
title: ITiffOptions class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.export/itiffoptions/
---
## ITiffOptions classe

Fornisce opzioni che controllano come una presentazione viene salvata nel formato TIFF.

Il tipo ITiffOptions espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`image_size`](/slides/python-net/it/aspose.slides.export/itiffoptions/image_size/) | Specifica la dimensione di un'immagine TIFF generata.<br/>            Il valore predefinito è 0x0, il che significa che le dimensioni dell'immagine generata saranno calcolate in base al valore della dimensione della diapositiva della presentazione.<br/>            Lettura/scrittura **aspose.slides.Size**. |
| [`dpi_x`](/slides/python-net/it/aspose.slides.export/itiffoptions/dpi_x/) | Specifica la risoluzione orizzontale in punti per pollice.<br/>            Lettura/scrittura **int**. |
| [`dpi_y`](/slides/python-net/it/aspose.slides.export/itiffoptions/dpi_y/) | Specifica la risoluzione verticale in punti per pollice.<br/>            Lettura/scrittura **int**. |
| [`show_hidden_slides`](/slides/python-net/it/aspose.slides.export/itiffoptions/show_hidden_slides/) | Specifica se il documento generato debba includere diapositive nascoste o meno.<br/>            Il valore predefinito è `false`. |
| [`compression_type`](/slides/python-net/it/aspose.slides.export/itiffoptions/compression_type/) | Specifica il tipo di compressione.<br/>            Lettura/scrittura [`TiffCompressionTypes`](/slides/python-net/it/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/it/aspose.slides.export/itiffoptions/pixel_format/) | Specifica il formato pixel per le immagini generate.<br/>            Lettura/scrittura [`ImagePixelFormat`](/slides/python-net/it/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/it/aspose.slides.export/itiffoptions/slides_layout_options/) | Ottiene o imposta la modalità in cui le diapositive vengono posizionate sulla pagina durante l'esportazione di una presentazione [`ISlidesLayoutOptions`](/slides/python-net/it/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/it/aspose.slides.export/itiffoptions/bw_conversion_mode/) | Specifica l'algoritmo per convertire un'immagine a colori in un'immagine in bianco e nero.<br/>            Questa opzione verrà applicata solo se [`ITiffOptions.compression_type`](/slides/python-net/it/aspose.slides.export/itiffoptions/compression_type) <br/>            è impostato su [`TiffCompressionTypes.CCITT4`](/slides/python-net/it/aspose.slides.export/tiffcompressiontypes/CCITT4) o [`TiffCompressionTypes.CCITT3`](/slides/python-net/it/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            Lettura/scrittura [`BlackWhiteConversionMode`](/slides/python-net/it/aspose.slides.export/blackwhiteconversionmode).<br/>            Il valore predefinito è [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/it/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |
| [`ink_options`](/slides/python-net/it/aspose.slides.export/itiffoptions/ink_options/) | Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato.<br/>            Solo lettura [`IInkOptions`](/slides/python-net/it/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/it/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/it/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/it/aspose.slides.export/itiffoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/it/aspose.slides.export/itiffoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/it/aspose.slides.export/itiffoptions/skip_java_script_links/) |  |

### Vedi anche
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)