---
title: Fallback()
second_title: Aspose.Slides C++ API referencia
description: Kezeli a kódolási hibát.
type: docs
weight: 27
url: /hu/system.text/encoderreplacementfallbackbuffer/fallback/
---
## EncoderReplacementFallbackBuffer::Fallback(char_t, int) metódus

Kezeli a kódolási hibát.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknown, int index) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| charUnknown | char_t | Ismeretlen karakter; figyelmen kívül hagyva. |
| index | int | Ismeretlen karakter pozíciója; figyelmen kívül hagyva. |

### Visszatérési érték

true, ha a helyettesítő karakterlánc meg van adva és nem üres, false egyébként.

## EncoderReplacementFallbackBuffer::Fallback(char_t, char_t, int) metódus

Kezeli a kódolási hibát.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| charUnknownHigh | char_t | A hibát kiváltó szurrogátpár magas része. |
| charUnknownLow | char_t | A hibát kiváltó szurrogátpár alacsony része. |
| index | int | Ismeretlen karakter pozíciója; figyelmen kívül hagyva. |

### Visszatérési érték

true, ha a helyettesítő karakterlánc meg van adva és nem üres, false egyébként.

## Lásd még

* Osztály [EncoderReplacementFallbackBuffer](../)
* Névtér [System::Text](../../)
* Könyvtár [Aspose.Slides](../../../)