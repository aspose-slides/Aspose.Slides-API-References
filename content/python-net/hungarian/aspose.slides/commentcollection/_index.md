---
title: CommentCollection class
second_title: Aspose.Slides a Python számára a .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides/commentcollection/
---
## CommentCollection osztály

Egy szerző megjegyzéseinek gyűjteményét képviseli.

A CommentCollection típus a következő tagokat teszi közzé:

Lekéri az elemet a megadott indexnél.  
Csak olvasható [`Comment`](/slides/python-net/hu/aspose.slides/comment).

## Indexelő

| Név | Leírás |
| :- | :- |
| [`[index]`](/slides/python-net/hu/aspose.slides/commentcollection/__getitem__/) |  |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`to_array(self)`](/slides/python-net/hu/aspose.slides/commentcollection/to_array/#) | Létrehoz és visszaad egy tömböt az összes megjegyzéssel. |
| [`to_array(self, start_index, count)`](/slides/python-net/hu/aspose.slides/commentcollection/to_array/#int-int) | Létrehoz és visszaad egy tömböt a megadott tartományból származó összes megjegyzéssel. |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/hu/aspose.slides/commentcollection/add_comment/#str-islide-asposeslidespointf-datetime) | Új megjegyzést ad hozzá a gyűjtemény végéhez. |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/hu/aspose.slides/commentcollection/add_modern_comment/#str-islide-ishape-asposeslidespointf-datetime) | Új modern megjegyzést ad hozzá a gyűjtemény végéhez. |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/hu/aspose.slides/commentcollection/insert_comment/#int-str-islide-asposeslidespointf-datetime) | Új megjegyzést szúr be a gyűjteménybe a megadott indexnél. |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/hu/aspose.slides/commentcollection/insert_modern_comment/#int-str-islide-ishape-asposeslidespointf-datetime) | Új modern megjegyzést szúr be a gyűjteménybe a megadott indexnél. |
| [`remove_at(self, index)`](/slides/python-net/hu/aspose.slides/commentcollection/remove_at/#int) | Eltávolítja az elemet a megadott indexnél a gyűjteményből. |
| [`remove(self, comment)`](/slides/python-net/hu/aspose.slides/commentcollection/remove/#icomment) | Eltávolítja a megadott megjegyzés első előfordulását a gyűjteményben. |
| [`clear(self)`](/slides/python-net/hu/aspose.slides/commentcollection/clear/#) | Eltávolítja az összes megjegyzést a gyűjteményből. |
| [`find_comment_by_idx(self, idx)`](/slides/python-net/hu/aspose.slides/commentcollection/find_comment_by_idx/#int) | Megkeresi a megjegyzést a gyűjteményben index szerint. |

### Lásd még
* osztály [`Comment`](/slides/python-net/hu/aspose.slides/comment)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)