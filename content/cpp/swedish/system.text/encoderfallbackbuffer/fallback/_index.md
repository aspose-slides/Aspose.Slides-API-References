---
title: Fallback()
second_title: Aspose.Slides för C++ API-referens
description: Implementerar den faktiska återfallsproceduren.
type: docs
weight: 14
url: /sv/system.text/encoderfallbackbuffer/fallback/
---
## EncoderFallbackBuffer::Fallback(char_t, int) metod

Implementerar den faktiska återfallsproceduren.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknown, int index)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| charUnknown | char_t | Teckenkodaren misslyckas med att koda. |
| index | int | [Index](../../../system/index/) av tecken som orsakade fel. |

### Returvärde

Sant om bufferten bearbetar okända tecken, falskt om den ignorerar dem.

## EncoderFallbackBuffer::Fallback(char_t, char_t, int) metod

Implementerar den faktiska återfallsproceduren.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| charUnknownHigh | char_t | Övre delen av surrogatparet som orsakade felet. |
| charUnknownLow | char_t | Nedre delen av surrogatparet som orsakade felet. |
| index | int | [Index](../../../system/index/) av tecken som orsakade fel. |

### Returvärde

Sant om bufferten bearbetar okända tecken, falskt om den ignorerar dem.

## Se även

* Klass [EncoderFallbackBuffer](../)
* Namnrymd [System::Text](../../)
* Bibliotek [Aspose.Slides](../../../)