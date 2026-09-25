---
title: CommentCollection class
second_title: Aspose.Slides dla Pythona poprzez .NET – referencja API
description: 
type: docs
url: /pl/aspose.slides/commentcollection/
---
## CommentCollection klasa

Reprezentuje kolekcję komentarzy jednego autora.

Typ CommentCollection udostępnia następujące elementy:

Pobiera element pod określonym indeksem.
            Tylko do odczytu [`Comment`](/slides/python-net/pl/aspose.slides/comment).

## Indeksator

| Nazwa | Opis |
| :- | :- |
| [`[index]`](/slides/python-net/pl/aspose.slides/commentcollection/__getitem__/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`to_array(self)`](/slides/python-net/pl/aspose.slides/commentcollection/to_array/#) | Tworzy i zwraca tablicę ze wszystkimi komentarzami. |
| [`to_array(self, start_index, count)`](/slides/python-net/pl/aspose.slides/commentcollection/to_array/#int-int) | Tworzy i zwraca tablicę ze wszystkimi komentarzami z określonego zakresu. |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/pl/aspose.slides/commentcollection/add_comment/#str-islide-asposeslidespointf-datetime) | Dodaje nowy komentarz na końcu kolekcji. |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/pl/aspose.slides/commentcollection/add_modern_comment/#str-islide-ishape-asposeslidespointf-datetime) | Dodaje nowy nowoczesny komentarz na końcu kolekcji. |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/pl/aspose.slides/commentcollection/insert_comment/#int-str-islide-asposeslidespointf-datetime) | Wstawia nowy komentarz do kolekcji pod określonym indeksem. |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/pl/aspose.slides/commentcollection/insert_modern_comment/#int-str-islide-ishape-asposeslidespointf-datetime) | Wstawia nowy nowoczesny komentarz do kolekcji pod określonym indeksem. |
| [`remove_at(self, index)`](/slides/python-net/pl/aspose.slides/commentcollection/remove_at/#int) | Usuwa element pod określonym indeksem w kolekcji. |
| [`remove(self, comment)`](/slides/python-net/pl/aspose.slides/commentcollection/remove/#icomment) | Usuwa pierwsze wystąpienie określonego komentarza w kolekcji. |
| [`clear(self)`](/slides/python-net/pl/aspose.slides/commentcollection/clear/#) | Usuwa wszystkie komentarze z kolekcji. |
| [`find_comment_by_idx(self, idx)`](/slides/python-net/pl/aspose.slides/commentcollection/find_comment_by_idx/#int) | Znajduje komentarz w kolekcji według indeksu. |

### Zobacz także
* klasa [`Comment`](/slides/python-net/pl/aspose.slides/comment)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)