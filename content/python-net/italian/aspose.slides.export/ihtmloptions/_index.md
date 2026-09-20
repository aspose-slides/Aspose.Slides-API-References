---
title: IHtmlOptions class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.export/ihtmloptions/
---
## IHtmlOptions classe

Rappresenta le opzioni di esportazione HTML.

Il tipo IHtmlOptions espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`html_formatter`](/slides/python-net/it/aspose.slides.export/ihtmloptions/html_formatter/) | Restituisce o imposta il modello HTML.<br/>            Lettura/scrittura [`IHtmlFormatter`](/slides/python-net/it/aspose.slides.export/ihtmlformatter). |
| [`slide_image_format`](/slides/python-net/it/aspose.slides.export/ihtmloptions/slide_image_format/) | Restituisce o imposta le opzioni del formato immagine delle diapositive.<br/>            Lettura/scrittura [`ISlideImageFormat`](/slides/python-net/it/aspose.slides.export/islideimageformat). |
| [`show_hidden_slides`](/slides/python-net/it/aspose.slides.export/ihtmloptions/show_hidden_slides/) | Specifica se il documento generato deve includere diapositive nascoste o no.<br/>            Il valore predefinito è `false`. |
| [`jpeg_quality`](/slides/python-net/it/aspose.slides.export/ihtmloptions/jpeg_quality/) | Restituisce o imposta un valore che determina la qualità delle immagini JPEG all'interno del documento PDF.<br/>            Lettura/scrittura **int**. |
| [`pictures_compression`](/slides/python-net/it/aspose.slides.export/ihtmloptions/pictures_compression/) | Rappresenta il livello di compressione delle immagini<br/>            Lettura/scrittura [`IHtmlOptions.pictures_compression`](/slides/python-net/it/aspose.slides.export/ihtmloptions/pictures_compression). |
| [`delete_pictures_cropped_areas`](/slides/python-net/it/aspose.slides.export/ihtmloptions/delete_pictures_cropped_areas/) | Un flag booleano indica se le parti ritagliate rimangono come parte del documento. Se true le parti ritagliate saranno rimosse, se false saranno serializzate nel documento (il che può eventualmente portare a un <br/>            file più grande)<br/>            Lettura/scrittura **bool**. |
| [`svg_responsive_layout`](/slides/python-net/it/aspose.slides.export/ihtmloptions/svg_responsive_layout/) | True per escludere gli attributi width e height dal contenitore SVG - ciò renderà il layout responsivo. False altrimenti.<br/>            Lettura/scrittura **bool**. |
| [`disable_font_ligatures`](/slides/python-net/it/aspose.slides.export/ihtmloptions/disable_font_ligatures/) | Restituisce o imposta un valore che indica se il testo è renderizzato senza usare le legature.<br/>            Quando impostato su `true`, le legature saranno disabilitate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata su `false`. |
| [`slides_layout_options`](/slides/python-net/it/aspose.slides.export/ihtmloptions/slides_layout_options/) | Restituisce o imposta la modalità in cui le diapositive sono posizionate nella pagina durante l'esportazione di una presentazione [`ISlidesLayoutOptions`](/slides/python-net/it/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/it/aspose.slides.export/ihtmloptions/ink_options/) | Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato.<br/>            Sola lettura [`IInkOptions`](/slides/python-net/it/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/it/aspose.slides.export/ihtmloptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/it/aspose.slides.export/ihtmloptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/it/aspose.slides.export/ihtmloptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/it/aspose.slides.export/ihtmloptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/it/aspose.slides.export/ihtmloptions/skip_java_script_links/) |  |

### Vedi anche
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)