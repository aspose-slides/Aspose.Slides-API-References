---
title: KeyValuePair
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Para klucza i wartości. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub przez referencję. Nigdy nie używaj klasy System::SmartPtr do zarządzania obiektami tego typu."
type: docs
weight: 378
url: /pl/system.collections.generic/keyvaluepair/
---
## KeyValuePair klasa

Para klucza i wartości. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub przez referencję. Nigdy nie używaj klasy [System::SmartPtr](../../system/smartptr/) do zarządzania obiektami tego typu.

```cpp
template<typename TKey,typename TValue>class KeyValuePair
```

## Metody

| Metoda | Opis |
| --- | --- |
| const TKey\& [get_Key](./get_key/)() const | Zwraca klucz. |
| const TValue\& [get_Value](./get_value/)() const | Zwraca wartość. |
| int [GetHashCode](./gethashcode/)() const | Oblicza skrót pary klucz-wartość przez XOR-owanie skrótów klucza i wartości. |
| **bool** [IsNull](./isnull/)() const | Zawsze zwraca false. |
| [KeyValuePair](./keyvaluepair/)() | Inicjalizator pustej pary klucz-wartość. |
| [KeyValuePair](./keyvaluepair/)(const TKey\&, const TValue\&) | Konstruktor. |
| [KeyValuePair](./keyvaluepair/)(const std::pair\<OtherK, OtherV\>\&) | Konstruktor konwersji typu. |
| **bool** [operator<](./operator_less/)(const [KeyValuePair](./)\&) const | Łatka dla klas dziedziczących po IComparer<KeyValuePair<TKey, TValue>>, nie porównuje nic. |
| [String](../../system/string/) [ToString](./tostring/)() const | Konwertuje parę klucz-wartość na ciąg znaków. |

## Zobacz także

* Przestrzeń nazw [System::Collections::Generic](../)
* Biblioteka [Aspose.Slides](../../)