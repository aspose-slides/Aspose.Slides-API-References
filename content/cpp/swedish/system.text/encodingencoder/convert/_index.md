---
title: Convert()
second_title: Aspose.Slides för C++ API-Referens
description: Konverterar tecken till byte.
type: docs
weight: 1
url: /sv/system.text/encodingencoder/convert/
---
## EncodingEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int&, int&, bool&) metod

Konverterar tecken till byte.

```cpp
virtual void System::Text::EncodingEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | const char_t * | Tecken att koda. |
| charCount | int | Storlek på inmatningsbuffert. |
| bytes | **uint8_t** * | Destinationens bytebuffert. |
| byteCount | int | Storlek på destinationsarray. |
| flush | **bool** | Om true rensar intern kodartillstånd efter beräkning. |
| charsUsed | int\& | Referens till variabel för att lagra antalet lästa tecken. |
| bytesUsed | int\& | Referens till variabel för att lagra antalet skrivna byte. |
| completed | **bool**\& | Referens till variabel som ska sättas till true om inmatningsbufferten är uttömd och till false annars. |

## EncodingEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) metod

Konverterar tecken till byte.

```cpp
virtual void System::Text::EncodingEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tecken att koda. |
| charIndex | int | Förskjutning för inmatningsbuffert. |
| charCount | int | Storlek på inmatningsbuffert. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Destinationens bytebuffert. |
| byteIndex | int | Förskjutning för destinationsarray. |
| byteCount | int | Storlek på destinationsarray. |
| flush | **bool** | Om true rensar intern kodartillstånd efter beräkning. |
| charsUsed | int\& | Referens till variabel för att lagra antalet lästa tecken. |
| bytesUsed | int\& | Referens till variabel för att lagra antalet skrivna byte. |
| completed | **bool**\& | Referens till variabel som ska sättas till true om inmatningsbufferten är uttömd och till false annars. |

## Se också

* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Klass [EncodingEncoder](../)
* Namnrymd [System::Text](../../)
* Bibliotek [Aspose.Slides](../../../)