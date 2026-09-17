---
title: LayoutSlide class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/layoutslide/
---
## LayoutSlide Klasse

Stellt eine Layout-Folie dar.

**Vererbung:**[`LayoutSlide`](/slides/python-net/de/aspose.slides/layoutslide) → [`BaseSlide`](/slides/python-net/de/aspose.slides/baseslide)

Der LayoutSlide-Typ stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`shapes`](/slides/python-net/de/aspose.slides/layoutslide/shapes/) | Gibt die Formen einer Folie zurück.<br/>            Nur lesbar [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/de/aspose.slides/layoutslide/controls/) | Gibt die Sammlung von ActiveX-Steuerelementen einer Folie zurück.<br/>            Nur lesbar [`IControlCollection`](/slides/python-net/de/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/de/aspose.slides/layoutslide/name/) | Gibt den Namen einer Folie zurück oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`slide_id`](/slides/python-net/de/aspose.slides/layoutslide/slide_id/) | Gibt die ID einer Folie zurück.<br/>            Nur lesbar **int**. |
| [`custom_data`](/slides/python-net/de/aspose.slides/layoutslide/custom_data/) | Gibt die benutzerdefinierten Daten der Folie zurück.<br/>            Nur lesbar [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/de/aspose.slides/layoutslide/timeline/) | Gibt das Animationszeitlinien-Objekt zurück.<br/>            Nur lesbar [`IAnimationTimeLine`](/slides/python-net/de/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/de/aspose.slides/layoutslide/slide_show_transition/) | Gibt das Transition-Objekt zurück, das Informationen darüber enthält<br/>            wie die angegebene Folie während einer Bildschirmpräsentation fortschreitet.<br/>            Nur lesbar [`ISlideShowTransition`](/slides/python-net/de/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/de/aspose.slides/layoutslide/background/) | Gibt den Hintergrund der Folie zurück.<br/>            Nur lesbar [`IBackground`](/slides/python-net/de/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/de/aspose.slides/layoutslide/hyperlink_queries/) | Stellt einfachen Zugriff auf enthaltene Hyperlinks bereit.<br/>            Nur lesbar [`IHyperlinkQueries`](/slides/python-net/de/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/de/aspose.slides/layoutslide/show_master_shapes/) | Legt fest, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht.<br/>            Lesen/Schreiben **bool**. |
| [`presentation`](/slides/python-net/de/aspose.slides/layoutslide/presentation/) | Gibt die IPresentation-Schnittstelle zurück.<br/>            Nur lesbar [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/de/aspose.slides/layoutslide/header_footer_manager/) | Gibt den HeaderFooter-Manager der Layoutfolie zurück.<br/>            Nur lesbar [`ILayoutSlideHeaderFooterManager`](/slides/python-net/de/aspose.slides/ilayoutslideheaderfootermanager). |
| [`placeholder_manager`](/slides/python-net/de/aspose.slides/layoutslide/placeholder_manager/) | Gibt den Platzhalter-Manager der Layoutfolie zurück.<br/>            Nur lesbar [`ILayoutPlaceholderManager`](/slides/python-net/de/aspose.slides/ilayoutplaceholdermanager). |
| [`master_slide`](/slides/python-net/de/aspose.slides/layoutslide/master_slide/) | Gibt die Masterfolie für ein Layout zurück oder legt sie fest.<br/>            Lesen/Schreiben [`IMasterSlide`](/slides/python-net/de/aspose.slides/imasterslide). |
| [`theme_manager`](/slides/python-net/de/aspose.slides/layoutslide/theme_manager/) | Gibt den überschreibenden Theme-Manager zurück.<br/>            Nur lesbar [`IOverrideThemeManager`](/slides/python-net/de/aspose.slides.theme/ioverridethememanager). |
| [`layout_type`](/slides/python-net/de/aspose.slides/layoutslide/layout_type/) | Gibt den Layouttyp dieser Layoutfolie zurück.<br/>            Nur lesbar [`SlideLayoutType`](/slides/python-net/de/aspose.slides/slidelayouttype). |
| [`has_depending_slides`](/slides/python-net/de/aspose.slides/layoutslide/has_depending_slides/) | Gibt true zurück, wenn mindestens eine Folie von dieser Layoutfolie abhängt.<br/>            Nur lesbar **bool**. |
| [`drawing_guides`](/slides/python-net/de/aspose.slides/layoutslide/drawing_guides/) | Gibt eine Sammlung von Zeichenhilfen für die Layoutfolie zurück.<br/>            Nur lesbar [`IDrawingGuidesCollection`](/slides/python-net/de/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/de/aspose.slides/layoutslide/slide/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/de/aspose.slides/layoutslide/join_portions_with_same_formatting/#) | Verbindet Läufe mit gleicher Formatierung in allen Absätzen aller akzeptablen Formen. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/de/aspose.slides/layoutslide/join_portions_with_same_formatting/#ishapecollection) | Verbindet Läufe mit gleicher Formatierung in allen Absätzen in allen akzeptablen Formen. |
| [`equals(self, slide)`](/slides/python-net/de/aspose.slides/layoutslide/equals/#ibaseslide) | Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind.<br/>            Der Rückgabewert wird basierend auf der Struktur und dem statischen Inhalt der Folie berechnet.<br/>            Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und andere Einstellungen usw. gleich sind. Der Vergleich berücksichtigt keine eindeutigen Bezeichnerwerte, z. B. SlideId, und keinen dynamischen Inhalt, z. B. den aktuellen Datumswert im Datums-Platzhalter. |
| [`create_theme_effective(self)`](/slides/python-net/de/aspose.slides/layoutslide/create_theme_effective/#) | Gibt ein effektives Theme für diese Folie zurück. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/de/aspose.slides/layoutslide/find_shape_by_alt_text/#str) | Findet das erste Vorkommen einer Form mit dem angegebenen Alternativtext. |
| [`remove(self)`](/slides/python-net/de/aspose.slides/layoutslide/remove/#) | Entfernt das Layout aus der Präsentation. |
| [`get_depending_slides(self)`](/slides/python-net/de/aspose.slides/layoutslide/get_depending_slides/#) | Gibt ein Array mit allen Folien zurück, die von dieser Layoutfolie abhängen. |

### Siehe auch
* Klasse [`BaseSlide`](/slides/python-net/de/aspose.slides/baseslide)
* Klasse [`LayoutSlide`](/slides/python-net/de/aspose.slides/layoutslide)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)