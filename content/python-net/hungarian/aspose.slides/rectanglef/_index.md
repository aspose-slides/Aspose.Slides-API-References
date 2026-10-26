---
title: RectangleF class
second_title: Aspose.Slides a Pythonhoz a .NET API referenciája
description: Tárol egy négy lebegőpontos számot tartalmazó halmazt, amely a téglalap helyét és méretét jelöli.
type: docs
url: /hu/aspose.slides/rectanglef/
net_type: System.Drawing.RectangleF
---
## RectangleF osztály

Tárol egy négy lebegőpontos számot tartalmazó halmazt, amely egy téglalap helyét és méretét jelöli. Kompatibilis a .NET `System.Drawing.RectangleF`-vel.

**Öröklés:**[`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef) → [`Rectangle`](/slides/python-net/hu/aspose.slides/rectangle)

A RectangleF típus a következő tagokat tartalmazza:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self, x=0.0, y=0.0, width=0.0, height=0.0)`](/slides/python-net/hu/aspose.slides/rectanglef/__init__/#float-float-float-float) | Létrehoz egy téglalapot a megadott helyzettel és mérettel. |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`x`](/slides/python-net/hu/aspose.slides/rectanglef/x/) | A téglalap bal felső sarkának x-koordinátáját adja vissza.<br/>            Csak olvasható **float**. |
| [`y`](/slides/python-net/hu/aspose.slides/rectanglef/y/) | A téglalap bal felső sarkának y-koordinátáját adja vissza.<br/>            Csak olvasható **float**. |
| [`width`](/slides/python-net/hu/aspose.slides/rectanglef/width/) | A téglalap szélességét adja vissza.<br/>            Csak olvasható **float**. |
| [`height`](/slides/python-net/hu/aspose.slides/rectanglef/height/) | A téglalap magasságát adja vissza.<br/>            Csak olvasható **float**. |
| [`left`](/slides/python-net/hu/aspose.slides/rectanglef/left/) | A téglalap bal oldali élének x-koordinátáját adja vissza. Egyenlő `x`-szel.<br/>            Csak olvasható **float**. |
| [`top`](/slides/python-net/hu/aspose.slides/rectanglef/top/) | A téglalap felső élének y-koordinátáját adja vissza. Egyenlő `y`-nal.<br/>            Csak olvasható **float**. |
| [`right`](/slides/python-net/hu/aspose.slides/rectanglef/right/) | A téglalap x-koordinátáját adja vissza, amely `x` és `width` összegével egyenlő.<br/>            Csak olvasható **float**. |
| [`bottom`](/slides/python-net/hu/aspose.slides/rectanglef/bottom/) | A téglalap y-koordinátáját adja vissza, amely `y` és `height` összegével egyenlő.<br/>            Csak olvasható **float**. |
| [`is_empty`](/slides/python-net/hu/aspose.slides/rectanglef/is_empty/) | Megadja, hogy a téglalap összes numerikus tulajdonsága nulla értékű-e.<br/>            Csak olvasható **bool**. |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/hu/aspose.slides/rectanglef/contains/#float-float) | Megállapítja, hogy a megadott pont benne van-e ebben a téglalapban. |
| [`contains(self, point)`](/slides/python-net/hu/aspose.slides/rectanglef/contains/#pointf) | Megállapítja, hogy a megadott pont benne van-e ebben a téglalapban. |
| [`contains(self, rect)`](/slides/python-net/hu/aspose.slides/rectanglef/contains/#rectanglef) | Megállapítja, hogy a `rect` által képviselt téglalap terület teljes egészében benne van-e ebben a téglalapban. |

### Megjegyzés

A téglalapok a helyzetük és méretük alapján hasonlíthatók össze `==`-vel, és használhatók szótárkulcsként vagy halmazelemként.

### Lásd még
* osztály [`Rectangle`](/slides/python-net/hu/aspose.slides/rectangle)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)