---
title: MathParagraph class
second_title: Aspose.Slides a Pythonhoz a .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathparagraph/
---
## MathParagraph osztály

Matematikai bekezdés, amely matematikai blokkok (IMathBlock) tárolóját képezi

A MathParagraph típus a következő tagokat teszi közzé:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathparagraph/__init__/#) | Új példányt hoz létre a MathParagraph osztályból. |
| [`__init__(self, math_block)`](/slides/python-net/hu/aspose.slides.mathtext/mathparagraph/__init__/#imathblock) | Új példányt hoz létre a MathParagraph osztályból. |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`justification`](/slides/python-net/hu/aspose.slides.mathtext/mathparagraph/justification/) | Bekezdés igazítása <br/>            Alapértelmezett érték: CenteredAsGroup |
| [`count`](/slides/python-net/hu/aspose.slides.mathtext/mathparagraph/count/) | Lekéri a gyűjteményben ténylegesen tárolt elemek számát.<br/>            Csak olvasható **int**. |

Lekéri a megadott indexű elemet.
            Csak olvasható [`IMathBlock`](/slides/python-net/hu/aspose.slides.mathtext/imathblock).

## Indexelő

| Név | Leírás |
| :- | :- |
| [`[index]`](/slides/python-net/hu/aspose.slides.mathtext/mathparagraph/__getitem__/) | A lekérendő elem nulla alapú indexe |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`clear(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathparagraph/clear/#) | Eltávolítja az összes elemet a gyűjteményből. |
| [`add(self, math_block)`](/slides/python-net/hu/aspose.slides.mathtext/mathparagraph/add/#imathblock) | Az IMathBlock-ot hozzáadja a gyűjtemény végéhez. |
| [`remove(self, math_block)`](/slides/python-net/hu/aspose.slides.mathtext/mathparagraph/remove/#imathblock) | Eltávolítja egy adott objektum első előfordulását a gyűjteményből/>. |
| [`contains(self, math_block)`](/slides/python-net/hu/aspose.slides.mathtext/mathparagraph/contains/#imathblock) | Megállapítja, hogy a gyűjtemény tartalmaz-e egy adott értéket. |
| [`index_of(self, math_block)`](/slides/python-net/hu/aspose.slides.mathtext/mathparagraph/index_of/#imathblock) | Megállapítja egy adott IMathBlock indexét a gyűjteményben. |
| [`insert(self, index, math_block)`](/slides/python-net/hu/aspose.slides.mathtext/mathparagraph/insert/#int-imathblock) | Beszúrja az IMathBlock-ot a gyűjteménybe a megadott indexnél. |
| [`remove_at(self, index)`](/slides/python-net/hu/aspose.slides.mathtext/mathparagraph/remove_at/#int) | Eltávolít egy elemet a gyűjtemény megadott indexén. |
| [`write_as_math_ml(self, stream)`](/slides/python-net/hu/aspose.slides.mathtext/mathparagraph/write_as_math_ml/#iorawiobase) | Elmenti ennek [`MathParagraph`](/slides/python-net/hu/aspose.slides.mathtext/mathparagraph) tartalmát MathML formátumban |
| [`to_latex(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathparagraph/to_latex/#) | Lekéri a matematikai egyenletet LaTeX formátumban |


### Lásd még
* osztály [`IMathBlock`](/slides/python-net/hu/aspose.slides.mathtext/imathblock)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)