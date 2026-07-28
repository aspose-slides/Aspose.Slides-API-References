---
title: Rectangle
second_title: Aspose.Slides dla C++ - odniesienie API
description: "Reprezentuje prostokątny obszar obrazu określony jako całkowite współrzędne X i Y lewego górnego rogu oraz jego szerokość i wysokość. Ten typ powinien być przydzielany na stosie i przekazywany do funkcji przez wartość lub referencję. Nigdy nie używaj klasy System::SmartPtr do zarządzania obiektami tego typu."
type: docs
weight: 235
url: /pl/system.drawing/rectangle/
---
## Rectangle klasa

Represents a rectangular area of an image defined as integer X and Y coordinates of its upper left corner and its width and height. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../../system/smartptr/) class to manage objects of this type.

```cpp
class Rectangle
```

## Metody

| Metoda | Opis |
| --- | --- |
| static [Rectangle](./) [Ceiling](./ceiling/)(const [RectangleF](../rectanglef/)\&) | Tworzy obiekt [Rectangle](./) na podstawie określonego obiektu [RectangleF](../rectanglef/) poprzez zaokrąglenie wartości położenia i rozmiaru obiektu [RectangleF](../rectanglef/) do następnych wyższych wartości całkowitych. |
| **bool** [Contains](./contains/)(int, int) const | Określa, czy podany punkt znajduje się wewnątrz prostokąta reprezentowanego przez bieżący obiekt. |
| **bool** [Contains](./contains/)(const [Point](../point/)\&) const | Określa, czy podany punkt znajduje się wewnątrz prostokąta reprezentowanego przez bieżący obiekt. |
| **bool** [Contains](./contains/)(const [Rectangle](./)\&) const | Określa, czy podany prostokąt znajduje się wewnątrz prostokąta reprezentowanego przez bieżący obiekt. |
| **bool** [Equals](./equals/)(const [Rectangle](./)\&) const | Określa, czy prostokąty reprezentowane przez bieżący i określony obiekt są identyczne. |
| static [Rectangle](./) [FromLTRB](./fromltrb/)(int, int, int, int) | Tworzy nowy obiekt [Rectangle](./), który reprezentuje prostokąt o podanych położeniach krawędzi. |
| int [get_Bottom](./get_bottom/)() const | Zwraca współrzędną y dolnej krawędzi prostokąta reprezentowanego przez bieżący obiekt. |
| int [get_Height](./get_height/)() const | Zwraca wysokość prostokąta reprezentowanego przez bieżący obiekt. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Określa, czy współrzędne X i Y lewego górnego rogu prostokąta reprezentowanego przez bieżący obiekt oraz jego szerokość i wysokość mają wartość 0. |
| int [get_Left](./get_left/)() const | Zwraca współrzędną X lewej krawędzi prostokąta reprezentowanego przez bieżący obiekt. |
| [Point](../point/) [get_Location](./get_location/)() const | Zwraca instancję klasy [Point](../point/), która określa położenie lewego górnego rogu prostokąta reprezentowanego przez bieżący obiekt. |
| int [get_Right](./get_right/)() const | Zwraca współrzędną X prawej krawędzi prostokąta reprezentowanego przez bieżący obiekt. |
| [Size](../size/) [get_Size](./get_size/)() const | Zwraca instancję klasy [Size](../size/), która określa szerokość i wysokość prostokąta reprezentowanego przez bieżący obiekt. |
| int [get_Top](./get_top/)() const | Zwraca współrzędną Y górnej krawędzi prostokąta reprezentowanego przez bieżący obiekt. |
| int [get_Width](./get_width/)() const | Zwraca szerokość prostokąta reprezentowanego przez bieżący obiekt. |
| int [get_X](./get_x/)() const | Zwraca współrzędną X lewego górnego rogu prostokąta reprezentowanego przez bieżący obiekt. |
| int [get_Y](./get_y/)() const | Zwraca współrzędną Y lewego górnego rogu prostokąta reprezentowanego przez bieżący obiekt. |
| int [GetHashCode](./gethashcode/)() const | Zwraca kod skrótu bieżącego obiektu. |
| void [Inflate](./inflate/)(int, int) | Zwiększa szerokość i wysokość prostokąta reprezentowanego przez bieżący obiekt, zachowując położenie środka geometrycznego prostokąta. Szerokość i wysokość są zwiększane w obu kierunkach o podane wartości. |
| void [Inflate](./inflate/)(const [Size](../size/)\&) | Zwiększa szerokość i wysokość prostokąta reprezentowanego przez bieżący obiekt, zachowując położenie środka geometrycznego prostokąta. Szerokość i wysokość są zwiększane w obu kierunkach o wartości określone przez odpowiednie wartości szerokości i wysokości podanego obiektu rozmiaru. |
| static [Rectangle](./) [Inflate](./inflate/)(const [Rectangle](./)\&, int, int) | Zwiększa szerokość i wysokość prostokąta reprezentowanego przez określony obiekt, zachowując położenie środka geometrycznego prostokąta. Szerokość i wysokość są zwiększane w obu kierunkach o podane wartości. |
| void [Intersect](./intersect/)(const [Rectangle](./)\&) | Zastępuje prostokąt reprezentowany przez bieżący obiekt prostokątem będącym wynikiem jego przecięcia z prostokątem reprezentowanym przez określony obiekt. |
| static [Rectangle](./) [Intersect](./intersect/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | Zwraca prostokąt będący wynikiem przecięcia podanych prostokątów. |
| **bool** [IntersectsWith](./intersectswith/)(const [Rectangle](./)\&) | Określa, czy prostokąty reprezentowane przez bieżący i określony obiekt przecinają się. |
| void [Offset](./offset/)(const [Point](../point/)\&) | Przesuwa pozycję prostokąta reprezentowanego przez bieżący obiekt o podane wartości. |
| void [Offset](./offset/)(int, int) | Przesuwa pozycję prostokąta reprezentowanego przez bieżący obiekt o podane wartości. |
| [operator RectangleF](./operator_rectanglef/)() const | Zwraca obiekt [RectangleF](../rectanglef/), który reprezentuje prostokąt równoważny prostokątowi reprezentowanemu przez bieżący obiekt. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Zawsze zwraca true. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Zawsze zwraca false. |
| [Rectangle](./rectangle/)() | Tworzy nową instancję obiektu [Rectangle](./), który reprezentuje prostokąt z współrzędnymi X i Y oraz wartościami szerokości i wysokości ustawionymi na 0. |
| [Rectangle](./rectangle/)(int, int, int, int) | Tworzy nową instancję obiektu [Rectangle](./), który reprezentuje prostokąt o podanych współrzędnych lewego górnego rogu oraz szerokości i wysokości. |
| [Rectangle](./rectangle/)(const [Point](../point/)\&, const [Size](../size/)\&) | Tworzy nową instancję obiektu [Rectangle](./), który reprezentuje prostokąt, którego współrzędne lewego górnego rogu określone są jako instancja klasy [Point](../point/), a jego szerokość i wysokość jako instancja klasy [Size](../size/). |
| [Rectangle](./rectangle/)(const **System::Windows::Forms::Screen::Rectangle_**\&) | Tworzy nową instancję obiektu [Rectangle](./), który reprezentuje prostokąt równoważny podanemu. |
| static [Rectangle](./) [Round](./round/)(const [RectangleF](../rectanglef/)\&) | Tworzy obiekt [Rectangle](./) na podstawie określonego obiektu [RectangleF](../rectanglef/) poprzez zaokrąglenie wartości położenia i rozmiaru obiektu [RectangleF](../rectanglef/) do najbliższych wartości całkowitych. |
| void [set_Height](./set_height/)(int) | Ustawia wysokość prostokąta reprezentowanego przez bieżący obiekt. |
| void [set_Location](./set_location/)([Point](../point/)) | Ustawia położenie lewego górnego rogu prostokąta reprezentowanego przez bieżący obiekt. |
| void [set_Size](./set_size/)([Size](../size/)) | Ustawia szerokość i wysokość prostokąta reprezentowanego przez bieżący obiekt. |
| void [set_Width](./set_width/)(int) | Ustawia szerokość prostokąta reprezentowanego przez bieżący obiekt. |
| void [set_X](./set_x/)(int) | Ustawia współrzędną X lewego górnego rogu prostokąta reprezentowanego przez bieżący obiekt. |
| void [set_Y](./set_y/)(int) | Ustawia współrzędną Y lewego górnego rogu prostokąta reprezentowanego przez bieżący obiekt. |
| [String](../../system/string/) [ToString](./tostring/)() const | Zwraca ciąg znaków reprezentujący bieżący obiekt. |
| static [Rectangle](./) [Truncate](./truncate/)(const [RectangleF](../rectanglef/)\&) | Tworzy obiekt [Rectangle](./) na podstawie określonego obiektu [RectangleF](../rectanglef/) poprzez obcięcie wartości położenia i rozmiaru obiektu [RectangleF](../rectanglef/) do kolejnych niższych wartości całkowitych. |
| static [Rectangle](./) [Union](./union/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | Zwraca prostokąt będący wynikiem sumy (union) podanych prostokątów. |

## Pola

| Pole | Opis |
| --- | --- |
| static [Empty](./empty/) | Pusty prostokąt, tj. prostokąt, którego wartości położenia i rozmiaru są zerowe. |

## Zobacz także

* Przestrzeń nazw [System::Drawing](../)
* Biblioteka [Aspose.Slides](../../)