---
title: Size
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Reprezentuje parę wartości całkowitych określających szerokość i wysokość obrazu. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub przez referencję. Nigdy nie używaj klasy System::SmartPtr do zarządzania obiektami tego typu."
type: docs
weight: 274
url: /pl/system.drawing/size/
---
## Klasa Size

Reprezentuje parę wartości całkowitych, które określają szerokość i wysokość obrazu. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub przez referencję. Nigdy nie używaj klasy [System::SmartPtr](../../system/smartptr/) do zarządzania obiektami tego typu.

```cpp
class Size
```

## Metody

| Metoda | Opis |
| --- | --- |
| static [Size](./) [Add](./add/)(const [Size](./)\&, const [Size](./)\&) | Zwraca nowy obiekt [Size](./), który jest sumą określonego obiektu [Size](./), tzn. jego wartość szerokości jest równa sumie wartości szerokości określonych obiektów, a wartość wysokości jest równa sumie wartości wysokości określonych obiektów. |
| static [Size](./) [Ceiling](./ceiling/)(const [SizeF](../sizef/)\&) | Tworzy obiekt [Size](./) z określonego obiektu [SizeF](../sizef/) poprzez zaokrąglenie wartości szerokości i wysokości obiektu [SizeF](../sizef/) do następnych wyższych liczb całkowitych. |
| **bool** [Equals](./equals/)(const [Size](./)\&) const | Określa, czy bieżący obiekt i określony obiekt są równe, tzn. reprezentują tę samą parę wartości szerokości i wysokości. |
| int [get_Height](./get_height/)() const | Zwraca wartość wysokości reprezentowaną przez bieżący obiekt. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Określa, czy zarówno wartości szerokości, jak i wysokości są równe 0. |
| int [get_Width](./get_width/)() const | Zwraca wartość szerokości reprezentowaną przez bieżący obiekt. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Zwraca kod skrótu (hash) dla bieżącego obiektu. |
|  [operator Point](./operator_point/)() const | Tworzy instancję obiektu [Point](../point/) i inicjalizuje jego współrzędne X i Y odpowiednio wartościami szerokości i wysokości bieżącego obiektu. |
|  [operator SizeF](./operator_sizef/)() const | Tworzy instancję obiektu [SizeF](../sizef/) i inicjalizuje ją wartościami szerokości i wysokości bieżącego obiektu [Size](./). |
| static [Size](./) [Round](./round/)(const [SizeF](../sizef/)\&) | Tworzy obiekt [Size](./) z określonego obiektu [SizeF](../sizef/) poprzez zaokrąglenie wartości szerokości i wysokości obiektu [SizeF](../sizef/) do najbliższych liczb całkowitych. |
| void [set_Height](./set_height/)(int) | Ustawia wartość wysokości reprezentowaną przez bieżący obiekt. |
| void [set_Width](./set_width/)(int) | Ustawia wartość szerokości reprezentowaną przez bieżący obiekt. |
|  [Size](./size/)() | Tworzy nowy obiekt [Size](./) i inicjalizuje jego wartości szerokości i wysokości na 0. |
|  [Size](./size/)(const [Point](../point/)\&) | Tworzy nowy obiekt [Size](./) i inicjalizuje jego wartości szerokości i wysokości wartościami współrzędnych X i Y podanego punktu odpowiednio. |
|  [Size](./size/)(int, int) | Tworzy nowy obiekt [Size](./) i inicjalizuje go podaną wartością. |
| static [Size](./) [Subtract](./subtract/)(const [Size](./)\&, const [Size](./)\&) | Zwraca nowy obiekt [Size](./), który jest wynikiem odjęcia **size2** od **size1**, tzn. jego wartość szerokości jest wynikiem odjęcia wartości szerokości **size2** od wartości szerokości **size1**, a wartość wysokości jest wynikiem odjęcia wartości wysokości **size2** od wartości wysokości **size1**. |
| [String](../../system/string/) [ToString](./tostring/)() const | Zwraca reprezentację tekstową pary wartości szerokości i wysokości reprezentowanej przez bieżący obiekt. |
| static [Size](./) [Truncate](./truncate/)(const [SizeF](../sizef/)\&) | Tworzy obiekt [Size](./) z określonego obiektu [SizeF](../sizef/) poprzez przycięcie wartości szerokości i wysokości obiektu [SizeF](../sizef/) do następnych niższych liczb całkowitych. |

## Pola

| Pole | Opis |
| --- | --- |
| static [Empty](./empty/) | Pustą instancję klasy [Size](./), której wartości szerokości i wysokości wynoszą 0. |

## Zobacz także

* Przestrzeń nazw [System::Drawing](../)
* Biblioteka [Aspose.Slides](../../)