---
title: CommentCollection class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/commentcollection/
---
## CommentCollection Klasse

Stellt eine Sammlung von Kommentaren eines Autors dar.

Der Typ CommentCollection stellt die folgenden Mitglieder bereit:

Ruft das Element am angegebenen Index ab.
            Nur lesbar [`Comment`](/slides/python-net/de/aspose.slides/comment).

## Indexer

| Name | Beschreibung |
| :- | :- |
| [`[index]`](/slides/python-net/de/aspose.slides/commentcollection/__getitem__/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`to_array(self)`](/slides/python-net/de/aspose.slides/commentcollection/to_array/#) | Erstellt und gibt ein Array mit allen Kommentaren zurück. |
| [`to_array(self, start_index, count)`](/slides/python-net/de/aspose.slides/commentcollection/to_array/#int-int) | Erstellt und gibt ein Array mit allen Kommentaren aus dem angegebenen Bereich zurück. |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/de/aspose.slides/commentcollection/add_comment/#str-islide-asposeslidespointf-datetime) | Fügt einen neuen Kommentar am Ende einer Sammlung hinzu. |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/de/aspose.slides/commentcollection/add_modern_comment/#str-islide-ishape-asposeslidespointf-datetime) | Fügt einen neuen modernen Kommentar am Ende einer Sammlung hinzu. |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/de/aspose.slides/commentcollection/insert_comment/#int-str-islide-asposeslidespointf-datetime) | Fügt einen neuen Kommentar an dem angegebenen Index in die Sammlung ein. |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/de/aspose.slides/commentcollection/insert_modern_comment/#int-str-islide-ishape-asposeslidespointf-datetime) | Fügt einen neuen modernen Kommentar an dem angegebenen Index in die Sammlung ein. |
| [`remove_at(self, index)`](/slides/python-net/de/aspose.slides/commentcollection/remove_at/#int) | Entfernt das Element am angegebenen Index in einer Sammlung. |
| [`remove(self, comment)`](/slides/python-net/de/aspose.slides/commentcollection/remove/#icomment) | Entfernt das erste Vorkommen des angegebenen Kommentars in einer Sammlung. |
| [`clear(self)`](/slides/python-net/de/aspose.slides/commentcollection/clear/#) | Entfernt alle Kommentare aus einer Sammlung. |
| [`find_comment_by_idx(self, idx)`](/slides/python-net/de/aspose.slides/commentcollection/find_comment_by_idx/#int) | Findet einen Kommentar in der Sammlung nach Index. |


### Siehe auch
* Klasse [`Comment`](/slides/python-net/de/aspose.slides/comment)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)