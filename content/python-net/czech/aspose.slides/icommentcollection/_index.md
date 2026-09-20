---
title: ICommentCollection class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/icommentcollection/
---
## ICommentCollection třída

Reprezentuje kolekci komentářů od jednoho autora.

Typ ICommentCollection vystavuje následující členy:

Získá prvek na zadaném indexu.
            Pouze pro čtení [`IComment`](/slides/python-net/cs/aspose.slides/icomment).

## Indexer

| Název | Popis |
| :- | :- |
| [`[index]`](/slides/python-net/cs/aspose.slides/icommentcollection/__getitem__/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`to_array(self)`](/slides/python-net/cs/aspose.slides/icommentcollection/to_array/#) | Vytvoří a vrátí pole se všemi komentáři. |
| [`to_array(self, start_index, count)`](/slides/python-net/cs/aspose.slides/icommentcollection/to_array/#int-int) | Vytvoří a vrátí pole se všemi komentáři ze zadaného rozsahu. |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/cs/aspose.slides/icommentcollection/add_comment/#str-islide-asposepydrawingpointf-datetime) | Přidá nový komentář na konec kolekce. |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/cs/aspose.slides/icommentcollection/add_modern_comment/#str-islide-ishape-asposepydrawingpointf-datetime) | Přidá nový moderní komentář na konec kolekce. |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/cs/aspose.slides/icommentcollection/insert_comment/#int-str-islide-asposepydrawingpointf-datetime) | Vloží nový komentář do kolekce na zadaném indexu. |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/cs/aspose.slides/icommentcollection/insert_modern_comment/#int-str-islide-ishape-asposepydrawingpointf-datetime) | Vloží nový moderní komentář do kolekce na zadaném indexu. |
| [`remove_at(self, index)`](/slides/python-net/cs/aspose.slides/icommentcollection/remove_at/#int) | Odstraní prvek na zadaném indexu v kolekci. |
| [`remove(self, comment)`](/slides/python-net/cs/aspose.slides/icommentcollection/remove/#icomment) | Odstraní první výskyt zadaného komentáře v kolekci. |
| [`clear(self)`](/slides/python-net/cs/aspose.slides/icommentcollection/clear/#) | Odstraní všechny komentáře z kolekce. |


### Viz také
* třída [`IComment`](/slides/python-net/cs/aspose.slides/icomment)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)