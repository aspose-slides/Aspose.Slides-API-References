---
title: ToByteArray()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert Zeichenkette oder Teilzeichenkette in ein Byte-Array.
type: docs
weight: 508
url: /de/system/string/tobytearray/
---
## String::ToByteArray(int32_t, int32_t, bool) const Methode

Konvertiert Zeichenkette oder Teilzeichenkette in ein Byte-Array.

```cpp
ArrayPtr<uint8_t> System::String::ToByteArray(int32_t startIndex=0, int32_t length=INT32_MAX, bool LE=1) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startIndex | **int32_t** | Startindex der Teilzeichenkette. |
| length | **int32_t** | Länge der Teilzeichenkette. |
| LE | **bool** | Falls true, kodieren Sie Zeichen mit Little Endian; andernfalls verwenden Sie Big Endian. |

### Rückgabewert

[Array](../../array/) mit Bytes, die die Zeichen der Zeichenkette darstellen.

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [String](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)