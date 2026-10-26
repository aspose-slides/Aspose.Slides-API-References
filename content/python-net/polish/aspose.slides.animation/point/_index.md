---
title: Point class
second_title: Aspose.Slides dla Pythona - odniesienie API .NET
description: 
type: docs
url: /pl/aspose.slides.animation/point/
---
## Klasa Point

Reprezentuje punkt animacji.

Typ Point udostępnia następujące członkowie:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pl/aspose.slides.animation/point/__init__/#) | Domyślny konstruktor. |
| [`__init__(self, time, value, formula)`](/slides/python-net/pl/aspose.slides.animation/point/__init__/#float-any-str) | Tworzy punkt animacji z czasem, wartością i formułą. |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`time`](/slides/python-net/pl/aspose.slides.animation/point/time/) | Reprezentuje wartość czasu.<br/>            Odczyt/zapis **float**. |
| [`value`](/slides/python-net/pl/aspose.slides.animation/point/value/) | Reprezentuje wartość punktu.<br/>            Dozwolone typy: bool, ColorFormat, float, int, string.<br/>            Odczyt/zapis **any**. |
| [`formula`](/slides/python-net/pl/aspose.slides.animation/point/formula/) | Formuły w wartościach, atrybutach from, to, by mogą składać się z następujących elementów:<br/>            Standardowe operatory arytmetyczne: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)<br/>            Stałe: ‘pi’ ‘e’<br/>            Operatory warunkowe: ‘abs’, ‘min’, ‘max’, ‘?’ (if)<br/>            Operatory porównania: '==', '>=', '', '!=', '!'<br/>            Operatory trygonometryczne: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’<br/>            Logarytm naturalny ‘ln()’<br/>            Odwołania do właściwości (wspierane właściwości hosta)<br/>            <br/>            na przykład: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"<br/>            Odczyt/zapis **str**. |

### Zobacz także
* moduł [`aspose.slides.animation`](/slides/python-net/pl/aspose.slides.animation)
* biblioteka [`Aspose.Slides`](/slides/python-net)