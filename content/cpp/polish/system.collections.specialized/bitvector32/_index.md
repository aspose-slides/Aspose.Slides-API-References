---
title: BitVector32
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Zapewnia prosty, lekki wektor bitów z łatwym dostępem całkowitoliczbowym lub logicznym do 32-bitowego magazynu.
type: docs
weight: 1
url: /pl/system.collections.specialized/bitvector32/
---
## BitVector32 klasa

Zapewnia prosty lekki wektor bitów z łatwym dostępem całkowitoliczbowym lub [Boolean](../../system/boolean/) do 32-bitowego magazynu.

```cpp
class BitVector32
```

## Metody

| Metoda | Opis |
| --- | --- |
|  [BitVector32](./bitvector32/)() | Inicjalizuje nową pustą instancję [BitVector32](./). |
|  [BitVector32](./bitvector32/)(**int32_t**) | Inicjalizuje nową instancję struktury [BitVector32](./) przy określonych danych wewnętrznych. |
|  [BitVector32](./bitvector32/)(const [BitVector32](./)\&) | Inicjalizuje nową instancję struktury [BitVector32](./) z informacjami z określonej wartości. |
| static **int32_t** [CreateMask](./createmask/)() | Tworzy pierwszą maskę w serii. |
| static **int32_t** [CreateMask](./createmask/)(**int32_t**) | Tworzy następną maskę w serii. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**) | Tworzy pierwszą sekcję w serii, z określoną maksymalną wartością. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**, **BitVector32::Section**) | Tworzy następną sekcję w serii, z określoną maksymalną wartością. |
| **bool** [Equals](./equals/)(const [BitVector32](./)\&) | Określa, czy podany obiekt jest taki sam jak bieżący. |
| **int32_t** [get_Data](./get_data/)() | zwraca surowe dane przechowywane w tym wektorze bitów... |
| **int32_t** [GetHashCode](./gethashcode/)() const | Zwraca kod hash dla bieżącego obiektu. |
| **bool** [idx_get](./idx_get/)(**int32_t**) | Pobiera wartość wskazującą, czy wszystkie określone bity są ustawione. |
| **int32_t** [idx_get](./idx_get/)(**BitVector32::Section**) | Pobiera wartość dla określonej sekcji. |
| void [idx_set](./idx_set/)(**int32_t**, **bool**) | Ustawia wartość wskazującą, czy wszystkie określone bity są ustawione. |
| void [idx_set](./idx_set/)(**BitVector32::Section**, **int32_t**) | Ustawia wartość dla określonej sekcji. |
| static [String](../../system/string/) [ToString](./tostring/)(const [BitVector32](./)\&) | Konwertuje wartość reprezentowaną przez parametr value na ciąg znaków. |
| [String](../../system/string/) [ToString](./tostring/)() const | Konwertuje wartość reprezentowaną przez bieżący obiekt na ciąg znaków. |
## Zobacz także

* Przestrzeń nazw [System::Collections::Specialized](../)
* Biblioteka [Aspose.Slides](../../)