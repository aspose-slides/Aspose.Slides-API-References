---
title: Fallback()
second_title: Aspose.Slides C++ API hivatkozás
description: Megvalósítja a tényleges visszatérési eljárást.
type: docs
weight: 14
url: /hu/system.text/decoderfallbackbuffer/fallback/
---
## DecoderFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) metódus

Megvalósítja a tényleges visszatérési eljárást.

```cpp
virtual bool System::Text::DecoderFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) a byte-ok közül, beleértve azt a byte-ot, amelyet a dekóder nem tud dekódolni. |
| index | int | [Index](../../../system/index/) a hibát kiváltó byte-ot. |

### Visszatérési érték

Igaz, ha a puffer feldolgozza az ismeretlen byte-okat, hamis, ha figyelmen kívül hagyja azokat.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [DecoderFallbackBuffer](../)
* Névterület [System::Text](../../)
* Könyvtár [Aspose.Slides](../../../)