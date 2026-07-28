---
title: Fallback()
second_title: Aspose.Slides C++ API hivatkozás
description: Megvalósítja a tényleges visszaesési eljárást.
type: docs
weight: 14
url: /hu/system.text/encoderfallbackbuffer/fallback/
---
## EncoderFallbackBuffer::Fallback(char_t, int) metódus


Megvalósítja a tényleges visszaesési eljárást.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknown, int index)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| charUnknown | char_t | Az karakterkódoló nem képes kódolni. |
| index | int | [Index](../../../system/index/) a hibát kiváltó karakter. |

### Visszatérési érték

True, ha a puffer feldolgozza az ismeretlen karaktereket, false, ha figyelmen kívül hagyja őket.

## EncoderFallbackBuffer::Fallback(char_t, char_t, int) metódus


Megvalósítja a tényleges visszaesési eljárást.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| charUnknownHigh | char_t | A hibát kiváltó helyettesítő pár magas része. |
| charUnknownLow | char_t | A hibát kiváltó helyettesítő pár alacsony része. |
| index | int | [Index](../../../system/index/) a hibát kiváltó karakter. |

### Visszatérési érték

True, ha a puffer feldolgozza az ismeretlen karaktereket, false, ha figyelmen kívül hagyja őket.

## Lásd még

* Osztály [EncoderFallbackBuffer](../)
* Névtér [System::Text](../../)
* Könyvtár [Aspose.Slides](../../../)