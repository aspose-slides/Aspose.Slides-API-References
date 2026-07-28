---
title: Guid
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Reprezentuje globalnie unikalny identyfikator. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub przez referencję. Nigdy nie używaj klasy System::SmartPtr do zarządzania obiektami tego typu."
type: docs
weight: 885
url: /pl/system/guid/
---
## Guid klasa

Reprezentuje globalnie unikalny identyfikator. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub przez referencję. Nigdy nie używaj klasy [System::SmartPtr](../smartptr/) do zarządzania obiektami tego typu.

```cpp
class Guid
```

## Metody

| Metoda | Opis |
| --- | --- |
| int [CompareTo](./compareto/)(const [Guid](./)\&) const | Wykonuje arytmetyczne porównanie GUIDów reprezentowanych przez bieżący i określony obiekt. |
| **bool** [Equals](./equals/)(const [Guid](./)\&) const | Określa, czy GUIDs reprezentowane przez bieżący i określony obiekt są równe. |
| int [GetHashCode](./gethashcode/)() const | Zwraca kod skrótu dla bieżącego obiektu. |
|  [Guid](./guid/)() | Tworzy obiekt, który reprezentuje GUID składający się wyłącznie z zer. |
|  [Guid](./guid/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Tworzy obiekt, który reprezentuje GUID określony jako tablica wartości całkowitych bez znaku 8-bitowych. |
|  [Guid](./guid/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Tworzy obiekt, który reprezentuje GUID określony jako widok tablicy wartości całkowitych bez znaku 8-bitowych. |
|  [Guid](./guid/)(const [String](../string/)\&) | Tworzy obiekt, który reprezentuje GUID określony jako ciąg znaków. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Tworzy instancję klasy [Guid](./) z podanych składników GUID. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const System::Details::ArrayView\<**uint8_t**\>\&) | Tworzy instancję klasy [Guid](./) z podanych składników GUID. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | Tworzy instancję klasy [Guid](./) z podanych liczb całkowitych bez znaku i bajtów. |
|  [Guid](./guid/)(**uint32_t**, **uint16_t**, **uint16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | Tworzy instancję klasy [Guid](./) z podanych liczb całkowitych bez znaku i bajtów. |
|  [Guid](./guid/)(const [Guid](./)\&) | Tworzy obiekt, który reprezentuje ten sam GUID co określony obiekt. |
| static [Guid](./) [NewGuid](./newguid/)() | Generuje nowy GUID i zwraca obiekt [Guid](./) go reprezentujący. |
| **bool** [operator!=](./operator_not_equal/)(const [Guid](./)\&) const | Określa, czy GUIDs reprezentowane przez bieżący i określony obiekt nie są równe. |
| [Guid](./)\& [operator=](./operator_equal/)(const [Guid](./)\&) | Przypisuje bieżącemu obiektowi wartość GUID reprezentowaną przez określony obiekt [Guid](./). |
| **bool** [operator==](./operator_equal_equal/)(const [Guid](./)\&) const | Określa, czy GUIDs reprezentowane przez bieżący i określony obiekt są równe. |
| static [Guid](./) [Parse](./parse/)(const [String](../string/)\&) | Konwertuje określone łańcuchowe przedstawienie GUID na odpowiedni obiekt [Guid](./). |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)() const | Konwertuje GUID reprezentowany przez bieżący obiekt na tablicę bajtów. |
| [String](../string/) [ToString](./tostring/)() const | Konwertuje GUID reprezentowany przez bieżący obiekt na jego łańcuchową reprezentację. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Konwertuje GUID reprezentowany przez bieżący obiekt na jego łańcuchową reprezentację przy użyciu określonego formatu ciągu. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Konwertuje GUID reprezentowany przez bieżący obiekt na jego łańcuchową reprezentację przy użyciu określonego formatu ciągu i kultury. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Guid](./)\&) | Próbuje skonwertować określony łańcuch na obiekt [Guid](./). |
|  [~Guid](./~guid/)() | Destruktor. |

## Pola

| Pole | Opis |
| --- | --- |
| static [Empty](./empty/) | Reprezentuje GUID o wartości 0. |

## Zobacz także

* przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)