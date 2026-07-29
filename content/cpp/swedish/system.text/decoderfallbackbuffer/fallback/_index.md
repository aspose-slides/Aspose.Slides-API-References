---
title: Fallback()
second_title: Aspose.Slides för C++ API-referens
description: Implementerar den faktiska återfallsproceduren.
type: docs
weight: 14
url: /sv/system.text/decoderfallbackbuffer/fallback/
---
## DecoderFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) metod

Implementerar den faktiska återfallsproceduren.

```cpp
virtual bool System::Text::DecoderFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) av byte inklusive den som avkodaren misslyckas med att avkoda. |
| index | int | [Index](../../../system/index/) av byte som utlöste felet. |

### Returvärde

True om bufferten bearbetar okända byte, false om den ignorerar dem.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [DecoderFallbackBuffer](../)
* Namnrymd [System::Text](../../)
* Bibliotek [Aspose.Slides](../../../)