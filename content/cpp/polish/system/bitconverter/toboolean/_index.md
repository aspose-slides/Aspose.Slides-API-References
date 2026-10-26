---
title: ToBoolean()
second_title: Aspose.Slides dla C++ – referencja API
description: Konwertuje jeden bajt z określonej tablicy, rozpoczynając od podanego indeksu, na wartość logiczną.
type: docs
weight: 27
url: /pl/system/bitconverter/toboolean/
---
## BitConverter::ToBoolean(const System::ArrayPtr\<uint8_t\>\&, int) metoda

Konwertuje jeden bajt z podanej tablicy zaczynając od określonego indeksu na wartość logiczną.

```cpp
static bool System::BitConverter::ToBoolean(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) zawierający bajty do konwersji |
| startIndex | int | [Index](../../index/) w tablicy, od którego rozpocząć pobieranie bajtów do konwersji |

### Wartość zwracana

[Boolean](../../boolean/) wartość wynikająca z konwersji

## BitConverter::ToBoolean(const System::Details::ArrayView\<uint8_t\>\&, int) metoda

Konwertuje jeden bajt z podanej tablicy zaczynając od określonego indeksu na wartość logiczną.

```cpp
static bool System::BitConverter::ToBoolean(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView zawierający bajty do konwersji |
| startIndex | int | [Index](../../index/) w tablicy, od którego rozpocząć pobieranie bajtów do konwersji |

### Wartość zwracana

[Boolean](../../boolean/) wartość wynikająca z konwersji

## Zobacz także

* Typedef [ArrayPtr](../../arrayptr/)
* Klasa [BitConverter](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)