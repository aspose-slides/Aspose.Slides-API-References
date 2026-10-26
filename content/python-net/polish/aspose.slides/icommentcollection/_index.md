---
title: ICommentCollection class
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET - odniesienie API
description: 
type: docs
url: /pl/aspose.slides/icommentcollection/
---
## ICommentCollection klasa

Reprezentuje kolekcję komentarzy jednego autora.

Typ ICommentCollection udostępnia następujące elementy:

Zwraca element pod określonym indeksem.
            Tylko do odczytu [`IComment`](/slides/python-net/pl/aspose.slides/icomment).

## Indeksator

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/pl/aspose.slides/icommentcollection/__getitem__/) |  |

## Metody

| Method | Description |
| :- | :- |
| [`to_array(self)`](/slides/python-net/pl/aspose.slides/icommentcollection/to_array/#) | Tworzy i zwraca tablicę ze wszystkimi komentarzami. |
| [`to_array(self, start_index, count)`](/slides/python-net/pl/aspose.slides/icommentcollection/to_array/#int-int) | Tworzy i zwraca tablicę z komentarzami z określonego zakresu. |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/pl/aspose.slides/icommentcollection/add_comment/#str-islide-asposeslidespointf-datetime) | Dodaje nowy komentarz na końcu kolekcji. |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/pl/aspose.slides/icommentcollection/add_modern_comment/#str-islide-ishape-asposeslidespointf-datetime) | Dodaje nowy nowoczesny komentarz na końcu kolekcji. |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/pl/aspose.slides/icommentcollection/insert_comment/#int-str-islide-asposeslidespointf-datetime) | Wstawia nowy komentarz do kolekcji pod określonym indeksem. |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/pl/aspose.slides/icommentcollection/insert_modern_comment/#int-str-islide-ishape-asposeslidespointf-datetime) | Wstawia nowy nowoczesny komentarz do kolekcji pod określonym indeksem. |
| [`remove_at(self, index)`](/slides/python-net/pl/aspose.slides/icommentcollection/remove_at/#int) | Usuwa element pod określonym indeksem w kolekcji. |
| [`remove(self, comment)`](/slides/python-net/pl/aspose.slides/icommentcollection/remove/#icomment) | Usuwa pierwsze wystąpienie określonego komentarza w kolekcji. |
| [`clear(self)`](/slides/python-net/pl/aspose.slides/icommentcollection/clear/#) | Usuwa wszystkie komentarze z kolekcji. |


### Zobacz też
* klasa [`IComment`](/slides/python-net/pl/aspose.slides/icomment)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)