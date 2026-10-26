---
title: Point
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Reprezentuje parę całkowitych współrzędnych X i Y punktu na dwuwymiarowej płaszczyźnie. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub przez referencję. Nigdy nie używaj klasy System::SmartPtr do zarządzania obiektami tego typu."
type: docs
weight: 209
url: /pl/system.drawing/point/
---
## Point klasa

Represents a pair of integer X and Y coordinates of a point on a 2-dimensional plane. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../../system/smartptr/) klasy to manage objects of this type.

```cpp
class Point
```

## Metody

| Method | Description |
| --- | --- |
| static [Point](./) [Add](./add/)(const [Point](./)\&, const [Size](../size/)\&) | Dodaje wartości szerokości i wysokości określonego obiektu [Size](../size/) do wartości współrzędnych X i Y określonego obiektu [Point](./) odpowiednio. |
| static [Point](./) [Ceiling](./ceiling/)(const [PointF](../pointf/)\&) | Tworzy obiekt [Point](./) z określonego obiektu [PointF](../pointf/) przez zaokrąglenie wartości współrzędnych X i Y obiektu [PointF](../pointf/) do następnych wyższych wartości całkowitych. |
| **bool** [Equals](./equals/)(const [Point](./)\&) const | Określa, czy bieżący obiekt i określony obiekt są równe, tzn. reprezentują tę samą parę wartości współrzędnych X i Y. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Określa, czy zarówno wartości współrzędnych X, jak i Y są równe 0. |
| int [get_X](./get_x/)() const | Zwraca wartość współrzędnej X reprezentowaną przez bieżący obiekt. |
| int [get_Y](./get_y/)() const | Zwraca wartość współrzędnej Y reprezentowaną przez bieżący obiekt. |
| int [GetHashCode](./gethashcode/)() const | Zwraca kod skrótu dla bieżącego obiektu. |
| size_t [getStdHash](./getstdhash/)() const | Zwraca wartość skrótu dla bieżącego obiektu. |
| **bool** [IsNull](./isnull/)() const | Zawsze zwraca false. |
| void [Offset](./offset/)(int, int) | Przesuwa wartość współrzędnych X i Y reprezentowaną przez bieżący obiekt o podane wartości. |
| void [Offset](./offset/)([Point](./)) | Przesuwa współrzędne X i Y reprezentowane przez bieżący obiekt o wartości współrzędnych X i Y reprezentowane przez określony obiekt [Point](./) odpowiednio. |
|  [operator PointF](./operator_pointf/)() const | Tworzy instancję obiektu [PointF](../pointf/) i inicjalizuje ją z wartościami współrzędnych X i Y bieżącego obiektu [Point](./). |
|  [operator Size](./operator_size/)() const | Tworzy instancję obiektu [Size](../size/) i inicjalizuje jej wartości szerokości i wysokości wartościami współrzędnych X i Y reprezentowanymi przez bieżący obiekt odpowiednio. |
|  [Point](./point/)() | Tworzy nowy obiekt [Point](./) i inicjalizuje jego wartości współrzędnych X i Y zerem. |
|  [Point](./point/)(int, int) | Tworzy nowy obiekt [Point](./) i inicjalizuje go podanymi wartościami. |
|  [Point](./point/)(const [Size](../size/)\&) | Tworzy nowy obiekt [Point](./) i inicjalizuje jego wartości współrzędnych X i Y wartościami szerokości i wysokości określonego obiektu [SizeF](../sizef/) odpowiednio. |
|  [Point](./point/)(int) | Tworzy nowy obiekt [Point](./) i inicjalizuje jego wartość współrzędnej X wartością utworzoną z wysokich 16 bitów podanej 32-bitowej liczby całkowitej oraz wartość współrzędnej Y wartością utworzoną z niskich 16 bitów tej samej 32-bitowej liczby całkowitej. |
| static [Point](./) [Round](./round/)(const [PointF](../pointf/)\&) | Tworzy obiekt [Point](./) z określonego obiektu [PointF](../pointf/) przez zaokrąglenie wartości współrzędnych X i Y obiektu [PointF](../pointf/) do najbliższych wartości całkowitych. |
| void [set_X](./set_x/)(int) | Ustawia wartość współrzędnej X reprezentowanej przez bieżący obiekt. |
| void [set_Y](./set_y/)(int) | Ustawia wartość współrzędnej Y reprezentowanej przez bieżący obiekt. |
| static [Point](./) [Subtract](./subtract/)(const [Point](./)\&, const [Size](../size/)\&) | Odejmuje wartości szerokości i wysokości określonego obiektu [Size](../size/) od wartości współrzędnych X i Y określonego obiektu [Point](./) odpowiednio. |
| [String](../../system/string/) [ToString](./tostring/)() const | Zwraca łańcuchowy reprezentację pary wartości współrzędnych X i Y reprezentowanych przez bieżący obiekt. |
| static [Point](./) [Truncate](./truncate/)(const [PointF](../pointf/)\&) | Tworzy obiekt [Point](./) z określonego obiektu [PointF](../pointf/) przez obcięcie wartości współrzędnych X i Y obiektu [PointF](../pointf/) do następnych niższych wartości całkowitych. |

## Pola

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | Pusta instancja klasy [Point](./), której wartości współrzędnych X i Y są równe 0. |

## Zobacz także

* Przestrzeń nazw [System::Drawing](../)
* Biblioteka [Aspose.Slides](../../)