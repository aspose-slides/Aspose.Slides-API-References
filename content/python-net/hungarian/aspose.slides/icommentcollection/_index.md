---
title: ICommentCollection class
second_title: Aspose.Slides a Pythonhoz a .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides/icommentcollection/
---
## ICommentCollection osztály

Egy szerző megjegyzéseinek gyűjteményét képviseli.

Az ICommentCollection típus a következő tagokat teszi közzé:

Megkapja a megadott indexű elemet. Csak olvasható [`IComment`](/slides/python-net/hu/aspose.slides/icomment).

## Indexer

| Név | Leírás |
| :- | :- |
| [`[index]`](/slides/python-net/hu/aspose.slides/icommentcollection/__getitem__/) |  |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`to_array(self)`](/slides/python-net/hu/aspose.slides/icommentcollection/to_array/#) | Létrehoz és visszaad egy tömböt az összes megjegyzéssel. |
| [`to_array(self, start_index, count)`](/slides/python-net/hu/aspose.slides/icommentcollection/to_array/#int-int) | Létrehoz és visszaad egy tömböt a megadott tartományban lévő összes megjegyzéssel. |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/hu/aspose.slides/icommentcollection/add_comment/#str-islide-asposepydrawingpointf-datetime) | Új megjegyzést ad a gyűjtemény végéhez. |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/hu/aspose.slides/icommentcollection/add_modern_comment/#str-islide-ishape-asposepydrawingpointf-datetime) | Új modern megjegyzést ad a gyűjtemény végéhez. |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/hu/aspose.slides/icommentcollection/insert_comment/#int-str-islide-asposepydrawingpointf-datetime) | Új megjegyzést szúr be a gyűjteménybe a megadott indexnél. |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/hu/aspose.slides/icommentcollection/insert_modern_comment/#int-str-islide-ishape-asposepydrawingpointf-datetime) | Új modern megjegyzést szúr be a gyűjteménybe a megadott indexnél. |
| [`remove_at(self, index)`](/slides/python-net/hu/aspose.slides/icommentcollection/remove_at/#int) | Eltávolítja a megadott indexű elemet a gyűjteményből. |
| [`remove(self, comment)`](/slides/python-net/hu/aspose.slides/icommentcollection/remove/#icomment) | Eltávolítja a megadott megjegyzés első előfordulását a gyűjteményből. |
| [`clear(self)`](/slides/python-net/hu/aspose.slides/icommentcollection/clear/#) | Eltávolítja az összes megjegyzést a gyűjteményből. |


### Lásd még
* osztály [`IComment`](/slides/python-net/hu/aspose.slides/icomment)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)