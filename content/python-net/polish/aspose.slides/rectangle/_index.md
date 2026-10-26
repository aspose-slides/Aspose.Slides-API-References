---
title: Rectangle class
second_title: Aspose.Slides dla Pythona poprzez .NET Referencja API
description: Przechowuje zestaw czterech liczb całkowitych, które reprezentują położenie i rozmiar prostokąta.
type: docs
url: /pl/aspose.slides/rectangle/
net_type: System.Drawing.Rectangle
---
## Rectangle klasa

Przechowuje zestaw czterech liczb całkowitych, które reprezentują położenie i rozmiar prostokąta. Zgodny z .NET `System.Drawing.Rectangle`.

Typ Rectangle udostępnia następujące elementy:

## Konstruktory

| Constructor | Description |
| :- | :- |
| [`__init__(self, x=0, y=0, width=0, height=0)`](/slides/python-net/pl/aspose.slides/rectangle/__init__/#int-int-int-int) | Tworzy prostokąt o określonym położeniu i rozmiarze. Wartości zmiennoprzecinkowe są obcinane do liczb całkowitych. |

## Właściwości

| Property | Description |
| :- | :- |
| [`x`](/slides/python-net/pl/aspose.slides/rectangle/x/) | Zwraca współrzędną x lewego górnego rogu tego prostokąta.<br/>            Tylko do odczytu **int**. |
| [`y`](/slides/python-net/pl/aspose.slides/rectangle/y/) | Zwraca współrzędną y lewego górnego rogu tego prostokąta.<br/>            Tylko do odczytu **int**. |
| [`width`](/slides/python-net/pl/aspose.slides/rectangle/width/) | Zwraca szerokość tego prostokąta.<br/>            Tylko do odczytu **int**. |
| [`height`](/slides/python-net/pl/aspose.slides/rectangle/height/) | Zwraca wysokość tego prostokąta.<br/>            Tylko do odczytu **int**. |
| [`left`](/slides/python-net/pl/aspose.slides/rectangle/left/) | Zwraca współrzędną x lewej krawędzi tego prostokąta. Równa `x`.<br/>            Tylko do odczytu **int**. |
| [`top`](/slides/python-net/pl/aspose.slides/rectangle/top/) | Zwraca współrzędną y górnej krawędzi tego prostokąta. Równa `y`.<br/>            Tylko do odczytu **int**. |
| [`right`](/slides/python-net/pl/aspose.slides/rectangle/right/) | Zwraca współrzędną x będącą sumą `x` i `width` tego prostokąta.<br/>            Tylko do odczytu **int**. |
| [`bottom`](/slides/python-net/pl/aspose.slides/rectangle/bottom/) | Zwraca współrzędną y będącą sumą `y` i `height` tego prostokąta.<br/>            Tylko do odczytu **int**. |
| [`is_empty`](/slides/python-net/pl/aspose.slides/rectangle/is_empty/) | Określa, czy wszystkie numeryczne właściwości tego prostokąta mają wartość zero.<br/>            Tylko do odczytu **bool**. |

## Metody

| Method | Description |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/pl/aspose.slides/rectangle/contains/#int-int) | Określa, czy określony punkt znajduje się w tym prostokącie. |
| [`contains(self, point)`](/slides/python-net/pl/aspose.slides/rectangle/contains/#point) | Określa, czy określony punkt znajduje się w tym prostokącie. |
| [`contains(self, rect)`](/slides/python-net/pl/aspose.slides/rectangle/contains/#rectangle) | Określa, czy prostokątny obszar reprezentowany przez `rect` jest całkowicie zawarty w tym prostokącie. |


### Uwagi

Prostokąty są porównywane według ich położenia i rozmiaru przy użyciu `==` i mogą być używane jako klucze słowników lub elementy zbiorów.


### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)