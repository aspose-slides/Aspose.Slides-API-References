---
title: ICommentCollection class
second_title: Aspose.Slides Pythonhoz .NET API Referencia
description: 
type: docs
url: /hu/aspose.slides/icommentcollection/
---
## ICommentCollection osztály

Egy adott szerző megjegyzéseinek gyűjteményét képviseli.

Az ICommentCollection típus a következő tagokat teszi közzé:

Visszaadja a megadott indexű elemet.  
Csak olvasható [`IComment`](/slides/python-net/hu/aspose.slides/icomment).

## Indexelő

| Név | Leírás |
| :- | :- |
| [`[index]`](/slides/python-net/hu/aspose.slides/icommentcollection/__getitem__/) |  |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`to_array(self)`](/slides/python-net/hu/aspose.slides/icommentcollection/to_array/#) | Létrehozza és visszaadja az összes megjegyzésből álló tömböt. |
| [`to_array(self, start_index, count)`](/slides/python-net/hu/aspose.slides/icommentcollection/to_array/#int-int) | Létrehozza és visszaadja a megadott tartományból származó megjegyzések tömbjét. |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/hu/aspose.slides/icommentcollection/add_comment/#str-islide-asposeslidespointf-datetime) | Új megjegyzést ad a gyűjtemény végéhez. |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/hu/aspose.slides/icommentcollection/add_modern_comment/#str-islide-ishape-asposeslidespointf-datetime) | Új modern megjegyzést ad a gyűjtemény végéhez. |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/hu/aspose.slides/icommentcollection/insert_comment/#int-str-islide-asposeslidespointf-datetime) | Új megjegyzést szúr be a gyűjteménybe a megadott indexnél. |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/hu/aspose.slides/icommentcollection/insert_modern_comment/#int-str-islide-ishape-asposeslidespointf-datetime) | Új modern megjegyzést szúr be a gyűjteménybe a megadott indexnél. |
| [`remove_at(self, index)`](/slides/python-net/hu/aspose.slides/icommentcollection/remove_at/#int) | Eltávolítja a megadott indexű elemet a gyűjteményből. |
| [`remove(self, comment)`](/slides/python-net/hu/aspose.slides/icommentcollection/remove/#icomment) | Eltávolítja a megadott megjegyzés első előfordulását a gyűjteményből. |
| [`clear(self)`](/slides/python-net/hu/aspose.slides/icommentcollection/clear/#) | Eltávolítja az összes megjegyzést a gyűjteményből. |

### Lásd még
* osztály [`IComment`](/slides/python-net/hu/aspose.slides/icomment)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)