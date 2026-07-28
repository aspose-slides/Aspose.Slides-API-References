---
title: PointF
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Reprezentuje parę współrzędnych X i Y punktu na płaszczyźnie dwuwymiarowej, zapisanych jako liczby zmiennoprzecinkowe pojedynczej precyzji. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub referencję. Nigdy nie używaj klasy System::SmartPtr do zarządzania obiektami tego typu."
type: docs
weight: 222
url: /pl/system.drawing/pointf/
---
## PointF klasa

Represents a pair of single-precision floating point X and Y coordinates of a point on a 2-dimensional plane. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../../system/smartptr/) class to manage objects of this type.

```cpp
class PointF
```

## Metody

| Metoda | Opis |
| --- | --- |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | Dodaje wartości szerokości i wysokości określonego obiektu [SizeF](../sizef/) do wartości współrzędnych X i Y określonego obiektu [PointF](./) odpowiednio. |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [Size](../size/)\&) | Dodaje wartości szerokości i wysokości określonego obiektu [Size](../size/) do wartości współrzędnych X i Y określonego obiektu [PointF](./) odpowiednio. |
| **bool** [Equals](./equals/)(const [PointF](./)\&) const | Określa, czy bieżący obiekt i określony obiekt są równe, tzn. reprezentują tę samą parę wartości współrzędnych X i Y. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Określa, czy wartości współrzędnych X i Y są równe 0. |
| **float** [get_X](./get_x/)() const | Zwraca wartość współrzędnej X reprezentowaną przez bieżący obiekt. |
| **float** [get_Y](./get_y/)() const | Zwraca wartość współrzędnej Y reprezentowaną przez bieżący obiekt. |
| int [GetHashCode](./gethashcode/)() const | Zwraca kod skrótu dla bieżącego obiektu. |
| **bool** [IsNull](./isnull/)() const | Zawsze zwraca fałsz. |
| explicit  [operator bool](./operator_bool/)() | Zawsze zwraca prawdę. |
|  [PointF](./pointf/)() | Tworzy nowy obiekt [PointF](./) i inicjalizuje jego wartości współrzędnych X i Y na 0. |
|  [PointF](./pointf/)(**float**, **float**) | Tworzy nowy obiekt [PointF](./) i inicjalizuje go podanymi wartościami. |
|  [PointF](./pointf/)(const [SizeF](../sizef/)\&) | Tworzy nowy obiekt [PointF](./) i inicjalizuje jego wartości współrzędnych X i Y wartościami szerokości i wysokości określonego obiektu [SizeF](../sizef/) odpowiednio. |
| void [set_X](./set_x/)(**float**) | Ustawia wartość współrzędnej X reprezentowanej przez bieżący obiekt. |
| void [set_Y](./set_y/)(**float**) | Ustawia wartość współrzędnej Y reprezentowanej przez bieżący obiekt. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | Odejmuje wartości szerokości i wysokości określonego obiektu [SizeF](../sizef/) od wartości współrzędnych X i Y określonego obiektu [PointF](./) odpowiednio. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [Size](../size/)\&) | Odejmuje wartości szerokości i wysokości określonego obiektu [Size](../size/) od wartości współrzędnych X i Y określonego obiektu [PointF](./) odpowiednio. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Zwraca tekstową reprezentację pary wartości współrzędnych X i Y reprezentowanej przez bieżący obiekt. |

## Pola

| Pole | Opis |
| --- | --- |
| static [Empty](./empty/) | Pusta instancja klasy [PointF](./), której wartości współrzędnych X i Y wynoszą 0. |

## Zobacz także

* Przestrzeń nazw [System::Drawing](../)
* Biblioteka [Aspose.Slides](../../)