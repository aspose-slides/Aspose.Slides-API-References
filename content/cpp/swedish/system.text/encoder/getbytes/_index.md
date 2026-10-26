---
title: GetBytes()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar de byte som erhålls vid kodning av en buffert.
type: docs
weight: 53
url: /sv/system.text/encoder/getbytes/
---
## Encoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) method


Hämtar de byte som erhålls vid kodning av en buffert.

```cpp
virtual int System::Text::Encoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tecken att koda. |
| charIndex | int | Förskjutning i källarrayen. |
| charCount | int | Längd på delarrayen i källan. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Målbytebuffert. |
| byteIndex | int | Förskjutning i målbufferten. |
| flush | **bool** | Om true, rensar det interna kodartillståndet efter beräkning. |

### Returvärde

Antalet skrivna byte.

## Encoder::GetBytes(const char_t *, int, uint8_t *, int, bool) method


Hämtar de byte som erhålls vid kodning av en buffert.

```cpp
virtual int System::Text::Encoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | const char_t * | Tecken att koda. |
| charCount | int | Längd på källarray. |
| bytes | **uint8_t** * | Målbytebuffert. |
| byteCount | int | Storlek på målbuffer. |
| flush | **bool** | Om true, rensar det interna kodartillståndet efter beräkning. |

### Returvärde

Antalet skrivna byte.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [Encoder](../)
* Namnrymd [System::Text](../../)
* Bibliotek [Aspose.Slides](../../../)