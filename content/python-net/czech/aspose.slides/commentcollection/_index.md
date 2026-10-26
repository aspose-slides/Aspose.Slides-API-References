---
title: CommentCollection class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/commentcollection/
---
## CommentCollection třída

Reprezentuje kolekci komentářů od jednoho autora.

Typ CommentCollection zpřístupňuje následující členy:

Získá prvek na zadaném indexu.  
Pouze pro čtení [`Comment`](/slides/python-net/cs/aspose.slides/comment).

## Indexér

| Název | Popis |
| :- | :- |
| [`[index]`](/slides/python-net/cs/aspose.slides/commentcollection/__getitem__/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`to_array(self)`](/slides/python-net/cs/aspose.slides/commentcollection/to_array/#) | Vytvoří a vrátí pole se všemi komentáři. |
| [`to_array(self, start_index, count)`](/slides/python-net/cs/aspose.slides/commentcollection/to_array/#int-int) | Vytvoří a vrátí pole se všemi komentáři ze zadaného rozsahu. |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/cs/aspose.slides/commentcollection/add_comment/#str-islide-asposeslidespointf-datetime) | Přidá nový komentář na konec kolekce. |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/cs/aspose.slides/commentcollection/add_modern_comment/#str-islide-ishape-asposeslidespointf-datetime) | Přidá nový moderní komentář na konec kolekce. |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/cs/aspose.slides/commentcollection/insert_comment/#int-str-islide-asposeslidespointf-datetime) | Vloží nový komentář do kolekce na zadaném indexu. |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/cs/aspose.slides/commentcollection/insert_modern_comment/#int-str-islide-ishape-asposeslidespointf-datetime) | Vloží nový moderní komentář do kolekce na zadaném indexu. |
| [`remove_at(self, index)`](/slides/python-net/cs/aspose.slides/commentcollection/remove_at/#int) | Odebere prvek na zadaném indexu v kolekci. |
| [`remove(self, comment)`](/slides/python-net/cs/aspose.slides/commentcollection/remove/#icomment) | Odebere první výskyt zadaného komentáře v kolekci. |
| [`clear(self)`](/slides/python-net/cs/aspose.slides/commentcollection/clear/#) | Odebere všechny komentáře z kolekce. |
| [`find_comment_by_idx(self, idx)`](/slides/python-net/cs/aspose.slides/commentcollection/find_comment_by_idx/#int) | Vyhledá komentář v kolekci podle indexu. |


### Viz také
* třída [`Comment`](/slides/python-net/cs/aspose.slides/comment)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)