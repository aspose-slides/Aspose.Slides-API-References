---
title: Index
second_title: Aspose.Slides dla C++ – Referencja API
description: "Reprezentuje indeks w kolekcji. Indeks może pochodzić od początku lub od końca. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub przez referencję. Nigdy nie używaj klasy System::SmartPtr do zarządzania obiektami tego typu."
type: docs
weight: 1015
url: /pl/system/index/
---
## Klasa Index

Reprezentuje indeks w kolekcji. Indeks może pochodzić od początku lub od końca. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub przez referencję. Nigdy nie używaj [System::SmartPtr](../smartptr/) klasy do zarządzania obiektami tego typu.

```cpp
class Index : public System::Details::BoxableObjectBase
```

## Metody

| Metoda | Opis |
| --- | --- |
| **bool** [Equals](./equals/)(const [Index](./)\&) const | Określa, czy bieżąca instancja i określony [Index](./) reprezentują tę samą pozycję. |
| static constexpr [Index](./) [FromEnd](./fromend/)(**int32_t**) | Tworzy [Index](./), który jest względny względem końca kolekcji. |
| static constexpr [Index](./) [get_End](./get_end/)() | Zwraca obiekt [Index](./) reprezentujący koniec kolekcji. |
| constexpr **bool** [get_IsFromEnd](./get_isfromend/)() const | Zwraca wartość wskazującą, czy indeks pochodzi od końca. |
| static constexpr [Index](./) [get_Start](./get_start/)() | Zwraca obiekt [Index](./) reprezentujący początek kolekcji. |
| constexpr **int32_t** [get_Value](./get_value/)() const | Zwraca wartość indeksu. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Zwraca kod hash dla bieżącego indeksu. |
| **int32_t** [GetOffset](./getoffset/)(**int32_t**) const | Konwertuje bieżący [Index](./) na offset od początku kolekcji o określonej długości. |
| constexpr [Index](./index/)() | Tworzy instancję, która reprezentuje początek kolekcji. |
| constexpr [Index](./index/)(**int32_t**) | Tworzy instancję, która reprezentuje określoną pozycję od początku kolekcji. |
| constexpr [Index](./index/)(**int32_t**, **bool**) | Tworzy instancję, która reprezentuje określony indeks. |

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)