---
title: CommentCollection class
second_title: Aspose.Slides for Python via .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides/commentcollection/
---
## CommentCollection osztály

Egy szerző összes megjegyzését tartalmazó gyűjteményt képvisel.

A CommentCollection típus a következő tagokat biztosítja:

Lekéri az elemet a megadott indexen.  
            Csak olvasható [`Comment`](/slides/python-net/hu/aspose.slides/comment).

## Indexelő

| Név | Leírás |
| :- | :- |
| [`[index]`](/slides/python-net/hu/aspose.slides/commentcollection/__getitem__/) |  |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`to_array(self)`](/slides/python-net/hu/aspose.slides/commentcollection/to_array/#) | Létrehozza és visszaad egy tömböt az összes megjegyzéssel. |
| [`to_array(self, start_index, count)`](/slides/python-net/hu/aspose.slides/commentcollection/to_array/#int-int) | Létrehozza és visszaad egy tömböt a megadott tartományban lévő megjegyzésekkel. |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/hu/aspose.slides/commentcollection/add_comment/#str-islide-asposepydrawingpointf-datetime) | Új megjegyzést ad a gyűjtemény végéhez. |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/hu/aspose.slides/commentcollection/add_modern_comment/#str-islide-ishape-asposepydrawingpointf-datetime) | Új modern megjegyzést ad a gyűjtemény végéhez. |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/hu/aspose.slides/commentcollection/insert_comment/#int-str-islide-asposepydrawingpointf-datetime) | Új megjegyzést szúr be a gyűjteménybe a megadott indexnél. |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/hu/aspose.slides/commentcollection/insert_modern_comment/#int-str-islide-ishape-asposepydrawingpointf-datetime) | Új modern megjegyzést szúr be a gyűjteménybe a megadott indexnél. |
| [`remove_at(self, index)`](/slides/python-net/hu/aspose.slides/commentcollection/remove_at/#int) | Eltávolítja az elemet a megadott indexen a gyűjteményből. |
| [`remove(self, comment)`](/slides/python-net/hu/aspose.slides/commentcollection/remove/#icomment) | Eltávolítja a megadott megjegyzés első előfordulását a gyűjteményből. |
| [`clear(self)`](/slides/python-net/hu/aspose.slides/commentcollection/clear/#) | Eltávolítja az összes megjegyzést a gyűjteményből. |
| [`find_comment_by_idx(self, idx)`](/slides/python-net/hu/aspose.slides/commentcollection/find_comment_by_idx/#int) | Megkeresi a megjegyzést a gyűjteményben index alapján. |

### Lásd még
* osztály [`Comment`](/slides/python-net/hu/aspose.slides/comment)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)