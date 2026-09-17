---
title: ISlide class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/islide/
---
## ISlide Klasse

Represents a slide in a presentation.

The ISlide type exposes the following members:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/de/aspose.slides/islide/header_footer_manager/) | Gibt den HeaderFooter-Manager der Folie zurück.<br/>            Nur lesbar [`ISlideHeaderFooterManager`](/slides/python-net/de/aspose.slides/islideheaderfootermanager). |
| [`slide_number`](/slides/python-net/de/aspose.slides/islide/slide_number/) | Gibt die Nummer der Folie zurück.<br/>            Der Index der Folie in der [`IPresentation.slides`](/slides/python-net/de/aspose.slides/ipresentation/slides)-Sammlung ist immer gleich SlideNumber - 1.<br/>            Lesen/Schreiben **int**. |
| [`hidden`](/slides/python-net/de/aspose.slides/islide/hidden/) | Bestimmt, ob die angegebene Folie während einer Diashow ausgeblendet ist.<br/>            Lesen/Schreiben **bool**. |
| [`layout_slide`](/slides/python-net/de/aspose.slides/islide/layout_slide/) | Gibt die Layout-Folie für die aktuelle Folie zurück oder setzt sie.<br/>            Lesen/Schreiben [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/de/aspose.slides/islide/notes_slide_manager/) | Ermöglicht den Zugriff auf die Notizfolie, das Hinzufügen und Entfernen.<br/>            Nur lesbar [`INotesSlideManager`](/slides/python-net/de/aspose.slides/inotesslidemanager). |
| [`shapes`](/slides/python-net/de/aspose.slides/islide/shapes/) |  |
| [`controls`](/slides/python-net/de/aspose.slides/islide/controls/) |  |
| [`name`](/slides/python-net/de/aspose.slides/islide/name/) |  |
| [`slide_id`](/slides/python-net/de/aspose.slides/islide/slide_id/) |  |
| [`custom_data`](/slides/python-net/de/aspose.slides/islide/custom_data/) |  |
| [`timeline`](/slides/python-net/de/aspose.slides/islide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/de/aspose.slides/islide/slide_show_transition/) |  |
| [`background`](/slides/python-net/de/aspose.slides/islide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/de/aspose.slides/islide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/de/aspose.slides/islide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/de/aspose.slides/islide/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides/islide/presentation/) |  |
| [`theme_manager`](/slides/python-net/de/aspose.slides/islide/theme_manager/) |  |

## Methoden

| Method | Description |
| :- | :- |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/de/aspose.slides/islide/get_image/#float-float) | Gibt ein Bildobjekt mit benutzerdefinierter Skalierung zurück. |
| [`get_image(self)`](/slides/python-net/de/aspose.slides/islide/get_image/#) | Gibt ein Thumbnail-Bildobjekt zurück (20 % der Originalgröße). |
| [`get_image(self, image_size)`](/slides/python-net/de/aspose.slides/islide/get_image/#asposepydrawingsize) | Gibt ein Bildobjekt mit angegebenen Abmessungen zurück. |
| [`get_image(self, options)`](/slides/python-net/de/aspose.slides/islide/get_image/#asposeslidesexportitiffoptions) | Gibt ein Thumbnail-TIFF-Bitmap-Objekt mit angegebenen Parametern zurück. |
| [`get_image(self, options)`](/slides/python-net/de/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions) | Gibt ein Thumbnail-Bitmap-Objekt zurück. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/de/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-float-float) | Gibt ein Thumbnail-Bitmap-Objekt mit benutzerdefinierter Skalierung zurück. |
| [`get_image(self, options, image_size)`](/slides/python-net/de/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Gibt ein Thumbnail-Bitmap-Objekt mit angegebenen Abmessungen zurück. |
| [`write_as_svg(self, stream)`](/slides/python-net/de/aspose.slides/islide/write_as_svg/#iorawiobase) | Speichert den Folieninhalt als SVG-Datei. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/de/aspose.slides/islide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Speichert den Folieninhalt als SVG-Datei. |
| [`get_slide_comments(self, author)`](/slides/python-net/de/aspose.slides/islide/get_slide_comments/#icommentauthor) | Gibt alle Folienkommentare zurück, die von einem bestimmten Autor hinzugefügt wurden. |
| [`write_as_emf(self, stream)`](/slides/python-net/de/aspose.slides/islide/write_as_emf/#iorawiobase) | Speichert den Folieninhalt als EMF-Datei. |
| [`remove(self)`](/slides/python-net/de/aspose.slides/islide/remove/#) | Entfernt die Folie aus der Präsentation. |
| [`reset(self)`](/slides/python-net/de/aspose.slides/islide/reset/#) | Setzt Position, Größe und Formatierung jeder Form zurück, die auf LayoutSlide einen Prototyp hat. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/de/aspose.slides/islide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/de/aspose.slides/islide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/de/aspose.slides/islide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/de/aspose.slides/islide/create_theme_effective/#) |  |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)