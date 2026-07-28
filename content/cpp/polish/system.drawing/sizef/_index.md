---
title: SizeF
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: "Reprezentuje parę wartości zmiennoprzecinkowych pojedynczej precyzji, które reprezentują szerokość i wysokość obrazu. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub przez referencję. Nigdy nie używaj klasy System::SmartPtr do zarządzania obiektami tego typu."
type: docs
weight: 287
url: /pl/system.drawing/sizef/
---
## SizeF klasa

Reprezentuje parę wartości zmiennoprzecinkowych pojedynczej precyzji, które reprezentują szerokość i wysokość obrazu. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub przez referencję. Nigdy nie używaj [System::SmartPtr](../../system/smartptr/) klasa do zarządzania obiektami tego typu.

```cpp
class SizeF
```

## Metody

| Metoda | Opis |
| --- | --- |
| static [SizeF](./) [Add](./add/)(const [SizeF](./)\&, const [SizeF](./)\&) | Zwraca nowy [SizeF](./) obiekt, który jest sumą określonych [SizeF](./) obiektów, tj. którego wartość szerokości jest równa sumie wartości szerokości określonych obiektów, a wartość wysokości jest równa sumie wartości wysokości określonych obiektów. |
| **bool** [Equals](./equals/)(const [SizeF](./)\&) const | Określa, czy bieżący obiekt i określony obiekt są równe, tj. reprezentują tę samą parę wartości szerokości i wysokości. |
| **float** [get_Height](./get_height/)() const | Zwraca wartość wysokości reprezentowaną przez bieżący obiekt. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Określa, czy zarówno wartości szerokości, jak i wysokości są równe 0. |
| **float** [get_Width](./get_width/)() const | Zwraca wartość szerokości reprezentowaną przez bieżący obiekt. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Zwraca kod skrótu dla bieżącego obiektu. |
| [operator PointF](./operator_pointf/)() const | Konwertuje bieżący obiekt na instancję obiektu [Point](../point/), inicjalizując jego współrzędne X i Y odpowiednio wartościami szerokości i wysokości bieżącego obiektu. |
| [SizeF](./)\& [operator+=](./operator_plus_equal/)(const [SizeF](./)\&) | Dodaje szerokość i wysokość określonego [SizeF](./) obiektu do szerokości i wysokości bieżącego [SizeF](./) obiektu odpowiednio. |
| void [set_Height](./set_height/)(**float**) | Ustawia wartość wysokości reprezentowaną przez bieżący obiekt. |
| void [set_Width](./set_width/)(**float**) | Ustawia wartość szerokości reprezentowaną przez bieżący obiekt. |
| [SizeF](./sizef/)() | Tworzy nowy [SizeF](./) obiekt i inicjalizuje jego wartości szerokości i wysokości na 0. |
| [SizeF](./sizef/)(const [PointF](../pointf/)\&) | Tworzy nowy [SizeF](./) obiekt i inicjalizuje jego wartości szerokości i wysokości odpowiednio wartościami współrzędnych X i Y określonego punktu. |
| [SizeF](./sizef/)(**float**, **float**) | Tworzy nowy [SizeF](./) obiekt i inicjalizuje go określonymi wartościami. |
| static [SizeF](./) [Subtract](./subtract/)(const [SizeF](./)\&, const [SizeF](./)\&) | Zwraca nowy [SizeF](./) obiekt, który jest wynikiem odjęcia **size2** od **size1**, tj. którego wartość szerokości jest wynikiem odjęcia wartości szerokości **size2** od wartości szerokości **size1**, a wartość wysokości jest wynikiem odjęcia wartości wysokości **size2** od wartości wysokości **size1**. |
| [PointF](../pointf/) [ToPointF](./topointf/)() const | Konwertuje bieżący obiekt na instancję obiektu [Point](../point/), inicjalizując jego współrzędne X i Y odpowiednio wartościami szerokości i wysokości bieżącego obiektu. |
| [Size](../size/) [ToSize](./tosize/)() const | Tworzy [Size](../size/) obiekt z bieżącego [SizeF](./) obiektu poprzez obcięcie wartości szerokości i wysokości [SizeF](./) obiektu do najbliższych niższych wartości całkowitych. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Zwraca reprezentację tekstową pary wartości szerokości i wysokości reprezentowanych przez bieżący obiekt. |

## Pola

| Pole | Opis |
| --- | --- |
| static [Empty](./empty/) | Pusta instancja klasy [SizeF](./), której wartości szerokości i wysokości wynoszą 0. |

## Zobacz też

* Przestrzeń nazw [System::Drawing](../)
* Biblioteka [Aspose.Slides](../../)