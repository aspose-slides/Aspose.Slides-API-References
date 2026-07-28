---
title: Range
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Reprezentuje zakres z indeksem początkowym i końcowym. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub przez referencję. Nigdy nie używaj klasy System::SmartPtr do zarządzania obiektami tego typu."
type: docs
weight: 1197
url: /pl/system/range/
---
## Range klasa

Reprezentuje zakres z indeksem początkowym i końcowym. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub przez referencję. Nigdy nie używaj [System::SmartPtr](../smartptr/) klasy do zarządzania obiektami tego typu.

```cpp
class Range : public System::Details::BoxableObjectBase
```

## Metody

| Metoda | Opis |
| --- | --- |
| static constexpr [Range](./) [EndAt](./endat/)(const [Index](../index/)\&) | Tworzy zakres, który zaczyna się od początku kolekcji i kończy na określonym indeksie końcowym. |
| **bool** [Equals](./equals/)(const [Range](./)\&) const | Określa, czy bieżący zakres jest równy określonemu zakresowi. |
| static constexpr [Range](./) [get_All](./get_all/)() | Zwraca [Range](./), który reprezentuje całą kolekcję. |
| const [Index](../index/)\& [get_End](./get_end/)() const | Pobiera indeks End. |
| const [Index](../index/)\& [get_Start](./get_start/)() const | Pobiera indeks Start. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Zwraca kod skrótu dla bieżącego zakresu. |
| [System::ValueTuple](../valuetuple/)\<**int32_t**, **int32_t**\> [GetOffsetAndLength](./getoffsetandlength/)(**int32_t**) const | Oblicza zerowy offset początkowy i długość dla określonej długości kolekcji. |
| constexpr [Range](./range/)() | Tworzy pusty zakres. |
| constexpr [Range](./range/)(const [Index](../index/)\&, const [Index](../index/)\&) | Tworzy [Range](./) z określonych indeksów początkowego i końcowego. |
| static constexpr [Range](./) [StartAt](./startat/)(const [Index](../index/)\&) | Tworzy zakres, który zaczyna się od określonego indeksu początkowego i rozciąga się do końca kolekcji. |

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)