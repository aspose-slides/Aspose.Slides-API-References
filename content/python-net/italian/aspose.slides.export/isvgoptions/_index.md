---
title: ISVGOptions class
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.export/isvgoptions/
---
## ISVGOptions classe

Rappresenta un'opzione SVG.

Il tipo ISVGOptions espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`vectorize_text`](/slides/python-net/it/aspose.slides.export/isvgoptions/vectorize_text/) | Determina se il testo su una diapositiva verrà salvato come grafica.<br/>            Lettura/scrittura **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/it/aspose.slides.export/isvgoptions/metafile_rasterization_dpi/) | Restituisce o imposta il limite di risoluzione inferiore per la rasterizzazione dei metafile.<br/>            Lettura/scrittura **int**. |
| [`disable_3d_text`](/slides/python-net/it/aspose.slides.export/isvgoptions/disable_3d_text/) | Determina se il testo 3D è disabilitato in SVG.<br/>            Lettura/scrittura **bool**. |
| [`disable_gradient_split`](/slides/python-net/it/aspose.slides.export/isvgoptions/disable_gradient_split/) | Disabilita la suddivisione dei gradienti FromCornerX e FromCenter.<br/>            Lettura/scrittura **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/it/aspose.slides.export/isvgoptions/disable_line_end_cropping/) | SVG 1.1 non consente di definire gli inserimenti per i marcatori.<br/>            Il motore di scrittura SVG di Aspose.Slides ha una soluzione per questo problema:<br/>            ritaglia l'estremità della linea con freccia, quindi la linea non si sovrappone ai marcatori.<br/>            Questa opzione disattiva tale comportamento.<br/>            Lettura/scrittura **bool**. |
| [`jpeg_quality`](/slides/python-net/it/aspose.slides.export/isvgoptions/jpeg_quality/) | Determina la qualità di codifica JPEG.<br/>            Lettura/scrittura **int**. |
| [`shape_formatting_controller`](/slides/python-net/it/aspose.slides.export/isvgoptions/shape_formatting_controller/) | Restituisce e imposta un'interfaccia di callback che consente all'utente di controllare la conversione delle forme.<br/>            Lettura/scrittura [`ISvgShapeFormattingController`](/slides/python-net/it/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/it/aspose.slides.export/isvgoptions/pictures_compression/) | Rappresenta il livello di compressione delle immagini<br/>            Lettura/scrittura [`ISVGOptions.pictures_compression`](/slides/python-net/it/aspose.slides.export/isvgoptions/pictures_compression). |
| [`delete_pictures_cropped_areas`](/slides/python-net/it/aspose.slides.export/isvgoptions/delete_pictures_cropped_areas/) | Un flag booleano indica se le parti ritagliate rimangono parte del documento. Se vero le parti ritagliate verranno rimosse, se falso saranno serializzate nel documento (il che può portare a un file più grande)<br/>            Lettura/scrittura **bool**. |
| [`use_frame_size`](/slides/python-net/it/aspose.slides.export/isvgoptions/use_frame_size/) | Determina se il riquadro di testo sarà incluso in un'area di rendering o meno.<br/>            Lettura/scrittura **bool**.<br/>            Il valore predefinito è false. |
| [`use_frame_rotation`](/slides/python-net/it/aspose.slides.export/isvgoptions/use_frame_rotation/) | Determina se eseguire la rotazione specificata della forma durante il rendering o meno.<br/>            Lettura/scrittura **bool**.<br/>            Il valore predefinito è true. |
| [`external_fonts_handling`](/slides/python-net/it/aspose.slides.export/isvgoptions/external_fonts_handling/) | Determina un metodo per gestire i font caricati esternamente.<br/>            Lettura/scrittura [`SvgExternalFontsHandling`](/slides/python-net/it/aspose.slides.export/svgexternalfontshandling). |
| [`ink_options`](/slides/python-net/it/aspose.slides.export/isvgoptions/ink_options/) | Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato.<br/>            Solo lettura [`IInkOptions`](/slides/python-net/it/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/it/aspose.slides.export/isvgoptions/disable_font_ligatures/) | Ottiene o imposta un valore che indica se il testo è renderizzato senza usare le legature.<br/>            Quando impostato a `true`, le legature saranno disabilitate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata su `false`. |
| [`warning_callback`](/slides/python-net/it/aspose.slides.export/isvgoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/it/aspose.slides.export/isvgoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/it/aspose.slides.export/isvgoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/it/aspose.slides.export/isvgoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/it/aspose.slides.export/isvgoptions/skip_java_script_links/) |  |

### Vedi anche
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)