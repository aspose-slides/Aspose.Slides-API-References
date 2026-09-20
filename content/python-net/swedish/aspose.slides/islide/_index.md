---
title: ISlide class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/islide/
---
## ISlide klass

Representerar en bild i en presentation.

ISlide-typen exponerar följande medlemmar:

## Egenskaper

| Property | Description |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/sv/aspose.slides/islide/header_footer_manager/) | Returnerar HeaderFooter-hanteraren för bilden.<br/>            Endast läsning [`ISlideHeaderFooterManager`](/slides/python-net/sv/aspose.slides/islideheaderfootermanager). |
| [`slide_number`](/slides/python-net/sv/aspose.slides/islide/slide_number/) | Returnerar ett nummer på bilden.<br/>            Indexet för bilden i [`IPresentation.slides`](/slides/python-net/sv/aspose.slides/ipresentation/slides)-samlingen är alltid lika med SlideNumber - 1.<br/>            Läs/skriv **int**. |
| [`hidden`](/slides/python-net/sv/aspose.slides/islide/hidden/) | Bestämmer om den angivna bilden är dold under bildspelet.<br/>            Läs/skriv **bool**. |
| [`layout_slide`](/slides/python-net/sv/aspose.slides/islide/layout_slide/) | Returnerar eller anger layoutbilden för den aktuella bilden.<br/>            Läs/skriv [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/sv/aspose.slides/islide/notes_slide_manager/) | Tillåter åtkomst till notisbilder, lägga till och ta bort dem.<br/>            Endast läsning [`INotesSlideManager`](/slides/python-net/sv/aspose.slides/inotesslidemanager). |
| [`shapes`](/slides/python-net/sv/aspose.slides/islide/shapes/) |  |
| [`controls`](/slides/python-net/sv/aspose.slides/islide/controls/) |  |
| [`name`](/slides/python-net/sv/aspose.slides/islide/name/) |  |
| [`slide_id`](/slides/python-net/sv/aspose.slides/islide/slide_id/) |  |
| [`custom_data`](/slides/python-net/sv/aspose.slides/islide/custom_data/) |  |
| [`timeline`](/slides/python-net/sv/aspose.slides/islide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/sv/aspose.slides/islide/slide_show_transition/) |  |
| [`background`](/slides/python-net/sv/aspose.slides/islide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/sv/aspose.slides/islide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/sv/aspose.slides/islide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/sv/aspose.slides/islide/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides/islide/presentation/) |  |
| [`theme_manager`](/slides/python-net/sv/aspose.slides/islide/theme_manager/) |  |

## Metoder

| Method | Description |
| :- | :- |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/sv/aspose.slides/islide/get_image/#float-float) | Returnerar ett bildobjekt med anpassad skalning. |
| [`get_image(self)`](/slides/python-net/sv/aspose.slides/islide/get_image/#) | Returnerar ett miniatyrbildsobjekt (20 % av verklig storlek). |
| [`get_image(self, image_size)`](/slides/python-net/sv/aspose.slides/islide/get_image/#asposepydrawingsize) | Returnerar ett bildobjekt med angiven storlek. |
| [`get_image(self, options)`](/slides/python-net/sv/aspose.slides/islide/get_image/#asposeslidesexportitiffoptions) | Returnerar ett miniatyr-tiff-bitmap-objekt med angivna parametrar. |
| [`get_image(self, options)`](/slides/python-net/sv/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions) | Returnerar ett miniatyr-Bitmap-objekt. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/sv/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-float-float) | Returnerar ett miniatyr-Bitmap-objekt med anpassad skalning. |
| [`get_image(self, options, image_size)`](/slides/python-net/sv/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Returnerar ett miniatyr-Bitmap-objekt med angiven storlek. |
| [`write_as_svg(self, stream)`](/slides/python-net/sv/aspose.slides/islide/write_as_svg/#iorawiobase) | Sparar bildens innehåll som en SVG-fil. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/sv/aspose.slides/islide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Sparar bildens innehåll som en SVG-fil. |
| [`get_slide_comments(self, author)`](/slides/python-net/sv/aspose.slides/islide/get_slide_comments/#icommentauthor) | Returnerar alla bildkommentarer som lagts till av en specifik författare. |
| [`write_as_emf(self, stream)`](/slides/python-net/sv/aspose.slides/islide/write_as_emf/#iorawiobase) | Sparar bildens innehåll som en EMF-fil. |
| [`remove(self)`](/slides/python-net/sv/aspose.slides/islide/remove/#) | Tar bort bilden från presentationen. |
| [`reset(self)`](/slides/python-net/sv/aspose.slides/islide/reset/#) | Återställer position, storlek och formatering för varje form som har en prototyp på LayoutSlide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/sv/aspose.slides/islide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/sv/aspose.slides/islide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/sv/aspose.slides/islide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/sv/aspose.slides/islide/create_theme_effective/#) |  |


### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)