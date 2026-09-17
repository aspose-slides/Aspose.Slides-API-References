---
title: ModernComment class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/moderncomment/
---
## ModernComment Klasse

Stellt einen Kommentar auf einer Folie dar.

**Vererbung:**[`ModernComment`](/slides/python-net/de/aspose.slides/moderncomment) → [`Comment`](/slides/python-net/de/aspose.slides/comment)

Der ModernComment-Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`text`](/slides/python-net/de/aspose.slides/moderncomment/text/) | Gibt den Klartext eines Folienkommentars zurück oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`created_time`](/slides/python-net/de/aspose.slides/moderncomment/created_time/) | Gibt die Erstellungszeit eines Kommentars zurück oder legt sie fest.<br/>            Das Setzen dieser Eigenschaft auf **System.DateTime** bedeutet, dass keine Kommentarzeit festgelegt ist.<br/>            Lesen/Schreiben **System.DateTime**. |
| [`slide`](/slides/python-net/de/aspose.slides/moderncomment/slide/) | Gibt die übergeordnete Folie eines Kommentars zurück oder legt sie fest.<br/>            Nur lesbar [`ISlide`](/slides/python-net/de/aspose.slides/islide). |
| [`author`](/slides/python-net/de/aspose.slides/moderncomment/author/) | Gibt den Autor eines Kommentars zurück.<br/>            Nur lesbar [`ICommentAuthor`](/slides/python-net/de/aspose.slides/icommentauthor). |
| [`position`](/slides/python-net/de/aspose.slides/moderncomment/position/) | Gibt die Position eines Kommentars auf einer Folie zurück oder legt sie fest.<br/>            Lesen/Schreiben **aspose.slides.PointF**. |
| [`parent_comment`](/slides/python-net/de/aspose.slides/moderncomment/parent_comment/) | Gibt den übergeordneten Kommentar zurück oder legt ihn fest.<br/>            Lesen/Schreiben [`IComment`](/slides/python-net/de/aspose.slides/icomment). |
| [`shape`](/slides/python-net/de/aspose.slides/moderncomment/shape/) | Gibt eine mit dem Kommentar verknüpfte Form zurück.<br/>            Nur lesbar [`IShape`](/slides/python-net/de/aspose.slides/ishape). |
| [`text_selection_start`](/slides/python-net/de/aspose.slides/moderncomment/text_selection_start/) | Gibt die Startposition der Textauswahl im Textfeld zurück oder legt sie fest, wenn der Kommentar mit einer AutoShape verknüpft ist.<br/>            Lesen/Schreiben **int**. |
| [`text_selection_length`](/slides/python-net/de/aspose.slides/moderncomment/text_selection_length/) | Gibt die Länge der Textauswahl im Textfeld zurück oder legt sie fest, wenn der Kommentar mit einer AutoShape verknüpft ist.<br/>            Lesen/Schreiben **int**. |
| [`status`](/slides/python-net/de/aspose.slides/moderncomment/status/) | Gibt den Status des Kommentars zurück oder legt ihn fest.<br/>            Lesen/Schreiben [`ModernCommentStatus`](/slides/python-net/de/aspose.slides/moderncommentstatus). |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`remove(self)`](/slides/python-net/de/aspose.slides/moderncomment/remove/#) | Entfernt den Kommentar und alle seine Antworten aus der übergeordneten Sammlung. |

### Siehe auch
* Klasse [`Comment`](/slides/python-net/de/aspose.slides/comment)
* Klasse [`ModernComment`](/slides/python-net/de/aspose.slides/moderncomment)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)