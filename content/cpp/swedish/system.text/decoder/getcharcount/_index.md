---
title: GetCharCount()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar antalet tecken som behövs för att avkoda en buffert.
type: docs
weight: 40
url: /sv/system.text/decoder/getcharcount/
---
## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) metod

Hämtar antalet tecken som behövs för att avkoda en buffert.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte att avkoda. |
| index | int | [Buffer](../../../system/buffer/) förskjutning. |
| count | int | Antal byte att avkoda. |

### Returvärde

Antal tecken som krävs för att avkoda bufferten.

## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) metod

Hämtar antalet tecken som behövs för att avkoda en buffert.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte att avkoda. |
| index | int | [Buffer](../../../system/buffer/) förskjutning. |
| count | int | Antal byte att avkoda. |
| flush | **bool** | Om true, rensar intern dekoderstatus efter beräkning. |

### Returvärde

Antal tecken som krävs för att avkoda bufferten.

## Decoder::GetCharCount(const uint8_t *, int, bool) metod

Hämtar antalet tecken som behövs för att avkoda en buffert.

```cpp
virtual int System::Text::Decoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | const **uint8_t** * | Byte att avkoda. |
| count | int | Antal byte att avkoda. |
| flush | **bool** | Om true, rensar intern dekoderstatus efter beräkning. |

### Returvärde

Antal tecken som krävs för att avkoda bufferten.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Decoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)