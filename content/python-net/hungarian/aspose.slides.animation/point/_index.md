---
title: Point class
second_title: Aspose.Slides Pythonhoz a .NET API hivatkozásával
description: 
type: docs
url: /hu/aspose.slides.animation/point/
---
## Point osztály

Az animációs pontot ábrázolja.

A Point típus a következő tagokat teszi elérhetővé:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides.animation/point/__init__/#) | Alapértelmezett konstruktor. |
| [`__init__(self, time, value, formula)`](/slides/python-net/hu/aspose.slides.animation/point/__init__/#float-any-str) | Animációs pont létrehozása idővel, értékkel és képlettel. |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`time`](/slides/python-net/hu/aspose.slides.animation/point/time/) | Ábrázolja az időértéket.<br/>Olvasás/írás **float**. |
| [`value`](/slides/python-net/hu/aspose.slides.animation/point/value/) | Ábrázolja a pont értékét.<br/>Csak: bool, ColorFormat, float, int, string.<br/>Olvasás/írás **any**. |
| [`formula`](/slides/python-net/hu/aspose.slides.animation/point/formula/) | A formulák az értékekben, from, to, by attribútumokban a következőkből állhatnak:<br/>Standard aritmetikai operátorok: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)<br/>Állandók: ‘pi’ ‘e’<br/>Feltételes operátorok: ‘abs’, ‘min’, ‘max’, ‘?’ (if)<br/>Összehasonlító operátorok: '==', '>=', '', '!=', '!'<br/>Trigonometrikus operátorok: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’<br/>Természetes logaritmus ‘ln()’<br/>Tulajdonság hivatkozások (host támogatott tulajdonságai)<br/><br/>például: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"<br/>Olvasás/írás **str**. |

### Lásd még
* modul [`aspose.slides.animation`](/slides/python-net/hu/aspose.slides.animation)
* könyvtár [`Aspose.Slides`](/slides/python-net)