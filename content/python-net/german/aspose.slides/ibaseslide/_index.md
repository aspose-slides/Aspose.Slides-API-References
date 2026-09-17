---
title: IBaseSlide class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ibaseslide/
---
## IBaseSlide Klasse

Stellt gemeinsame Daten für alle Folientypen dar.

Der Typ IBaseSlide stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`shapes`](/slides/python-net/de/aspose.slides/ibaseslide/shapes/) | Gibt die Formen einer Folie zurück.<br/>            Nur lesend [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/de/aspose.slides/ibaseslide/controls/) | Gibt die Sammlung der ActiveX-Steuerelemente einer Folie zurück.<br/>            Nur lesend [`IControlCollection`](/slides/python-net/de/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/de/aspose.slides/ibaseslide/name/) | Gibt den Namen einer Folie zurück oder legt ihn fest.<br/>            Lese/Schreib **str**. |
| [`slide_id`](/slides/python-net/de/aspose.slides/ibaseslide/slide_id/) | Gibt die ID einer Folie zurück.<br/>            Nur lesend **int**. |
| [`custom_data`](/slides/python-net/de/aspose.slides/ibaseslide/custom_data/) | Gibt die benutzerdefinierten Daten der Folie zurück.<br/>            Nur lesend [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/de/aspose.slides/ibaseslide/timeline/) | Gibt das Animationszeitlinien-Objekt zurück.<br/>            Nur lesend [`IAnimationTimeLine`](/slides/python-net/de/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/de/aspose.slides/ibaseslide/slide_show_transition/) | Gibt das TransitionEx-Objekt zurück, das Informationen darüber enthält,<br/>            wie die angegebene Folie während einer Diashow fortschreitet.<br/>            Nur lesend [`ISlideShowTransition`](/slides/python-net/de/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/de/aspose.slides/ibaseslide/background/) | Gibt den Hintergrund der Folie zurück.<br/>            Nur lesend [`IBackground`](/slides/python-net/de/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/de/aspose.slides/ibaseslide/hyperlink_queries/) | Bietet einfachen Zugriff auf enthaltene Hyperlinks.<br/>            Nur lesend [`IHyperlinkQueries`](/slides/python-net/de/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/de/aspose.slides/ibaseslide/show_master_shapes/) | Legt fest, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht.<br/>            Für die Masterfolie selbst gibt dieses Property immer `false` zurück.<br/>            Lese/Schreib **bool**. |
| [`slide`](/slides/python-net/de/aspose.slides/ibaseslide/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides/ibaseslide/presentation/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/de/aspose.slides/ibaseslide/find_shape_by_alt_text/#str) | Findet das erste Vorkommen einer Form mit dem angegebenen Alternativtext. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/de/aspose.slides/ibaseslide/join_portions_with_same_formatting/#) | Verbindet Lauftexte mit gleicher Formatierung in allen Absätzen in allen zulässigen Formen. |
| [`equals(self, slide)`](/slides/python-net/de/aspose.slides/ibaseslide/equals/#ibaseslide) | Ermittelt, ob die beiden IBaseSlide-Instanzen gleich sind.<br/>            Der Rückgabewert wird basierend auf der Struktur und dem statischen Inhalt der Folie berechnet.<br/>            Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und andere Einstellungen usw. gleich sind. Beim Vergleich werden eindeutige Bezeichnerwerte, z. B. SlideId, und dynamische Inhalte, z. B. der aktuelle Datumswert im Datums-Platzhalter, nicht berücksichtigt. |
| [`create_theme_effective(self)`](/slides/python-net/de/aspose.slides/ibaseslide/create_theme_effective/#) |  |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)