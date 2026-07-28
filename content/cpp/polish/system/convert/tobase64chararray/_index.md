---
title: ToBase64CharArray()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Base-64 koduje zakres elementów w określonej tablicy bajtów i zapisuje zakodowane dane jako tablicę znaków Unicode.
type: docs
weight: 27
url: /pl/system/convert/tobase64chararray/
---
## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char16_t\>\&, int, bool) metoda


Base-64 koduje zakres elementów w określonej tablicy bajtów i zapisuje zakodowane dane jako tablicę znaków Unicode.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char16_t> &out_array, int offset_out, bool insert_line_breaks=false)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Tablica bajtów zawierająca zakres elementów do zakodowania |
| offset_in | int | Indeks elementu w tablicy wejściowej, od którego zaczyna się zakres do zakodowania |
| length | int | Długość zakresu elementów do zakodowania |
| out_array | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | Stały odwołanie do tablicy wyjściowej, do której mają zostać zapisane wynikowe dane |
| offset_out | int | Indeks w tablicy wyjściowej, od którego rozpocząć zapisywanie wynikowych danych |
| insert_line_breaks | **bool** | Określa, czy znaki podziału linii mają być wstawiane w tablicy wyjściowej po każdych 76 znakach base-64 |

### Wartość zwracana

Liczba znaków zapisanych w tablicy wyjściowej

## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char_t\>\&, int, Base64FormattingOptions) metoda


Base-64 koduje zakres elementów w określonej tablicy bajtów i zapisuje zakodowane dane jako tablicę znaków Unicode.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char_t> &out_array, int offset_out, Base64FormattingOptions options)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Tablica bajtów zawierająca zakres elementów do zakodowania |
| offset_in | int | Indeks elementu w tablicy wejściowej, od którego zaczyna się zakres do zakodowania |
| length | int | Długość zakresu elementów do zakodowania |
| out_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Stały odwołanie do tablicy wyjściowej, do której mają zostać zapisane wynikowe dane |
| offset_out | int | Indeks w tablicy wyjściowej, od którego rozpocząć zapisywanie wynikowych danych |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Określa opcje formatowania danych zakodowanych w base-64 |

### Wartość zwracana

Liczba znaków zapisanych w tablicy wyjściowej

## Zobacz także

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)