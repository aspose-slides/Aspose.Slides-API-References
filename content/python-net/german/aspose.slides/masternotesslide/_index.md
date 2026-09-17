---
title: MasterNotesSlide class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/masternotesslide/
---
## MasterNotesSlide Klasse

Stellt die Masterfolie für Notizen dar.

**Vererbung:**[`MasterNotesSlide`](/slides/python-net/de/aspose.slides/masternotesslide) → [`BaseSlide`](/slides/python-net/de/aspose.slides/baseslide)

Der Typ MasterNotesSlide stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`shapes`](/slides/python-net/de/aspose.slides/masternotesslide/shapes/) | Gibt die Formen einer Folie zurück.<br/>            Nur lesend [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/de/aspose.slides/masternotesslide/controls/) | Gibt die Sammlung von ActiveX-Steuerelementen auf einer Folie zurück.<br/>            Nur lesend [`IControlCollection`](/slides/python-net/de/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/de/aspose.slides/masternotesslide/name/) | Gibt den Namen einer Folie zurück oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`slide_id`](/slides/python-net/de/aspose.slides/masternotesslide/slide_id/) | Gibt die ID einer Folie zurück.<br/>            Nur lesend **int**. |
| [`custom_data`](/slides/python-net/de/aspose.slides/masternotesslide/custom_data/) | Gibt die benutzerdefinierten Daten der Folie zurück.<br/>            Nur lesend [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/de/aspose.slides/masternotesslide/timeline/) | Gibt das Animations-Zeitlinien-Objekt zurück.<br/>            Nur lesend [`IAnimationTimeLine`](/slides/python-net/de/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/de/aspose.slides/masternotesslide/slide_show_transition/) | Gibt das Transition-Objekt zurück, das Informationen darüber enthält,<br/>            wie die angegebene Folie während einer Bildschirmanzeige fortschreitet.<br/>            Nur lesend [`ISlideShowTransition`](/slides/python-net/de/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/de/aspose.slides/masternotesslide/background/) | Gibt den Hintergrund der Folie zurück.<br/>            Nur lesend [`IBackground`](/slides/python-net/de/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/de/aspose.slides/masternotesslide/hyperlink_queries/) | Bietet einfachen Zugriff auf enthaltene Hyperlinks.<br/>            Nur lesend [`IHyperlinkQueries`](/slides/python-net/de/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/de/aspose.slides/masternotesslide/show_master_shapes/) | Gibt an, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht.<br/>            Für die Masterfolie selbst gibt diese Eigenschaft immer `false` zurück.<br/>            Lesen/Schreiben **bool**. |
| [`presentation`](/slides/python-net/de/aspose.slides/masternotesslide/presentation/) | Gibt die IPresentation-Schnittstelle zurück.<br/>            Nur lesend [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/de/aspose.slides/masternotesslide/header_footer_manager/) | Gibt den HeaderFooter-Manager der Master-Notizfolie zurück.<br/>            Nur lesend [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/de/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/de/aspose.slides/masternotesslide/theme_manager/) | Gibt den Theme-Manager zurück.<br/>            Nur lesend [`IMasterThemeManager`](/slides/python-net/de/aspose.slides.theme/imasterthememanager). |
| [`notes_style`](/slides/python-net/de/aspose.slides/masternotesslide/notes_style/) | Gibt den Stil eines Notiztextes zurück.<br/>            Nur lesend [`ITextStyle`](/slides/python-net/de/aspose.slides/itextstyle). |
| [`drawing_guides`](/slides/python-net/de/aspose.slides/masternotesslide/drawing_guides/) | Gibt eine Sammlung von Zeichenhilfen für die Master-Notizfolie zurück.<br/>            Nur lesend [`IDrawingGuidesCollection`](/slides/python-net/de/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/de/aspose.slides/masternotesslide/slide/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/de/aspose.slides/masternotesslide/join_portions_with_same_formatting/#) | Führt Textabschnitte mit gleicher Formatierung in allen Absätzen aller zulässigen Formen zusammen. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/de/aspose.slides/masternotesslide/join_portions_with_same_formatting/#ishapecollection) | Führt Textabschnitte mit gleicher Formatierung in allen Absätzen aller zulässigen Formen zusammen. |
| [`equals(self, slide)`](/slides/python-net/de/aspose.slides/masternotesslide/equals/#ibaseslide) | Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind.<br/>            Der Rückgabewert wird basierend auf der Struktur und dem statischen Inhalt der Folie berechnet.<br/>            Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und andere Einstellungen usw. gleich sind. Der Vergleich berücksichtigt keine eindeutigen Bezeichnerwerte, z. B. SlideId, und keinen dynamischen Inhalt, z. B. den aktuellen Datumswert im Datums-Platzhalter. |
| [`create_theme_effective(self)`](/slides/python-net/de/aspose.slides/masternotesslide/create_theme_effective/#) | Gibt ein effektives Theme für diese Folie zurück. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/de/aspose.slides/masternotesslide/find_shape_by_alt_text/#str) | Findet das erste Vorkommen einer Form mit dem angegebenen Alternativtext. |

### Siehe auch
* Klasse [`BaseSlide`](/slides/python-net/de/aspose.slides/baseslide)
* Klasse [`MasterNotesSlide`](/slides/python-net/de/aspose.slides/masternotesslide)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)