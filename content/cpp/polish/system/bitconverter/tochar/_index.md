---
title: ToChar()
second_title: Aspose.Slides dla C++ – referencja API
description: Konwertuje dwa bajty z podanej tablicy, począwszy od określonego indeksu, na wartość typu char_t.
type: docs
weight: 40
url: /pl/system/bitconverter/tochar/
---
## BitConverter::ToChar(const System::ArrayPtr\<uint8_t\>\&, int) metoda

Konwertuje dwa bajty z określonej tablicy rozpoczynając od podanego indeksu na wartość typu char_t.

```cpp
static char_t System::BitConverter::ToChar(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Arguments

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) zawierający bajty do konwersji |
| startIndex | int | [Index](../../index/) w tablicy, od którego zaczyna się pobieranie bajtów do konwersji |

### Return Value

wartość char_t uzyskana w wyniku konwersji

## BitConverter::ToChar(const System::Details::ArrayView\<uint8_t\>\&, int) metoda

Konwertuje dwa bajty z określonej tablicy rozpoczynając od podanego indeksu na wartość typu char_t.

```cpp
static char_t System::BitConverter::ToChar(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Arguments

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView zawierający bajty do konwersji |
| startIndex | int | [Index](../../index/) w tablicy, od którego zaczyna się pobieranie bajtów do konwersji |

### Return Value

wartość char_t uzyskana w wyniku konwersji

## Zobacz również

* Typedef [ArrayPtr](../../arrayptr/)
* Klasa [BitConverter](../)
* Przestrzeń nazw [System](../../)
* Library [Aspose.Slides](../../../)