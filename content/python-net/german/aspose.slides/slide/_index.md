---
title: Slide class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/slide/
---
## Slide Klasse

Stellt eine Folie in einer Präsentation dar.

**Vererbung:**[`Slide`](/slides/python-net/de/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/de/aspose.slides/baseslide)

Der Slide-Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/de/aspose.slides/slide/shapes/) | Gibt die Formen einer Folie zurück.<br/>            Nur lesend [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/de/aspose.slides/slide/controls/) | Gibt die Sammlung von ActiveX-Steuerelementen einer Folie zurück.<br/>            Nur lesend [`IControlCollection`](/slides/python-net/de/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/de/aspose.slides/slide/name/) | Gibt den Namen einer Folie zurück oder setzt ihn.<br/>            Lesen/Schreiben **str**. |
| [`slide_id`](/slides/python-net/de/aspose.slides/slide/slide_id/) | Gibt die ID einer Folie zurück.<br/>            Nur lesend **int**. |
| [`custom_data`](/slides/python-net/de/aspose.slides/slide/custom_data/) | Gibt die benutzerdefinierten Daten der Folie zurück.<br/>            Nur lesend [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/de/aspose.slides/slide/timeline/) | Gibt das Animationszeitlinien-Objekt zurück.<br/>            Nur lesend [`IAnimationTimeLine`](/slides/python-net/de/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/de/aspose.slides/slide/slide_show_transition/) | Gibt das Transition-Objekt zurück, das Informationen darüber enthält,<br/>            wie die angegebene Folie während einer Bildschirmpräsentation fortschreitet.<br/>            Nur lesend [`ISlideShowTransition`](/slides/python-net/de/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/de/aspose.slides/slide/background/) | Gibt den Hintergrund der Folie zurück.<br/>            Nur lesend [`IBackground`](/slides/python-net/de/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/de/aspose.slides/slide/hyperlink_queries/) | Bietet einfachen Zugriff auf enthaltene Hyperlinks.<br/>            Nur lesend [`IHyperlinkQueries`](/slides/python-net/de/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/de/aspose.slides/slide/show_master_shapes/) | Gibt an, ob Formen auf der Masterfolie auf den Folien angezeigt werden sollen oder nicht.<br/>            Lesen/Schreiben **bool**. |
| [`presentation`](/slides/python-net/de/aspose.slides/slide/presentation/) | Gibt die IPresentation-Schnittstelle zurück.<br/>            Nur lesend [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/de/aspose.slides/slide/header_footer_manager/) | Gibt den HeaderFooter-Manager der Folie zurück.<br/>            Nur lesend [`ISlideHeaderFooterManager`](/slides/python-net/de/aspose.slides/islideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/de/aspose.slides/slide/theme_manager/) | Gibt den überschreibenden Theme-Manager zurück.<br/>            Nur lesend [`IOverrideThemeManager`](/slides/python-net/de/aspose.slides.theme/ioverridethememanager). |
| [`slide_number`](/slides/python-net/de/aspose.slides/slide/slide_number/) | Gibt die Foliennummer zurück.<br/>            Der Index der Folie in der [`Presentation.slides`](/slides/python-net/de/aspose.slides/presentation/slides)-Sammlung ist stets gleich SlideNumber - Presentation.FirstSlideNumber.<br/>            Lesen/Schreiben **int**. |
| [`hidden`](/slides/python-net/de/aspose.slides/slide/hidden/) | Bestimmt, ob die angegebene Folie während einer Bildschirmpräsentation ausgeblendet ist.<br/>            Lesen/Schreiben **bool**. |
| [`layout_slide`](/slides/python-net/de/aspose.slides/slide/layout_slide/) | Gibt das Layout der Folie für die aktuelle Folie zurück oder setzt es.<br/>            Lesen/Schreiben [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/de/aspose.slides/slide/notes_slide_manager/) | Ermöglicht den Zugriff auf die Notizfolie, hinzufügen und entfernen.<br/>            Nur lesend [`INotesSlideManager`](/slides/python-net/de/aspose.slides/inotesslidemanager). |
| [`slide`](/slides/python-net/de/aspose.slides/slide/slide/) |  |

## Methoden

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/de/aspose.slides/slide/join_portions_with_same_formatting/#) | Verbindet Lauftexte mit gleicher Formatierung in allen Absätzen in allen zulässigen Formen. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/de/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | Verbindet Lauftexte mit gleicher Formatierung in allen Absätzen in allen zulässigen Formen. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/de/aspose.slides/slide/get_image/#float-float) | Gibt ein Thumbnail-Bildobjekt mit benutzerdefinierter Skalierung zurück. |
| [`get_image(self)`](/slides/python-net/de/aspose.slides/slide/get_image/#) | Gibt ein Thumbnail-Bildobjekt zurück (20 % der Originalgröße). |
| [`get_image(self, image_size)`](/slides/python-net/de/aspose.slides/slide/get_image/#asposeslidessize) | Gibt ein Thumbnail-Bildobjekt mit angegebener Größe zurück. |
| [`get_image(self, options)`](/slides/python-net/de/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | Gibt ein Thumbnail-TIFF-Bildobjekt mit angegebenen Parametern zurück. |
| [`get_image(self, options)`](/slides/python-net/de/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | Gibt ein Thumbnail-Bildobjekt zurück. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/de/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | Gibt ein Thumbnail-Bildobjekt mit benutzerdefinierter Skalierung zurück. |
| [`get_image(self, options, image_size)`](/slides/python-net/de/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | Gibt ein Thumbnail-Bildobjekt mit angegebener Größe zurück. |
| [`write_as_svg(self, stream)`](/slides/python-net/de/aspose.slides/slide/write_as_svg/#iorawiobase) | Speichert den Folieninhalt als SVG-Datei. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/de/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Speichert den Folieninhalt als SVG-Datei. |
| [`equals(self, slide)`](/slides/python-net/de/aspose.slides/slide/equals/#ibaseslide) | Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind.<br/>            Der Rückgabewert wird basierend auf der Struktur und dem statischen Inhalt der Folie berechnet.<br/>            Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und andere Einstellungen usw. gleich sind. Der Vergleich berücksichtigt keine eindeutigen Bezeichnerwerte, z. B. SlideId, und keinen dynamischen Inhalt, z. B. den aktuellen Datumswert im Datums-Platzhalter. |
| [`create_theme_effective(self)`](/slides/python-net/de/aspose.slides/slide/create_theme_effective/#) | Gibt ein effektives Theme für diese Folie zurück. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/de/aspose.slides/slide/find_shape_by_alt_text/#str) | Findet das erste Vorkommen einer Form mit dem angegebenen Alternativtext. |
| [`write_as_emf(self, stream)`](/slides/python-net/de/aspose.slides/slide/write_as_emf/#iorawiobase) | Speichert den Folieninhalt als EMF-Datei. |
| [`remove(self)`](/slides/python-net/de/aspose.slides/slide/remove/#) | Entfernt die Folie aus der Präsentation. |
| [`reset(self)`](/slides/python-net/de/aspose.slides/slide/reset/#) | Setzt Position, Größe und Formatierung jeder Form zurück, die eine Vorlage auf LayoutSlide hat. |
| [`get_slide_comments(self, author)`](/slides/python-net/de/aspose.slides/slide/get_slide_comments/#icommentauthor) | Gibt alle Folienkommentare zurück, die von einem bestimmten Autor hinzugefügt wurden. |

### Siehe auch
* class [`BaseSlide`](/slides/python-net/de/aspose.slides/baseslide)
* class [`Slide`](/slides/python-net/de/aspose.slides/slide)
* module [`aspose.slides`](/slides/python-net/de/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)