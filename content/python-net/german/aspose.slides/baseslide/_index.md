---
title: BaseSlide class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/baseslide/
---
## BaseSlide Klasse

Stellt gemeinsame Daten für alle Folientypen bereit.

Der BaseSlide-Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/de/aspose.slides/baseslide/shapes/) | Gibt die Formen einer Folie zurück.<br/>            Nur lesbar [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/de/aspose.slides/baseslide/controls/) | Gibt die Sammlung von ActiveX-Steuerelementen einer Folie zurück.<br/>            Nur lesbar [`IControlCollection`](/slides/python-net/de/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/de/aspose.slides/baseslide/name/) | Gibt den Namen einer Folie zurück oder setzt ihn.<br/>            Lesen/Schreiben **str**. |
| [`slide_id`](/slides/python-net/de/aspose.slides/baseslide/slide_id/) | Gibt die ID einer Folie zurück.<br/>            Nur lesbar **int**. |
| [`custom_data`](/slides/python-net/de/aspose.slides/baseslide/custom_data/) | Gibt die benutzerdefinierten Daten der Folie zurück.<br/>            Nur lesbar [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/de/aspose.slides/baseslide/timeline/) | Gibt das Animationszeitlinien-Objekt zurück.<br/>            Nur lesbar [`IAnimationTimeLine`](/slides/python-net/de/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/de/aspose.slides/baseslide/slide_show_transition/) | Gibt das Transition-Objekt zurück, das Informationen darüber enthält,<br/>            wie die angegebene Folie während einer Bildschirmpräsentation fortschreitet.<br/>            Nur lesbar [`ISlideShowTransition`](/slides/python-net/de/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/de/aspose.slides/baseslide/background/) | Gibt den Folienhintergrund zurück.<br/>            Nur lesbar [`IBackground`](/slides/python-net/de/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/de/aspose.slides/baseslide/hyperlink_queries/) | Bietet einfachen Zugriff auf enthaltene Hyperlinks.<br/>            Nur lesbar [`IHyperlinkQueries`](/slides/python-net/de/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/de/aspose.slides/baseslide/show_master_shapes/) | Gibt an, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht.<br/>            Für die Masterfolie selbst gibt diese Eigenschaft immer `false` zurück.<br/>            Lesen/Schreiben **bool**. |
| [`presentation`](/slides/python-net/de/aspose.slides/baseslide/presentation/) | Gibt das IPresentation-Interface zurück.<br/>            Nur lesbar [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |
| [`slide`](/slides/python-net/de/aspose.slides/baseslide/slide/) |  |

## Methoden

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/de/aspose.slides/baseslide/join_portions_with_same_formatting/#) | Verbindet Laufabschnitte mit gleicher Formatierung in allen Absätzen aller zulässigen Formen. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/de/aspose.slides/baseslide/join_portions_with_same_formatting/#ishapecollection) | Verbindet Laufabschnitte mit gleicher Formatierung in allen Absätzen aller zulässigen Formen. |
| [`equals(self, slide)`](/slides/python-net/de/aspose.slides/baseslide/equals/#ibaseslide) | Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind.<br/>            Der Rückgabewert wird basierend auf der Struktur und dem statischen Inhalt der Folie berechnet.<br/>            Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und andere Einstellungen usw. gleich sind. Der Vergleich berücksichtigt keine eindeutigen Bezeichnerwerte, z. B. SlideId, und keine dynamischen Inhalte, z. B. aktuellen Datumswert im Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/de/aspose.slides/baseslide/create_theme_effective/#) | Gibt ein effektives Theme für diese Folie zurück. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/de/aspose.slides/baseslide/find_shape_by_alt_text/#str) | Findet das erste Vorkommen einer Form mit dem angegebenen Alternativtext. |


### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)