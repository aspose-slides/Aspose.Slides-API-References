---
title: ToByteArray()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar en sträng eller delsträng till en bytearray.
type: docs
weight: 508
url: /sv/system/string/tobytearray/
---
## String::ToByteArray(int32_t, int32_t, bool) const metod

Konverterar en sträng eller delsträng till en bytearray.

```cpp
ArrayPtr<uint8_t> System::String::ToByteArray(int32_t startIndex=0, int32_t length=INT32_MAX, bool LE=1) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | **int32_t** | Startindex för delsträngen. |
| length | **int32_t** | Längd på delsträngen. |
| LE | **bool** | Om true, koda tecken med liten endianordning; annars med stor endianordning. |

### Returvärde

[Array](../../array/) som innehåller byte som representerar tecken i strängen.

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Klass [String](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)