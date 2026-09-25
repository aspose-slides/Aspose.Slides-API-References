---
title: Rectangle class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: Ukládá sadu čtyř celých čísel, která představují umístění a velikost obdélníku.
type: docs
url: /cs/aspose.slides/rectangle/
net_type: System.Drawing.Rectangle
---
## Rectangle třída

Ukládá sadu čtyř celých čísel, která představují umístění a velikost obdélníku. Kompatibilní s .NET `System.Drawing.Rectangle`.

Typ Rectangle poskytuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self, x=0, y=0, width=0, height=0)`](/slides/python-net/cs/aspose.slides/rectangle/__init__/#int-int-int-int) | Vytvoří obdélník se zadaným umístěním a velikostí. Hodnoty typu float jsou zkráceny na celá čísla. |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`x`](/slides/python-net/cs/aspose.slides/rectangle/x/) | Získá x-souřadnici levého horního rohu tohoto obdélníku.<br/>            Read-only **int**. |
| [`y`](/slides/python-net/cs/aspose.slides/rectangle/y/) | Získá y-souřadnici levého horního rohu tohoto obdélníku.<br/>            Read-only **int**. |
| [`width`](/slides/python-net/cs/aspose.slides/rectangle/width/) | Získá šířku tohoto obdélníku.<br/>            Read-only **int**. |
| [`height`](/slides/python-net/cs/aspose.slides/rectangle/height/) | Získá výšku tohoto obdélníku.<br/>            Read-only **int**. |
| [`left`](/slides/python-net/cs/aspose.slides/rectangle/left/) | Získá x-souřadnici levého okraje tohoto obdélníku. Je rovna `x`.<br/>            Read-only **int**. |
| [`top`](/slides/python-net/cs/aspose.slides/rectangle/top/) | Získá y-souřadnici horního okraje tohoto obdélníku. Je rovna `y`.<br/>            Read-only **int**. |
| [`right`](/slides/python-net/cs/aspose.slides/rectangle/right/) | Získá x-souřadnici, která je součtem `x` a `width` tohoto obdélníku.<br/>            Read-only **int**. |
| [`bottom`](/slides/python-net/cs/aspose.slides/rectangle/bottom/) | Získá y-souřadnici, která je součtem `y` a `height` tohoto obdélníku.<br/>            Read-only **int**. |
| [`is_empty`](/slides/python-net/cs/aspose.slides/rectangle/is_empty/) | Určuje, zda všechny číselné vlastnosti tohoto obdélníku mají hodnotu nula.<br/>            Read-only **bool**. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/cs/aspose.slides/rectangle/contains/#int-int) | Určuje, zda zadaný bod je obsažen v tomto obdélníku. |
| [`contains(self, point)`](/slides/python-net/cs/aspose.slides/rectangle/contains/#point) | Určuje, zda zadaný bod je obsažen v tomto obdélníku. |
| [`contains(self, rect)`](/slides/python-net/cs/aspose.slides/rectangle/contains/#rectangle) | Určuje, zda je obdélníkový region reprezentovaný `rect` zcela obsažen v tomto obdélníku. |

### Poznámky

Obdélníky jsou porovnávány podle jejich umístění a velikosti pomocí `==` a mohou být použity jako klíče slovníků nebo jako členové množin.

### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)