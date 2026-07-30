---
title: ToByteArray()
second_title: Aspose.Slides pro C++ – reference API
description: Převádí řetězec nebo podřetězec na pole bajtů.
type: docs
weight: 508
url: /cs/system/string/tobytearray/
---
## String::ToByteArray(int32_t, int32_t, bool) const metoda

Převádí řetězec nebo podřetězec na pole bajtů.

```cpp
ArrayPtr<uint8_t> System::String::ToByteArray(int32_t startIndex=0, int32_t length=INT32_MAX, bool LE=1) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| startIndex | **int32_t** | Počáteční index podřetězce. |
| length | **int32_t** | Délka podřetězce. |
| LE | **bool** | Pokud je true, kóduje znaky pomocí malého endianu; jinak použije velký endian. |

### Návratová hodnota

[Array](../../array/) obsahující bajty představující znaky řetězce.

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Třída [String](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)