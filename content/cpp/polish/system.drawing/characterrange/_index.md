---
title: CharacterRange
second_title: Aspose.Slides dla C++ Dokumentacja API
description: "Reprezentuje zakres pozycji znaków w łańcuchu. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub przez referencję. Nigdy nie używaj klasy System::SmartPtr do zarządzania obiektami tego typu."
type: docs
weight: 40
url: /pl/system.drawing/characterrange/
---
## CharacterRange klasa


Reprezentuje zakres pozycji znaków w łańcuchu znaków. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub przez referencję. Nigdy nie używaj klasy [System::SmartPtr](../../system/smartptr/) do zarządzania obiektami tego typu.

```cpp
class CharacterRange
```

## Metody

| Metoda | Opis |
| --- | --- |
|  [CharacterRange](./characterrange/)(**int32_t**, **int32_t**) | Tworzy nową instancję klasy [CharacterRange](./) reprezentującą określony zakres. |
|  [CharacterRange](./characterrange/)() | Tworzy nową instancję klasy [CharacterRange](./) reprezentującą pusty zakres. |
| **int32_t** [get_First](./get_first/)() const | Zwraca pozycję pierwszego znaku zakresu reprezentowanego przez bieżący obiekt. |
| **int32_t** [get_Length](./get_length/)() const | Zwraca liczbę znaków w zakresie reprezentowanym przez bieżący obiekt. |
| **bool** [operator!=](./operator_not_equal/)(const [CharacterRange](./)\&) const | Określa, czy bieżący i określony obiekt reprezentują różne zakresy. |
| **bool** [operator==](./operator_equal_equal/)(const [CharacterRange](./)\&) const | Określa, czy bieżący i określony obiekt reprezentują ten sam zakres. |
| void [set_First](./set_first/)(**int32_t**) | Ustawia pozycję pierwszego znaku zakresu reprezentowanego przez bieżący obiekt. |
| void [set_Length](./set_length/)(**int32_t**) | Zwraca liczbę znaków w zakresie reprezentowanym przez bieżący obiekt. |
## Zobacz także

* Przestrzeń nazw [System::Drawing](../)
* Biblioteka [Aspose.Slides](../../)