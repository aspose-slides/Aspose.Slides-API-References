---
title: Point class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description:
type: docs
url: /cs/aspose.slides.animation/point/
---
## Třída Point

Reprezentuje animační bod.

Typ Point obsahuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/cs/aspose.slides.animation/point/__init__/#) | Výchozí konstruktor. |
| [`__init__(self, time, value, formula)`](/slides/python-net/cs/aspose.slides.animation/point/__init__/#float-any-str) | Vytvoří animační bod s časem, hodnotou a vzorcem. |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`time`](/slides/python-net/cs/aspose.slides.animation/point/time/) | Zastupuje časovou hodnotu.<br/>            Čtení/Zápis **float**. |
| [`value`](/slides/python-net/cs/aspose.slides.animation/point/value/) | Zastupuje hodnotu bodu.<br/>            Pouze: bool, ColorFormat, float, int, string.<br/>            Čtení/Zápis **any**. |
| [`formula`](/slides/python-net/cs/aspose.slides.animation/point/formula/) | Vzorce v hodnotách, atributy from, to, by mohou být složeny z následujících:<br/>            Standardní aritmetické operátory: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)<br/>            Konstanty: ‘pi’ ‘e’<br/>            Podmínkové operátory: ‘abs’, ‘min’, ‘max’, ‘?’ (if)<br/>            Porovnávací operátory: '==', '>=', '', '!=', '!'<br/>            Trigonometrické operátory: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’<br/>            Přirozený logaritmus ‘ln()’<br/>            Odkazy na vlastnosti (vlastnosti podporované hostitelem)<br/><br/>            například: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"<br/>            Čtení/Zápis **str**. |

### Viz také
* modul [`aspose.slides.animation`](/slides/python-net/cs/aspose.slides.animation)
* knihovna [`Aspose.Slides`](/slides/python-net)