---
title: ToBase64String()
second_title: Aspose.Slides dla C++ - referencja API
description: Base-64 koduje elementy w określonej tablicy bajtów i zwraca zakodowane dane jako ciąg znaków.
type: docs
weight: 40
url: /pl/system/convert/tobase64string/
---
## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, bool) metoda

Base-64 koduje elementy w określonej tablicy bajtów i zwraca zakodowane dane jako ciąg znaków.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, bool insert_line_breaks=false)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Tablica bajtów do zakodowania |
| insert_line_breaks | **bool** | Określa, czy znaki podziału linii mają być wstawiane w ciągu wyjściowym po każdych 76 znakach base-64 |

### Wartość zwracana

Ciąg znaków zawierający zakodowaną w base-64 reprezentację tablicy wejściowej

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, bool) metoda

Base-64 koduje zakres elementów w określonej tablicy bajtów i zwraca zakodowane dane jako ciąg znaków.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, bool insert_line_breaks=false)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Tablica bajtów zawierająca zakres elementów do zakodowania |
| offset_in | int | Indeks elementu w tablicy wejściowej, od którego zaczyna się zakres do zakodowania |
| length | int | Długość zakresu elementów do zakodowania |
| insert_line_breaks | **bool** | Określa, czy znaki podziału linii mają być wstawiane w ciągu wyjściowym po każdych 76 znakach base-64 |

### Wartość zwracana

Ciąg znaków zawierający zakodowaną w base-64 reprezentację zakresu elementów tablicy wejściowej

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, Base64FormattingOptions) metoda

Base-64 koduje elementy w określonej tablicy bajtów i zwraca zakodowane dane jako ciąg znaków.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, Base64FormattingOptions options)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Tablica bajtów do zakodowania |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Określa opcje formatowania danych zakodowanych w base-64 |

### Wartość zwracana

Ciąg znaków zawierający zakodowaną w base-64 reprezentację tablicy wejściowej

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, Base64FormattingOptions) metoda

Base-64 koduje zakres elementów w określonej tablicy bajtów i zwraca zakodowane dane jako ciąg znaków.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, Base64FormattingOptions options)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Tablica bajtów zawierająca zakres elementów do zakodowania |
| offset_in | int | Indeks elementu w tablicy wejściowej, od którego zaczyna się zakres do zakodowania |
| length | int | Długość zakresu elementów do zakodowania |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Określa opcje formatowania danych zakodowanych w base-64 |

### Wartość zwracana

Ciąg znaków zawierający zakodowaną w base-64 reprezentację zakresu elementów tablicy wejściowej

## Zobacz także

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Klasa [String](../../string/)
* Struktura [Convert](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)