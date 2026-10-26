---
title: NotesSlide class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/notesslide/
---
## NotesSlide Klasse

Stellt eine Notizfolie in einer Präsentation dar.

**Vererbung:**[`NotesSlide`](/slides/python-net/de/aspose.slides/notesslide) → [`BaseSlide`](/slides/python-net/de/aspose.slides/baseslide)

Der Typ NotesSlide stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`shapes`](/slides/python-net/de/aspose.slides/notesslide/shapes/) | Gibt die Formen einer Folie zurück.<br/>            Nur lesbar [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/de/aspose.slides/notesslide/controls/) | Gibt die Sammlung von ActiveX-Steuerelementen auf einer Folie zurück.<br/>            Nur lesbar [`IControlCollection`](/slides/python-net/de/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/de/aspose.slides/notesslide/name/) | Gibt den Namen einer Folie zurück oder setzt ihn.<br/>            Lesen/Schreiben **str**. |
| [`slide_id`](/slides/python-net/de/aspose.slides/notesslide/slide_id/) | Gibt die ID einer Folie zurück.<br/>            Nur lesbar **int**. |
| [`custom_data`](/slides/python-net/de/aspose.slides/notesslide/custom_data/) | Gibt die benutzerdefinierten Daten der Folie zurück.<br/>            Nur lesbar [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/de/aspose.slides/notesslide/timeline/) | Gibt das Animationszeitachsen-Objekt zurück.<br/>            Nur lesbar [`IAnimationTimeLine`](/slides/python-net/de/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/de/aspose.slides/notesslide/slide_show_transition/) | Gibt das Transition-Objekt zurück, das Informationen darüber enthält<br/>            wie die angegebene Folie während einer Bildschirmpräsentation fortschreitet.<br/>            Nur lesbar [`ISlideShowTransition`](/slides/python-net/de/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/de/aspose.slides/notesslide/background/) | Gibt den Hintergrund der Folie zurück.<br/>            Nur lesbar [`IBackground`](/slides/python-net/de/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/de/aspose.slides/notesslide/hyperlink_queries/) | Bietet einfachen Zugriff auf enthaltene Hyperlinks.<br/>            Nur lesbar [`IHyperlinkQueries`](/slides/python-net/de/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/de/aspose.slides/notesslide/show_master_shapes/) | Gibt an, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht.<br/>            Lesen/Schreiben **bool**. |
| [`presentation`](/slides/python-net/de/aspose.slides/notesslide/presentation/) | Gibt die IPresentation-Schnittstelle zurück.<br/>            Nur lesbar [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/de/aspose.slides/notesslide/header_footer_manager/) | Gibt den HeaderFooter-Manager der Notizfolie zurück.<br/>            Nur lesbar [`INotesSlideHeaderFooterManager`](/slides/python-net/de/aspose.slides/inotesslideheaderfootermanager). |
| [`notes_text_frame`](/slides/python-net/de/aspose.slides/notesslide/notes_text_frame/) | Gibt einen TextFrame mit dem Text der Notizen zurück, falls vorhanden.<br/>            Nur lesbar [`ITextFrame`](/slides/python-net/de/aspose.slides/itextframe). |
| [`theme_manager`](/slides/python-net/de/aspose.slides/notesslide/theme_manager/) | Gibt den überschreibenden Themen-Manager zurück.<br/>            Nur lesbar [`IOverrideThemeManager`](/slides/python-net/de/aspose.slides.theme/ioverridethememanager). |
| [`parent_slide`](/slides/python-net/de/aspose.slides/notesslide/parent_slide/) | Gibt die übergeordnete Folie zurück.<br/>            Nur lesbar [`ISlide`](/slides/python-net/de/aspose.slides/islide). |
| [`slide`](/slides/python-net/de/aspose.slides/notesslide/slide/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/de/aspose.slides/notesslide/join_portions_with_same_formatting/#) | Verbindet Lauftexte mit derselben Formatierung in allen Absätzen aller zulässigen Formen. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/de/aspose.slides/notesslide/join_portions_with_same_formatting/#ishapecollection) | Verbindet Lauftexte mit derselben Formatierung in allen Absätzen in allen zulässigen Formen. |
| [`equals(self, slide)`](/slides/python-net/de/aspose.slides/notesslide/equals/#ibaseslide) | Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind.<br/>            Der zurückgegebene Wert wird basierend auf der Struktur der Folie und dem statischen Inhalt berechnet.<br/>            Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und andere Einstellungen usw. gleich sind. Der Vergleich berücksichtigt keine eindeutigen Bezeichnerwerte, z. B. SlideId und dynamischen Inhalt, z. B. den aktuellen Datumswert im Datumsplatzhalter. |
| [`create_theme_effective(self)`](/slides/python-net/de/aspose.slides/notesslide/create_theme_effective/#) | Gibt ein effektives Theme für diese Folie zurück. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/de/aspose.slides/notesslide/find_shape_by_alt_text/#str) | Findet das erste Vorkommen einer Form mit dem angegebenen alternativen Text. |

### Siehe auch
* Klasse [`BaseSlide`](/slides/python-net/de/aspose.slides/baseslide)
* Klasse [`NotesSlide`](/slides/python-net/de/aspose.slides/notesslide)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)