---
title: Slide class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/slide/
---
## Slide Klasse

Stellt eine Folie in einer Präsentation dar.

**Vererbung:**[`Slide`](/slides/python-net/de/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/de/aspose.slides/baseslide)

Der Typ Slide stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`shapes`](/slides/python-net/de/aspose.slides/slide/shapes/) | Gibt die Formen einer Folie zurück.<br/>            Nur lesend [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/de/aspose.slides/slide/controls/) | Gibt die Sammlung von ActiveX-Steuerelementen auf einer Folie zurück.<br/>            Nur lesend [`IControlCollection`](/slides/python-net/de/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/de/aspose.slides/slide/name/) | Gibt den Namen einer Folie zurück oder setzt ihn.<br/>            Lese/Schreib **str**. |
| [`slide_id`](/slides/python-net/de/aspose.slides/slide/slide_id/) | Gibt die ID einer Folie zurück.<br/>            Nur lesend **int**. |
| [`custom_data`](/slides/python-net/de/aspose.slides/slide/custom_data/) | Gibt die benutzerdefinierten Daten der Folie zurück.<br/>            Nur lesend [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/de/aspose.slides/slide/timeline/) | Gibt das Animationszeitlinien-Objekt zurück.<br/>            Nur lesend [`IAnimationTimeLine`](/slides/python-net/de/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/de/aspose.slides/slide/slide_show_transition/) | Gibt das Transition-Objekt zurück, das Informationen darüber enthält<br/>            wie die angegebene Folie während einer Bildschirmanzeige fortschreitet.<br/>            Nur lesend [`ISlideShowTransition`](/slides/python-net/de/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/de/aspose.slides/slide/background/) | Gibt den Folienhintergrund zurück.<br/>            Nur lesend [`IBackground`](/slides/python-net/de/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/de/aspose.slides/slide/hyperlink_queries/) | Bietet einfachen Zugriff auf enthaltene Hyperlinks.<br/>            Nur lesend [`IHyperlinkQueries`](/slides/python-net/de/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/de/aspose.slides/slide/show_master_shapes/) | Legt fest, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht.<br/>            Lese/Schreib **bool**. |
| [`presentation`](/slides/python-net/de/aspose.slides/slide/presentation/) | Gibt die IPresentation-Schnittstelle zurück.<br/>            Nur lesend [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/de/aspose.slides/slide/header_footer_manager/) | Gibt den HeaderFooter-Manager der Folie zurück.<br/>            Nur lesend [`ISlideHeaderFooterManager`](/slides/python-net/de/aspose.slides/islideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/de/aspose.slides/slide/theme_manager/) | Gibt den überschreibenden Themen-Manager zurück.<br/>            Nur lesend [`IOverrideThemeManager`](/slides/python-net/de/aspose.slides.theme/ioverridethememanager). |
| [`slide_number`](/slides/python-net/de/aspose.slides/slide/slide_number/) | Gibt die Nummer der Folie zurück.<br/>            Der Index der Folie in der [`Presentation.slides`](/slides/python-net/de/aspose.slides/presentation/slides)-Sammlung ist immer gleich SlideNumber - Presentation.FirstSlideNumber.<br/>            Lese/Schreib **int**. |
| [`hidden`](/slides/python-net/de/aspose.slides/slide/hidden/) | Bestimmt, ob die angegebene Folie während einer Bildschirmanzeige ausgeblendet ist.<br/>            Lese/Schreib **bool**. |
| [`layout_slide`](/slides/python-net/de/aspose.slides/slide/layout_slide/) | Gibt das Layout der Folie für die aktuelle Folie zurück oder setzt es.<br/>            Lese/Schreib [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/de/aspose.slides/slide/notes_slide_manager/) | Ermöglicht den Zugriff auf die Notizfolie, deren Hinzufügen und Entfernen.<br/>            Nur lesend [`INotesSlideManager`](/slides/python-net/de/aspose.slides/inotesslidemanager). |
| [`slide`](/slides/python-net/de/aspose.slides/slide/slide/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/de/aspose.slides/slide/join_portions_with_same_formatting/#) | Verbindet Lauftexte mit gleicher Formatierung in allen Absätzen in allen zulässigen Formen. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/de/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | Verbindet Lauftexte mit gleicher Formatierung in allen Absätzen in allen zulässigen Formen. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/de/aspose.slides/slide/get_image/#float-float) | Gibt ein Thumbnail-Image-Objekt mit benutzerdefinierter Skalierung zurück. |
| [`get_image(self)`](/slides/python-net/de/aspose.slides/slide/get_image/#) | Gibt ein Thumbnail-Image-Objekt zurück (20 % der realen Größe). |
| [`get_image(self, image_size)`](/slides/python-net/de/aspose.slides/slide/get_image/#asposepydrawingsize) | Gibt ein Thumbnail-Image-Objekt mit angegebener Größe zurück. |
| [`get_image(self, options)`](/slides/python-net/de/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | Gibt ein Thumbnail-Tiff-Image-Objekt mit angegebenen Parametern zurück. |
| [`get_image(self, options)`](/slides/python-net/de/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | Gibt ein Thumbnail-Image-Objekt zurück. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/de/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | Gibt ein Thumbnail-Image-Objekt mit benutzerdefinierter Skalierung zurück. |
| [`get_image(self, options, image_size)`](/slides/python-net/de/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Gibt ein Thumbnail-Image-Objekt mit angegebener Größe zurück. |
| [`write_as_svg(self, stream)`](/slides/python-net/de/aspose.slides/slide/write_as_svg/#iorawiobase) | Speichert den Folieninhalt als SVG-Datei. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/de/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Speichert den Folieninhalt als SVG-Datei. |
| [`equals(self, slide)`](/slides/python-net/de/aspose.slides/slide/equals/#ibaseslide) | Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind.<br/>            Der Rückgabewert wird basierend auf der Struktur und dem statischen Inhalt der Folie berechnet.<br/>            Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und andere Einstellungen etc. gleich sind. Der Vergleich berücksichtigt keine eindeutigen Bezeichnerwerte, z. B. SlideId, und keinen dynamischen Inhalt, z. B. den aktuellen Datumswert im Datums-Platzhalter. |
| [`create_theme_effective(self)`](/slides/python-net/de/aspose.slides/slide/create_theme_effective/#) | Gibt ein effektives Thema für diese Folie zurück. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/de/aspose.slides/slide/find_shape_by_alt_text/#str) | Findet das erste Vorkommen einer Form mit dem angegebenen Alternativtext. |
| [`write_as_emf(self, stream)`](/slides/python-net/de/aspose.slides/slide/write_as_emf/#iorawiobase) | Speichert den Folieninhalt als EMF-Datei. |
| [`remove(self)`](/slides/python-net/de/aspose.slides/slide/remove/#) | Entfernt die Folie aus der Präsentation. |
| [`reset(self)`](/slides/python-net/de/aspose.slides/slide/reset/#) | Setzt Position, Größe und Formatierung jeder Form zurück, die ein Prototype auf LayoutSlide hat. |
| [`get_slide_comments(self, author)`](/slides/python-net/de/aspose.slides/slide/get_slide_comments/#icommentauthor) | Gibt alle Folienkommentare zurück, die von einem bestimmten Autor hinzugefügt wurden. |

### Siehe auch
* Klasse [`BaseSlide`](/slides/python-net/de/aspose.slides/baseslide)
* Klasse [`Slide`](/slides/python-net/de/aspose.slides/slide)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)