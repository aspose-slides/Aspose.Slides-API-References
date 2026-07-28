---
title: ToString()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Konwertuje wszystkie wartości określonej tablicy bajtów na ich szesnastkową reprezentację w formie łańcucha znaków. Wielkość liter używanych w notacji szesnastkowej oraz separator wstawiany pomiędzy każdą parą sąsiadujących bajtów są określane za pomocą odpowiednich argumentów.
type: docs
weight: 157
url: /pl/system/bitconverter/tostring/
---
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, bool, const String\&) metoda

Konwertuje wszystkie wartości określonej tablicy bajtów na ich szesnastkową reprezentację w formie łańcucha znaków. Wielkość liter używanych w notacji szesnastkowej oraz separator wstawiany pomiędzy każdą parą sąsiadujących bajtów są określane za pomocą odpowiednich argumentów.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, bool uppercase=1, const String &separator=u"-")
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) zawierający bajty do konwersji |
| uppercase | **bool** | Określa wielkość liter używanych w wynikowej reprezentacji szesnastkowej |
| separator | const [String](../../string/)\& | Łańcuch znaków używany jako separator wstawiany pomiędzy każdą parą sąsiadujących bajtów w wynikowym łańcuchu |

### Wartość zwracana

[String](../../string/) zawierający szesnastkową reprezentację określonej tablicy bajtów

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int) metoda

Konwertuje wartości określonej tablicy bajtów na ich szesnastkową reprezentację zaczynając od podanego indeksu.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) zawierający bajty do konwersji |
| startIndex | int | [Index](../../index/) w określonej tablicy, od którego rozpocząć konwersję |

### Wartość zwracana

[String](../../string/) zawierający szesnastkową reprezentację określonego zakresu elementów w podanej tablicy

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int, int) metoda

Konwertuje zakres wartości określonej tablicy bajtów na ich szesnastkową reprezentację.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex, int length)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) zawierający bajty do konwersji |
| startIndex | int | [Index](../../index/) w określonej tablicy, od którego zaczyna się zakres elementów bajtów do konwersji |
| length | int | Długość zakresu elementów tablicy bajtów do konwersji |

### Wartość zwracana

[String](../../string/) zawierający szesnastkową reprezentację określonego zakresu elementów w podanej tablicy

## Zobacz też

* Definicja typu [ArrayPtr](../../arrayptr/)
* Klasa [String](../../string/)
* Klasa [BitConverter](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)