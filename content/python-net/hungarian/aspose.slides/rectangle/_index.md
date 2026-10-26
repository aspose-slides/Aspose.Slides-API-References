---
title: Rectangle class
second_title: Aspose.Slides a Pythonhoz .NET API hivatkozás
description: Tárol egy négy egész számot, amelyek a téglalap helyét és méretét ábrázolják.
type: docs
url: /hu/aspose.slides/rectangle/
net_type: System.Drawing.Rectangle
---
## Rectangle osztály

Egy négy egész számot tartalmaz, amely a téglalap helyét és méretét reprezentálja. Kompatibilis a .NET `System.Drawing.Rectangle` osztállyal.

A Rectangle típus a következő tagokat teszi közzé:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self, x=0, y=0, width=0, height=0)`](/slides/python-net/hu/aspose.slides/rectangle/__init__/#int-int-int-int) | Létrehoz egy téglalapot a megadott helyzettel és mérettel. A lebegőpontos értékeket egész számokra csonkolja. |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`x`](/slides/python-net/hu/aspose.slides/rectangle/x/) | Lekéri ennek a téglalapnak a bal felső sarok x-koordinátáját.<br/>            Csak olvasható **int**. |
| [`y`](/slides/python-net/hu/aspose.slides/rectangle/y/) | Lekéri ennek a téglalapnak a bal felső sarok y-koordinátáját.<br/>            Csak olvasható **int**. |
| [`width`](/slides/python-net/hu/aspose.slides/rectangle/width/) | Lekéri ennek a téglalap szélességét.<br/>            Csak olvasható **int**. |
| [`height`](/slides/python-net/hu/aspose.slides/rectangle/height/) | Lekéri ennek a téglalap magasságát.<br/>            Csak olvasható **int**. |
| [`left`](/slides/python-net/hu/aspose.slides/rectangle/left/) | Lekéri ennek a téglalap bal szélének x-koordinátáját. Egyenlő `x`-szel.<br/>            Csak olvasható **int**. |
| [`top`](/slides/python-net/hu/aspose.slides/rectangle/top/) | Lekéri ennek a téglalap felső szélének y-koordinátáját. Egyenlő `y`-szel.<br/>            Csak olvasható **int**. |
| [`right`](/slides/python-net/hu/aspose.slides/rectangle/right/) | Lekéri ennek a téglalap `x` és `width` összegeként számított x-koordinátát.<br/>            Csak olvasható **int**. |
| [`bottom`](/slides/python-net/hu/aspose.slides/rectangle/bottom/) | Lekéri ennek a téglalap `y` és `height` összegeként számított y-koordinátát.<br/>            Csak olvasható **int**. |
| [`is_empty`](/slides/python-net/hu/aspose.slides/rectangle/is_empty/) | Megadja, hogy a téglalap összes numerikus tulajdonsága null értékkel rendelkezik-e.<br/>            Csak olvasható **bool**. |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/hu/aspose.slides/rectangle/contains/#int-int) | Megállapítja, hogy a megadott pont ebben a téglalapban van-e. |
| [`contains(self, point)`](/slides/python-net/hu/aspose.slides/rectangle/contains/#point) | Megállapítja, hogy a megadott pont ebben a téglalapban van-e. |
| [`contains(self, rect)`](/slides/python-net/hu/aspose.slides/rectangle/contains/#rectangle) | Megállapítja, hogy a `rect` által reprezentált téglalaprész teljes egészében ebben a téglalapban van-e. |


### Megjegyzések

A téglalapok helyzetük és méretük alapján hasonlíthatók össze `==` operátorral, és használhatók szótárkulcsként vagy halmazelemként.


### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)