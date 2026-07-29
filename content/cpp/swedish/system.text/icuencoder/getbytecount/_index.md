---
title: GetByteCount()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar antalet byte som behövs för att koda en buffert.
type: docs
weight: 40
url: /sv/system.text/icuencoder/getbytecount/
---
## ICUEncoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) metod

Hämtar antalet byte som krävs för att koda en buffert.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tecken att koda. |
| index | int | [Buffer](../../../system/buffer/) förskjutning. |
| count | int | Antal tecken att koda. |
| flush | **bool** | Om true, rensar intern kodarens tillstånd efter beräkning. |

### Returvärde

Antal byte som krävs för att koda bufferten.

## ICUEncoder::GetByteCount(const char_t *, int, bool) metod

Hämtar antalet byte som krävs för att koda en buffert.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(const char_t *chars, int count, bool flush)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | const char_t * | Tecken att koda. |
| count | int | Antal tecken att koda. |
| flush | **bool** | Om true, rensar intern kodarens tillstånd efter beräkning. |

### Returvärde

Antal byte som krävs för att koda bufferten.

## Se också

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [ICUEncoder](../)
* Namnrymd [System::Text](../../)
* Bibliotek [Aspose.Slides](../../../)