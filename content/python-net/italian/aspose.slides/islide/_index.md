---
title: ISlide class
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/islide/
---
## ISlide classe

Rappresenta una diapositiva in una presentazione.

Il tipo ISlide espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/it/aspose.slides/islide/header_footer_manager/) | Returns HeaderFooter manager of the slide.<br/>            Solo lettura [`ISlideHeaderFooterManager`](/slides/python-net/it/aspose.slides/islideheaderfootermanager). |
| [`slide_number`](/slides/python-net/it/aspose.slides/islide/slide_number/) | Restituisce il numero di diapositiva.<br/>            L'indice della diapositiva nella collezione [`IPresentation.slides`](/slides/python-net/it/aspose.slides/ipresentation/slides) è sempre uguale a SlideNumber - 1.<br/>            Lettura/scrittura **int**. |
| [`hidden`](/slides/python-net/it/aspose.slides/islide/hidden/) | Determina se la diapositiva specificata è nascosta durante una presentazione.<br/>            Lettura/scrittura **bool**. |
| [`layout_slide`](/slides/python-net/it/aspose.slides/islide/layout_slide/) | Restituisce o imposta la diapositiva layout per la diapositiva corrente.<br/>            Lettura/scrittura [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/it/aspose.slides/islide/notes_slide_manager/) | Consente di accedere alla diapositiva delle note, aggiungerla e rimuoverla.<br/>            Solo lettura [`INotesSlideManager`](/slides/python-net/it/aspose.slides/inotesslidemanager). |
| [`shapes`](/slides/python-net/it/aspose.slides/islide/shapes/) |  |
| [`controls`](/slides/python-net/it/aspose.slides/islide/controls/) |  |
| [`name`](/slides/python-net/it/aspose.slides/islide/name/) |  |
| [`slide_id`](/slides/python-net/it/aspose.slides/islide/slide_id/) |  |
| [`custom_data`](/slides/python-net/it/aspose.slides/islide/custom_data/) |  |
| [`timeline`](/slides/python-net/it/aspose.slides/islide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/it/aspose.slides/islide/slide_show_transition/) |  |
| [`background`](/slides/python-net/it/aspose.slides/islide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/it/aspose.slides/islide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/it/aspose.slides/islide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/it/aspose.slides/islide/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides/islide/presentation/) |  |
| [`theme_manager`](/slides/python-net/it/aspose.slides/islide/theme_manager/) |  |

## Metodi

| Method | Description |
| :- | :- |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/it/aspose.slides/islide/get_image/#float-float) | Restituisce un oggetto immagine con scala personalizzata. |
| [`get_image(self)`](/slides/python-net/it/aspose.slides/islide/get_image/#) | Restituisce un oggetto Thumbnail Image (20% della dimensione reale). |
| [`get_image(self, image_size)`](/slides/python-net/it/aspose.slides/islide/get_image/#asposepydrawingsize) | Restituisce un oggetto immagine con dimensione specificata. |
| [`get_image(self, options)`](/slides/python-net/it/aspose.slides/islide/get_image/#asposeslidesexportitiffoptions) | Restituisce un oggetto Thumbnail tiff bitmap con parametri specificati. |
| [`get_image(self, options)`](/slides/python-net/it/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions) | Restituisce un oggetto Thumbnail Bitmap. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/it/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-float-float) | Restituisce un oggetto Thumbnail Bitmap con scala personalizzata. |
| [`get_image(self, options, image_size)`](/slides/python-net/it/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Restituisce un oggetto Thumbnail Bitmap con dimensione specificata. |
| [`write_as_svg(self, stream)`](/slides/python-net/it/aspose.slides/islide/write_as_svg/#iorawiobase) | Salva il contenuto della diapositiva come file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/it/aspose.slides/islide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Salva il contenuto della diapositiva come file SVG. |
| [`get_slide_comments(self, author)`](/slides/python-net/it/aspose.slides/islide/get_slide_comments/#icommentauthor) | Restituisce tutti i commenti della diapositiva aggiunti da uno specifico autore. |
| [`write_as_emf(self, stream)`](/slides/python-net/it/aspose.slides/islide/write_as_emf/#iorawiobase) | Salva il contenuto della diapositiva come file EMF. |
| [`remove(self)`](/slides/python-net/it/aspose.slides/islide/remove/#) | Rimuove la diapositiva dalla presentazione. |
| [`reset(self)`](/slides/python-net/it/aspose.slides/islide/reset/#) | Reimposta posizione, dimensione e formattazione di ogni forma che ha un prototipo su LayoutSlide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/it/aspose.slides/islide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/it/aspose.slides/islide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/it/aspose.slides/islide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/it/aspose.slides/islide/create_theme_effective/#) |  |

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)