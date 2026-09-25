---
title: ModernComment class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/moderncomment/
---
## ModernComment Klasse

Stellt einen Kommentar auf einer Folie dar.

**Inheritance:**[`ModernComment`](/slides/python-net/de/aspose.slides/moderncomment) → [`Comment`](/slides/python-net/de/aspose.slides/comment)

Der Typ ModernComment stellt die folgenden Member bereit:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`text`](/slides/python-net/de/aspose.slides/moderncomment/text/) | Gibt den Klartext eines Folienkommentars zurück oder setzt ihn.<br/>            Lesen/Schreiben **str**. |
| [`created_time`](/slides/python-net/de/aspose.slides/moderncomment/created_time/) | Gibt die Zeit der Erstellung eines Kommentars zurück oder setzt sie.<br/>            Das Setzen dieser Eigenschaft auf **System.DateTime** bedeutet, dass keine Kommentarzeit festgelegt ist.<br/>            Lesen/Schreiben **System.DateTime**. |
| [`slide`](/slides/python-net/de/aspose.slides/moderncomment/slide/) | Gibt die übergeordnete Folie eines Kommentars zurück oder setzt sie.<br/>            Nur lesen [`ISlide`](/slides/python-net/de/aspose.slides/islide). |
| [`author`](/slides/python-net/de/aspose.slides/moderncomment/author/) | Gibt den Autor eines Kommentars zurück.<br/>            Nur lesen [`ICommentAuthor`](/slides/python-net/de/aspose.slides/icommentauthor). |
| [`position`](/slides/python-net/de/aspose.slides/moderncomment/position/) | Gibt die Position eines Kommentars auf einer Folie zurück oder setzt sie.<br/>            Lesen/Schreiben [`PointF`](/slides/python-net/de/aspose.slides/pointf). |
| [`parent_comment`](/slides/python-net/de/aspose.slides/moderncomment/parent_comment/) | Gibt den übergeordneten Kommentar zurück oder setzt ihn.<br/>            Lesen/Schreiben [`IComment`](/slides/python-net/de/aspose.slides/icomment). |
| [`shape`](/slides/python-net/de/aspose.slides/moderncomment/shape/) | Gibt eine mit dem Kommentar verbundene Form zurück.<br/>            Nur lesen [`IShape`](/slides/python-net/de/aspose.slides/ishape). |
| [`text_selection_start`](/slides/python-net/de/aspose.slides/moderncomment/text_selection_start/) | Gibt die Startposition der Textauswahl im Textfeld zurück oder setzt sie, wenn der Kommentar mit einer AutoShape verknüpft ist.<br/>            Lesen/Schreiben **int**. |
| [`text_selection_length`](/slides/python-net/de/aspose.slides/moderncomment/text_selection_length/) | Gibt die Länge der Textauswahl im Textfeld zurück oder setzt sie, wenn der Kommentar mit einer AutoShape verknüpft ist.<br/>            Lesen/Schreiben **int**. |
| [`status`](/slides/python-net/de/aspose.slides/moderncomment/status/) | Gibt den Status des Kommentars zurück oder setzt ihn.<br/>            Lesen/Schreiben [`ModernCommentStatus`](/slides/python-net/de/aspose.slides/moderncommentstatus). |

## Methoden

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/de/aspose.slides/moderncomment/remove/#) | Entfernt den Kommentar und alle seine Antworten aus der übergeordneten Sammlung. |

### Siehe auch
* Klasse [`Comment`](/slides/python-net/de/aspose.slides/comment)
* Klasse [`ModernComment`](/slides/python-net/de/aspose.slides/moderncomment)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)