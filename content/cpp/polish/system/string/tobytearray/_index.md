---
title: ToByteArray()
second_title: Odwołanie API Aspose.Slides dla C++
description: Konwertuje string lub podciąg na tablicę bajtów.
type: docs
weight: 508
url: /pl/system/string/tobytearray/
---
## String::ToByteArray(int32_t, int32_t, bool) const metoda

Konwertuje string lub podciąg na tablicę bajtów.

```cpp
ArrayPtr<uint8_t> System::String::ToByteArray(int32_t startIndex=0, int32_t length=INT32_MAX, bool LE=1) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| startIndex | **int32_t** | Indeks początkowy podciągu. |
| length | **int32_t** | Długość podciągu. |
| LE | **bool** | Jeśli true, koduje znaki używając małego endianu; w przeciwnym razie używa dużego endianu. |

### Wartość zwracana

[Array](../../array/) zawierający bajty reprezentujące znaki stringa.

## Zobacz także

* Typedef [ArrayPtr](../../arrayptr/)
* Klasa [String](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)