---
title: RectangleF class
second_title: Aspose.Slides pro Python přes .NET referenci API
description: Ukládá sadu čtyř čísel s plovoucí desetinnou čárkou, které představují polohu a velikost obdélníku.
type: docs
url: /cs/aspose.slides/rectanglef/
net_type: System.Drawing.RectangleF
---
## RectangleF třída

Ukládá sadu čtyř čísel s plovoucí řádovou čárkou, které představují polohu a velikost obdélníku. Kompatibilní s .NET `System.Drawing.RectangleF`.

**Dědičnost:**[`RectangleF`](/slides/python-net/cs/aspose.slides/rectanglef) → [`Rectangle`](/slides/python-net/cs/aspose.slides/rectangle)

Typ RectangleF zveřejňuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self, x=0.0, y=0.0, width=0.0, height=0.0)`](/slides/python-net/cs/aspose.slides/rectanglef/__init__/#float-float-float-float) | Vytvoří obdélník se zadanou polohou a velikostí. |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`x`](/slides/python-net/cs/aspose.slides/rectanglef/x/) | Získá x-souřadnici levého horního rohu tohoto obdélníku.<br/>            Pouze ke čtení **float**. |
| [`y`](/slides/python-net/cs/aspose.slides/rectanglef/y/) | Získá y-souřadnici levého horního rohu tohoto obdélníku.<br/>            Pouze ke čtení **float**. |
| [`width`](/slides/python-net/cs/aspose.slides/rectanglef/width/) | Získá šířku tohoto obdélníku.<br/>            Pouze ke čtení **float**. |
| [`height`](/slides/python-net/cs/aspose.slides/rectanglef/height/) | Získá výšku tohoto obdélníku.<br/>            Pouze ke čtení **float**. |
| [`left`](/slides/python-net/cs/aspose.slides/rectanglef/left/) | Získá x-souřadnici levého okraje tohoto obdélníku. Rovná se `x`.<br/>            Pouze ke čtení **float**. |
| [`top`](/slides/python-net/cs/aspose.slides/rectanglef/top/) | Získá y-souřadnici horního okraje tohoto obdélníku. Rovná se `y`.<br/>            Pouze ke čtení **float**. |
| [`right`](/slides/python-net/cs/aspose.slides/rectanglef/right/) | Získá x-souřadnici, která je součtem `x` a `width` tohoto obdélníku.<br/>            Pouze ke čtení **float**. |
| [`bottom`](/slides/python-net/cs/aspose.slides/rectanglef/bottom/) | Získá y-souřadnici, která je součtem `y` a `height` tohoto obdélníku.<br/>            Pouze ke čtení **float**. |
| [`is_empty`](/slides/python-net/cs/aspose.slides/rectanglef/is_empty/) | Udává, zda všechny číselné vlastnosti tohoto obdélníku mají hodnotu nula.<br/>            Pouze ke čtení **bool**. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/cs/aspose.slides/rectanglef/contains/#float-float) | Určuje, zda je zadaný bod obsažen v tomto obdélníku. |
| [`contains(self, point)`](/slides/python-net/cs/aspose.slides/rectanglef/contains/#pointf) | Určuje, zda je zadaný bod obsažen v tomto obdélníku. |
| [`contains(self, rect)`](/slides/python-net/cs/aspose.slides/rectanglef/contains/#rectanglef) | Určuje, zda je obdélníková oblast reprezentovaná `rect` zcela obsažena v tomto obdélníku. |


### Poznámky

Obdélníky jsou porovnávány podle své polohy a velikosti pomocí `==` a mohou být použity jako klíče slovníků nebo členové množin.


### Viz také
* třída [`Rectangle`](/slides/python-net/cs/aspose.slides/rectangle)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)