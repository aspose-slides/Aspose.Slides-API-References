---
title: ISlide class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/islide/
---
## ISlide klasse

Representeert een slide in een presentatie.

Het ISlide-type biedt de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/nl/aspose.slides/islide/header_footer_manager/) | Retourneert HeaderFooter manager van de slide.<br/>            Alleen-lezen [`ISlideHeaderFooterManager`](/slides/python-net/nl/aspose.slides/islideheaderfootermanager). |
| [`slide_number`](/slides/python-net/nl/aspose.slides/islide/slide_number/) | Retourneert een nummer van de slide.<br/>            Index van de slide in de [`IPresentation.slides`](/slides/python-net/nl/aspose.slides/ipresentation/slides) collectie is altijd gelijk aan SlideNumber - 1.<br/>            Lezen/schrijven **int**. |
| [`hidden`](/slides/python-net/nl/aspose.slides/islide/hidden/) | Bepaalt of de opgegeven slide verborgen is tijdens een diavoorstelling.<br/>            Lezen/schrijven **bool**. |
| [`layout_slide`](/slides/python-net/nl/aspose.slides/islide/layout_slide/) | Retourneert of stelt de layout slide in voor de huidige slide.<br/>            Lezen/schrijven [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/nl/aspose.slides/islide/notes_slide_manager/) | Sta toe notes slide te benaderen, toe te voegen en te verwijderen.<br/>            Alleen-lezen [`INotesSlideManager`](/slides/python-net/nl/aspose.slides/inotesslidemanager). |
| [`shapes`](/slides/python-net/nl/aspose.slides/islide/shapes/) |  |
| [`controls`](/slides/python-net/nl/aspose.slides/islide/controls/) |  |
| [`name`](/slides/python-net/nl/aspose.slides/islide/name/) |  |
| [`slide_id`](/slides/python-net/nl/aspose.slides/islide/slide_id/) |  |
| [`custom_data`](/slides/python-net/nl/aspose.slides/islide/custom_data/) |  |
| [`timeline`](/slides/python-net/nl/aspose.slides/islide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/nl/aspose.slides/islide/slide_show_transition/) |  |
| [`background`](/slides/python-net/nl/aspose.slides/islide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/nl/aspose.slides/islide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/nl/aspose.slides/islide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/nl/aspose.slides/islide/slide/) |  |
| [`presentation`](/slides/python-net/nl/aspose.slides/islide/presentation/) |  |
| [`theme_manager`](/slides/python-net/nl/aspose.slides/islide/theme_manager/) |  |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/nl/aspose.slides/islide/get_image/#float-float) | Retourneert een afbeeldingsobject met aangepaste schaalverdeling. |
| [`get_image(self)`](/slides/python-net/nl/aspose.slides/islide/get_image/#) | Retourneert een Thumbnail Image object (20% van de werkelijke grootte). |
| [`get_image(self, image_size)`](/slides/python-net/nl/aspose.slides/islide/get_image/#asposeslidessize) | Retourneert een afbeeldingsobject met gespecificeerde grootte. |
| [`get_image(self, options)`](/slides/python-net/nl/aspose.slides/islide/get_image/#asposeslidesexportitiffoptions) | Retourneert een Thumbnail tiff bitmap object met gespecificeerde parameters. |
| [`get_image(self, options)`](/slides/python-net/nl/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions) | Retourneert een Thumbnail Bitmap object. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/nl/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-float-float) | Retourneert een Thumbnail Bitmap object met aangepaste schaalverdeling. |
| [`get_image(self, options, image_size)`](/slides/python-net/nl/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | Retourneert een Thumbnail Bitmap object met gespecificeerde grootte. |
| [`write_as_svg(self, stream)`](/slides/python-net/nl/aspose.slides/islide/write_as_svg/#iorawiobase) | Slaat de slide-inhoud op als een SVG-bestand. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/nl/aspose.slides/islide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Slaat de slide-inhoud op als een SVG-bestand. |
| [`get_slide_comments(self, author)`](/slides/python-net/nl/aspose.slides/islide/get_slide_comments/#icommentauthor) | Retourneert alle slide comments toegevoegd door een specifieke auteur. |
| [`write_as_emf(self, stream)`](/slides/python-net/nl/aspose.slides/islide/write_as_emf/#iorawiobase) | Slaat de slide-inhoud op als een EMF-bestand. |
| [`remove(self)`](/slides/python-net/nl/aspose.slides/islide/remove/#) | Verwijdert slide uit de presentatie. |
| [`reset(self)`](/slides/python-net/nl/aspose.slides/islide/reset/#) | Reset de positie, grootte en opmaak van elke vorm die een prototype heeft op LayoutSlide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/nl/aspose.slides/islide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/nl/aspose.slides/islide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/nl/aspose.slides/islide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/nl/aspose.slides/islide/create_theme_effective/#) |  |

### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)