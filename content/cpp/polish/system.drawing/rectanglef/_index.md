---
title: RectangleF
second_title: Aspose.Slides dla C++ – Referencja API
description: "Reprezentuje prostokątny obszar obrazu określony jako współrzędne X i Y w formacie zmiennoprzecinkowym pojedynczej precyzji lewego górnego rogu oraz jego szerokość i wysokość. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub referencję. Nigdy nie używaj klasy System::SmartPtr do zarządzania obiektami tego typu."
type: docs
weight: 248
url: /pl/system.drawing/rectanglef/
---
## RectangleF klasa

Reprezentuje prostokątny obszar obrazu określony jako współrzędne X i Y w formacie zmiennoprzecinkowym pojedynczej precyzji lewego górnego rogu oraz jego szerokość i wysokość. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub referencję. Nigdy nie używaj klasy [System::SmartPtr](../../system/smartptr/) do zarządzania obiektami tego typu.

```cpp
class RectangleF
```

## Metody

| Metoda | Opis |
| --- | --- |
| **bool** [Contains](./contains/)(**float**, **float**) | Określa, czy podany punkt znajduje się wewnątrz prostokąta reprezentowanego przez bieżący obiekt. |
| **bool** [Contains](./contains/)(const [PointF](../pointf/)\&) | Określa, czy podany punkt znajduje się wewnątrz prostokąta reprezentowanego przez bieżący obiekt. |
| **bool** [Contains](./contains/)(const [RectangleF](./)\&) | Określa, czy podany prostokąt znajduje się wewnątrz prostokąta reprezentowanego przez bieżący obiekt. |
| **bool** [Equals](./equals/)(const [RectangleF](./)\&) const | Określa, czy prostokąty reprezentowane przez bieżący i podany obiekt są identyczne. |
| static [RectangleF](./) [FromLTRB](./fromltrb/)(**float**, **float**, **float**, **float**) | Tworzy nowy obiekt [RectangleF](./), który reprezentuje prostokąt o podanych położeniach krawędzi. |
| **float** [get_Bottom](./get_bottom/)() const | Zwraca współrzędną y dolnej krawędzi prostokąta reprezentowanego przez bieżący obiekt. |
| **float** [get_Height](./get_height/)() const | Zwraca wysokość prostokąta reprezentowanego przez bieżący obiekt. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Określa, czy współrzędne X i Y lewego górnego rogu prostokąta reprezentowanego przez bieżący obiekt oraz jego szerokość i wysokość mają wartość 0. |
| **float** [get_Left](./get_left/)() const | Zwraca współrzędną X lewej krawędzi prostokąta reprezentowanego przez bieżący obiekt. |
| [PointF](../pointf/) [get_Location](./get_location/)() const | Zwraca instancję klasy [PointF](../pointf/), określającą położenie lewego górnego rogu prostokąta reprezentowanego przez bieżący obiekt. |
| **float** [get_Right](./get_right/)() const | Zwraca współrzędną X prawej krawędzi prostokąta reprezentowanego przez bieżący obiekt. |
| [SizeF](../sizef/) [get_Size](./get_size/)() const | Zwraca instancję klasy [SizeF](../sizef/), określającą szerokość i wysokość prostokąta reprezentowanego przez bieżący obiekt. |
| **float** [get_Top](./get_top/)() const | Zwraca współrzędną Y górnej krawędzi prostokąta reprezentowanego przez bieżący obiekt. |
| **float** [get_Width](./get_width/)() const | Zwraca szerokość prostokąta reprezentowanego przez bieżący obiekt. |
| **float** [get_X](./get_x/)() const | Zwraca współrzędną X lewego górnego rogu prostokąta reprezentowanego przez bieżący obiekt. |
| **float** [get_Y](./get_y/)() const | Zwraca współrzędną Y lewego górnego rogu prostokąta reprezentowanego przez bieżący obiekt. |
| int [GetHashCode](./gethashcode/)() const | Zwraca kod skrótu bieżącego obiektu. |
| void [Inflate](./inflate/)(**float**, **float**) | Zwiększa szerokość i wysokość prostokąta reprezentowanego przez bieżący obiekt, zachowując położenie środka geometrycznego prostokąta. Szerokość i wysokość są zwiększane w obu kierunkach o podane wartości. |
| void [Inflate](./inflate/)(const [SizeF](../sizef/)\&) | Zwiększa szerokość i wysokość prostokąta reprezentowanego przez bieżący obiekt, zachowując położenie środka geometrycznego prostokąta. Szerokość i wysokość są zwiększane w obu kierunkach o wartości określone w polach width i height podanego obiektu rozmiaru. |
| static [RectangleF](./) [Inflate](./inflate/)(const [RectangleF](./)\&, **float**, **float**) | Zwiększa szerokość i wysokość prostokąta reprezentowanego przez podany obiekt, zachowując położenie środka geometrycznego prostokąta. Szerokość i wysokość są zwiększane w obu kierunkach o podane wartości. |
| void [Intersect](./intersect/)(const [RectangleF](./)\&) | Zastępuje prostokąt reprezentowany przez bieżący obiekt prostokątem będącym wynikiem przecięcia z prostokątem reprezentowanym przez podany obiekt. |
| static [RectangleF](./) [Intersect](./intersect/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | Zwraca prostokąt będący wynikiem przecięcia podanych prostokątów. |
| **bool** [IntersectsWith](./intersectswith/)(const [RectangleF](./)\&) | Określa, czy prostokąty reprezentowane przez bieżący i podany obiekt przecinają się. |
| void [Offset](./offset/)(const [PointF](../pointf/)\&) | Przesuwa położenie prostokąta reprezentowanego przez bieżący obiekt o podane wartości. |
| void [Offset](./offset/)(**float**, **float**) | Przesuwa położenie prostokąta reprezentowanego przez bieżący obiekt o podane wartości. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Zawsze zwraca true. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Zawsze zwraca false. |
| [RectangleF](./rectanglef/)() | Tworzy nową instancję obiektu [RectangleF](./), który reprezentuje prostokąt z współrzędnymi X i Y oraz szerokością i wysokością ustawionymi na 0. |
| [RectangleF](./rectanglef/)(**float**, **float**, **float**, **float**) | Tworzy nową instancję obiektu [RectangleF](./), który reprezentuje prostokąt o podanych współrzędnych lewego górnego rogu oraz szerokości i wysokości. |
| [RectangleF](./rectanglef/)(const [PointF](../pointf/)\&, const [SizeF](../sizef/)\&) | Tworzy nową instancję obiektu [RectangleF](./), który reprezentuje prostokąt, którego współrzędne lewego górnego rogu określa instancja klasy [PointF](../pointf/), a szerokość i wysokość – instancja klasy [SizeF](../sizef/). |
| explicit  [RectangleF](./rectanglef/)(const [Rectangle](../rectangle/)\&) | Tworzy nową instancję obiektu [RectangleF](./), który reprezentuje prostokąt równoważny z podanym. |
| void [set_Height](./set_height/)(**float**) | Ustawia wysokość prostokąta reprezentowanego przez bieżący obiekt. |
| void [set_Location](./set_location/)([PointF](../pointf/)) | Ustawia położenie lewego górnego rogu prostokąta reprezentowanego przez bieżący obiekt. |
| void [set_Size](./set_size/)([SizeF](../sizef/)) | Ustawia szerokość i wysokość prostokąta reprezentowanego przez bieżący obiekt. |
| void [set_Width](./set_width/)(**float**) | Ustawia szerokość prostokąta reprezentowanego przez bieżący obiekt. |
| void [set_X](./set_x/)(**float**) | Ustawia współrzędną X lewego górnego rogu prostokąta reprezentowanego przez bieżący obiekt. |
| void [set_Y](./set_y/)(**float**) | Ustawia współrzędną Y lewego górnego rogu prostokąta reprezentowanego przez bieżący obiekt. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Zwraca tekstową reprezentację bieżącego obiektu. |
| static [RectangleF](./) [Union](./union/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | Zwraca prostokąt będący wynikiem unii podanych prostokątów. |

## Pola

| Pole | Opis |
| --- | --- |
| static [Empty](./empty/) | Pusty prostokąt, tj. prostokąt, którego wartości położenia i rozmiaru są zerowe. |

## Zobacz także

* Przestrzeń nazw [System::Drawing](../)
* Biblioteka [Aspose.Slides](../../)