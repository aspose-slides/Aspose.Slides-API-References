---
title: RectangleF class
second_title: Aspose.Slides dla Pythona przez .NET – dokumentacja API
description: Przechowuje zestaw czterech liczb zmiennoprzecinkowych, które reprezentują położenie i rozmiar prostokąta.
type: docs
url: /pl/aspose.slides/rectanglef/
net_type: System.Drawing.RectangleF
---
## RectangleF klasa

Przechowuje zestaw czterech liczb zmiennoprzecinkowych, które reprezentują położenie i rozmiar prostokąta. Zgodny z .NET `System.Drawing.RectangleF`.

**Dziedziczenie:**[`RectangleF`](/slides/python-net/pl/aspose.slides/rectanglef) → [`Rectangle`](/slides/python-net/pl/aspose.slides/rectangle)

Typ RectangleF udostępnia następujące człony:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self, x=0.0, y=0.0, width=0.0, height=0.0)`](/slides/python-net/pl/aspose.slides/rectanglef/__init__/#float-float-float-float) | Tworzy prostokąt o określonym położeniu i rozmiarze. |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`x`](/slides/python-net/pl/aspose.slides/rectanglef/x/) | Uzyskuje współrzędną x lewego górnego rogu tego prostokąta.<br/>            Tylko do odczytu **float**. |
| [`y`](/slides/python-net/pl/aspose.slides/rectanglef/y/) | Uzyskuje współrzędną y lewego górnego rogu tego prostokąta.<br/>            Tylko do odczytu **float**. |
| [`width`](/slides/python-net/pl/aspose.slides/rectanglef/width/) | Uzyskuje szerokość tego prostokąta.<br/>            Tylko do odczytu **float**. |
| [`height`](/slides/python-net/pl/aspose.slides/rectanglef/height/) | Uzyskuje wysokość tego prostokąta.<br/>            Tylko do odczytu **float**. |
| [`left`](/slides/python-net/pl/aspose.slides/rectanglef/left/) | Uzyskuje współrzędną x lewej krawędzi tego prostokąta. Równa `x`.<br/>            Tylko do odczytu **float**. |
| [`top`](/slides/python-net/pl/aspose.slides/rectanglef/top/) | Uzyskuje współrzędną y górnej krawędzi tego prostokąta. Równa `y`.<br/>            Tylko do odczytu **float**. |
| [`right`](/slides/python-net/pl/aspose.slides/rectanglef/right/) | Uzyskuje współrzędną x będącą sumą `x` i `width` tego prostokąta.<br/>            Tylko do odczytu **float**. |
| [`bottom`](/slides/python-net/pl/aspose.slides/rectanglef/bottom/) | Uzyskuje współrzędną y będącą sumą `y` i `height` tego prostokąta.<br/>            Tylko do odczytu **float**. |
| [`is_empty`](/slides/python-net/pl/aspose.slides/rectanglef/is_empty/) | Określa, czy wszystkie numeryczne właściwości tego prostokąta mają wartość zero.<br/>            Tylko do odczytu **bool**. |

## Metody

| Metoda | Opis |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/pl/aspose.slides/rectanglef/contains/#float-float) | Określa, czy wskazany punkt znajduje się wewnątrz tego prostokąta. |
| [`contains(self, point)`](/slides/python-net/pl/aspose.slides/rectanglef/contains/#pointf) | Określa, czy wskazany punkt znajduje się wewnątrz tego prostokąta. |
| [`contains(self, rect)`](/slides/python-net/pl/aspose.slides/rectanglef/contains/#rectanglef) | Określa, czy prostokątny obszar reprezentowany przez `rect` jest całkowicie zawarty w tym prostokącie. |

### Uwagi

Prostokąty są porównywane według ich położenia i rozmiaru za pomocą `==` i mogą być używane jako klucze słowników lub elementy zbiorów.

### Zobacz także
* klasa [`Rectangle`](/slides/python-net/pl/aspose.slides/rectangle)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)