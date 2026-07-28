---
title: Fallback()
second_title: Aspose.Slides C++ API referencia
description: Kezeli a kódolási hibát.
type: docs
weight: 27
url: /hu/system.text/encoderexceptionfallbackbuffer/fallback/
---
## EncoderExceptionFallbackBuffer::Fallback(char_t, int) metódus


Kezeli a kódolási hibát.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknown, int index) override
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| charUnknown | char_t | Ismeretlen karakterek; figyelmen kívül hagyva. |
| index | int | Ismeretlen karakterek eltolása; figyelmen kívül hagyva. |

### Visszatérési érték

Soha nem tér vissza, helyette kivételt dob.

## EncoderExceptionFallbackBuffer::Fallback(char_t, char_t, int) metódus


Kezeli a kódolási hibát.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| charUnknownHigh | char_t | A hibát kiváltó surrogát pár magas része. |
| charUnknownLow | char_t | A hibát kiváltó surrogát pár alacsony része. |
| index | int | Ismeretlen karakter eltolása; figyelmen kívül hagyva. |

### Visszatérési érték

Soha nem tér vissza, helyette kivételt dob.

## Lásd még

* Osztály [EncoderExceptionFallbackBuffer](../)
* Névtere [System::Text](../../)
* Könyvtár [Aspose.Slides](../../../)