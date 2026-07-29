---
title: Convert()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar tecken till byte.
type: docs
weight: 79
url: /sv/system.text/encoder/convert/
---
## Encoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) method

Konverterar tecken till byte.

```cpp
virtual void System::Text::Encoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tecken att koda. |
| charIndex | int | Inmatningsbuffertens förskjutning. |
| charCount | int | Inmatningsbuffertens storlek. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Destinationens bytebuffert. |
| byteIndex | int | Destinationens arrayförskjutning. |
| byteCount | int | Destinationens arraystorlek. |
| flush | **bool** | Om true, rensar intern encoderstatus efter beräkning. |
| charsUsed | int\& | Referens till variabel för att lagra antalet lästa tecken. |
| bytesUsed | int\& | Referens till variabel för att lagra antalet skrivna byte. |
| completed | **bool**\& | Referens till variabel som sätts till true om inmatningsbufferten är uttömd och till false annars. |

## Encoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) method

Konverterar tecken till byte.

```cpp
virtual void System::Text::Encoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | const char_t * | Tecken att koda. |
| charCount | int | Inmatningsbuffertens storlek. |
| bytes | **uint8_t** * | Destinationens bytebuffert. |
| byteCount | int | Destinationens arraystorlek. |
| flush | **bool** | Om true, rensar intern encoderstatus efter beräkning. |
| charsUsed | int\& | Referens till variabel för att lagra antalet lästa tecken. |
| bytesUsed | int\& | Referens till variabel för att lagra antalet skrivna byte. |
| completed | **bool**\& | Referens till variabel som sätts till true om inmatningsbufferten är uttömd och till false annars. |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [Encoder](../)
* Namnrymd [System::Text](../../)
* Bibliotek [Aspose.Slides](../../../)