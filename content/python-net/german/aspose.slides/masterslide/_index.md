---
title: MasterSlide class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/masterslide/
---
## MasterSlide Klasse

Stellt eine Masterfolie in einer Präsentation dar.

**Vererbung:**[`MasterSlide`](/slides/python-net/de/aspose.slides/masterslide) → [`BaseSlide`](/slides/python-net/de/aspose.slides/baseslide)

Der MasterSlide-Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/de/aspose.slides/masterslide/shapes/) | Gibt die Formen einer Folie zurück.<br/>            Nur lesbar [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/de/aspose.slides/masterslide/controls/) | Gibt die Sammlung von ActiveX-Steuerelementen auf einer Folie zurück.<br/>            Nur lesbar [`IControlCollection`](/slides/python-net/de/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/de/aspose.slides/masterslide/name/) | Gibt den Namen einer Masterfolie zurück oder setzt ihn.<br/>            Lese/Schreib **str**. |
| [`slide_id`](/slides/python-net/de/aspose.slides/masterslide/slide_id/) | Gibt die ID einer Folie zurück.<br/>            Nur lesbar **int**. |
| [`custom_data`](/slides/python-net/de/aspose.slides/masterslide/custom_data/) | Gibt die benutzerdefinierten Daten der Folie zurück.<br/>            Nur lesbar [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/de/aspose.slides/masterslide/timeline/) | Gibt das Animationszeitlinienobjekt zurück.<br/>            Nur lesbar [`IAnimationTimeLine`](/slides/python-net/de/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/de/aspose.slides/masterslide/slide_show_transition/) | Gibt das Transition-Objekt zurück, das Informationen darüber enthält<br/>            wie die angegebene Folie während einer Bildschirmanzeige fortschreitet.<br/>            Nur lesbar [`ISlideShowTransition`](/slides/python-net/de/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/de/aspose.slides/masterslide/background/) | Gibt den Hintergrund der Folie zurück.<br/>            Nur lesbar [`IBackground`](/slides/python-net/de/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/de/aspose.slides/masterslide/hyperlink_queries/) | Bietet einfachen Zugriff auf enthaltene Hyperlinks.<br/>            Nur lesbar [`IHyperlinkQueries`](/slides/python-net/de/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/de/aspose.slides/masterslide/show_master_shapes/) | Gibt an, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht.<br/>            Für die Masterfolie selbst gibt diese Eigenschaft immer `false` zurück.<br/>            Lese/Schreib **bool**. |
| [`presentation`](/slides/python-net/de/aspose.slides/masterslide/presentation/) | Gibt die IPresentation-Schnittstelle zurück.<br/>            Nur lesbar [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/de/aspose.slides/masterslide/header_footer_manager/) | Gibt den HeaderFooter-Manager der Masterfolie zurück.<br/>            Nur lesbar [`IMasterSlideHeaderFooterManager`](/slides/python-net/de/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/de/aspose.slides/masterslide/title_style/) | Gibt den Stil eines Titels zurück.<br/>            Nur lesbar [`ITextStyle`](/slides/python-net/de/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/de/aspose.slides/masterslide/body_style/) | Gibt den Stil eines Fließtextes zurück.<br/>            Nur lesbar [`ITextStyle`](/slides/python-net/de/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/de/aspose.slides/masterslide/other_style/) | Gibt den Stil eines anderen Textes zurück.<br/>            Nur lesbar [`ITextStyle`](/slides/python-net/de/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/de/aspose.slides/masterslide/layout_slides/) | Gibt die Sammlung der untergeordneten Layoutfolien für diese Masterfolie zurück.<br/>            Nur lesbar [`IMasterLayoutSlideCollection`](/slides/python-net/de/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/de/aspose.slides/masterslide/preserve/) | Bestimmt, ob die zugehörige Masterfolie gelöscht wird, wenn alle Folien, die dieser Masterfolie folgen, gelöscht werden.<br/>            Hinweis: Aspose.Slides entfernt niemals selbst unbenutzte Masterfolien; um unbenutzte Masterfolien tatsächlich zu entfernen, rufen Sie **Aspose.Slides.MasterSlideCollection.RemoveUnused(Syste** auf.<br/>            Lese/Schreib **bool**. |
| [`has_depending_slides`](/slides/python-net/de/aspose.slides/masterslide/has_depending_slides/) | Gibt true zurück, wenn mindestens eine Folie von dieser Masterfolie abhängt.<br/>            Nur lesbar **bool**. |
| [`theme_manager`](/slides/python-net/de/aspose.slides/masterslide/theme_manager/) | Gibt den Theme-Manager zurück.<br/>            Nur lesbar [`IMasterThemeManager`](/slides/python-net/de/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/de/aspose.slides/masterslide/drawing_guides/) | Gibt eine Sammlung von Zeichenhilfen für die Masterfolie zurück.<br/>            Nur lesbar [`IDrawingGuidesCollection`](/slides/python-net/de/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/de/aspose.slides/masterslide/slide/) |  |

## Methoden

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/de/aspose.slides/masterslide/join_portions_with_same_formatting/#) | Fügt Läufe mit gleicher Formatierung in allen Absätzen aller zulässigen Formen zusammen. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/de/aspose.slides/masterslide/join_portions_with_same_formatting/#ishapecollection) | Fügt Läufe mit gleicher Formatierung in allen Absätzen in allen zulässigen Formen zusammen. |
| [`equals(self, slide)`](/slides/python-net/de/aspose.slides/masterslide/equals/#ibaseslide) | Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind.<br/>            Der Rückgabewert wird basierend auf der Struktur der Folie und statischem Inhalt berechnet.<br/>            Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und andere Einstellungen usw. gleich sind. Der Vergleich berücksichtigt keine eindeutigen Bezeichnerwerte, z. B. SlideId, und keinen dynamischen Inhalt, z. B. den aktuellen Datumswert im Datumsplatzhalter. |
| [`create_theme_effective(self)`](/slides/python-net/de/aspose.slides/masterslide/create_theme_effective/#) | Gibt ein effektives Theme für diese Folie zurück. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/de/aspose.slides/masterslide/find_shape_by_alt_text/#str) | Findet das erste Vorkommen einer Form mit dem angegebenen Alternativtext. |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/de/aspose.slides/masterslide/apply_external_theme_to_depending_slides/#str) | Erstellt eine neue Masterfolie basierend auf der aktuellen, wendet ein externes Theme darauf an <br/>            und wendet die erstellte Masterfolie auf alle abhängigen Folien an. |
| [`get_depending_slides(self)`](/slides/python-net/de/aspose.slides/masterslide/get_depending_slides/#) | Gibt ein Array mit allen Folien zurück, die von dieser Masterfolie abhängen. |

### Siehe auch
* Klasse [`BaseSlide`](/slides/python-net/de/aspose.slides/baseslide)
* Klasse [`MasterSlide`](/slides/python-net/de/aspose.slides/masterslide)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)