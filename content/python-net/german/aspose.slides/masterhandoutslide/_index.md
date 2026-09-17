---
title: MasterHandoutSlide class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/masterhandoutslide/
---
## MasterHandoutSlide Klasse

Represents master slide for handouts.

**Inheritance:**[`MasterHandoutSlide`](/slides/python-net/de/aspose.slides/masterhandoutslide) → [`BaseSlide`](/slides/python-net/de/aspose.slides/baseslide)

The MasterHandoutSlide type exposes the following members:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`shapes`](/slides/python-net/de/aspose.slides/masterhandoutslide/shapes/) | Gibt die Formen einer Folie zurück.<br/>            Nur lesbar [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/de/aspose.slides/masterhandoutslide/controls/) | Gibt die Sammlung von ActiveX-Steuerelementen einer Folie zurück.<br/>            Nur lesbar [`IControlCollection`](/slides/python-net/de/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/de/aspose.slides/masterhandoutslide/name/) | Gibt den Namen einer Folie zurück oder setzt ihn.<br/>            Lesen/Schreiben **str**. |
| [`slide_id`](/slides/python-net/de/aspose.slides/masterhandoutslide/slide_id/) | Gibt die ID einer Folie zurück.<br/>            Nur lesbar **int**. |
| [`custom_data`](/slides/python-net/de/aspose.slides/masterhandoutslide/custom_data/) | Gibt die benutzerdefinierten Daten der Folie zurück.<br/>            Nur lesbar [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/de/aspose.slides/masterhandoutslide/timeline/) | Gibt das Animations-Zeitlinien-Objekt zurück.<br/>            Nur lesbar [`IAnimationTimeLine`](/slides/python-net/de/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/de/aspose.slides/masterhandoutslide/slide_show_transition/) | Gibt das Transition-Objekt zurück, das Informationen darüber enthält,<br/>            wie die angegebene Folie während einer Bildschirmpräsentation fortschreitet.<br/>            Nur lesbar [`ISlideShowTransition`](/slides/python-net/de/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/de/aspose.slides/masterhandoutslide/background/) | Gibt den Hintergrund der Folie zurück.<br/>            Nur lesbar [`IBackground`](/slides/python-net/de/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/de/aspose.slides/masterhandoutslide/hyperlink_queries/) | Stellt einfachen Zugriff auf enthaltene Hyperlinks bereit.<br/>            Nur lesbar [`IHyperlinkQueries`](/slides/python-net/de/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/de/aspose.slides/masterhandoutslide/show_master_shapes/) | Gibt an, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht.<br/>            Für die Masterfolie selbst gibt diese Eigenschaft immer `false` zurück.<br/>            Lesen/Schreiben **bool**. |
| [`presentation`](/slides/python-net/de/aspose.slides/masterhandoutslide/presentation/) | Gibt die IPresentation-Schnittstelle zurück.<br/>            Nur lesbar [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/de/aspose.slides/masterhandoutslide/header_footer_manager/) | Gibt den HeaderFooter-Manager der Master-Handout-Folie zurück.<br/>            Nur lesbar [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/de/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/de/aspose.slides/masterhandoutslide/theme_manager/) | Gibt den Theme-Manager zurück.<br/>            Nur lesbar [`IMasterThemeManager`](/slides/python-net/de/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/de/aspose.slides/masterhandoutslide/drawing_guides/) | Gibt eine Sammlung von Zeichenhilfen für die Master-Handout-Folie zurück.<br/>            Nur lesbar [`IDrawingGuidesCollection`](/slides/python-net/de/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/de/aspose.slides/masterhandoutslide/slide/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/de/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#) | Verbindet Textabschnitte mit gleicher Formatierung in allen Absätzen aller zulässigen Formen. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/de/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#ishapecollection) | Verbindet Textabschnitte mit gleicher Formatierung in allen Absätzen in allen zulässigen Formen. |
| [`equals(self, slide)`](/slides/python-net/de/aspose.slides/masterhandoutslide/equals/#ibaseslide) | Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind.<br/>            Der Rückgabewert wird basierend auf der Struktur und dem statischen Inhalt der Folie berechnet.<br/>            Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und andere Einstellungen usw. gleich sind. Der Vergleich berücksichtigt keine eindeutigen Bezeichnerwerte, z. B. SlideId, und keinen dynamischen Inhalt, z. B. den aktuellen Datumswert im Datums-Platzhalter. |
| [`create_theme_effective(self)`](/slides/python-net/de/aspose.slides/masterhandoutslide/create_theme_effective/#) | Gibt ein effektives Theme für diese Folie zurück. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/de/aspose.slides/masterhandoutslide/find_shape_by_alt_text/#str) | Findet das erste Vorkommen einer Form mit dem angegebenen Alternativtext. |


### Siehe auch
* Klasse [`BaseSlide`](/slides/python-net/de/aspose.slides/baseslide)
* Klasse [`MasterHandoutSlide`](/slides/python-net/de/aspose.slides/masterhandoutslide)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)