---
title: Convert()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar byte till tecken.
type: docs
weight: 79
url: /sv/system.text/decoder/convert/
---
## Decoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) metod

Konverterar byte till tecken.

```cpp
virtual void System::Text::Decoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte att avkoda. |
| byteIndex | int | Inmatningsbuffertens förskjutning. |
| byteCount | int | Inmatningsbuffertens storlek. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Destinationens teckenbuffert. |
| charIndex | int | Destinationens arrayoffset. |
| charCount | int | Destinationens arraystorlek. |
| flush | **bool** | Om true, rensar internt avkodartillstånd efter beräkning. |
| bytesUsed | int\& | Referens till variabel för att lagra antalet lästa byte. |
| charsUsed | int\& | Referens till variabel för att lagra antalet skrivna tecken. |
| completed | **bool**\& | Referens till variabel som ska sättas till true om inmatningsbufferten är uttömd och till false annars. |

## Decoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) metod

Konverterar byte till tecken.

```cpp
virtual void System::Text::Decoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | const **uint8_t** * | Byte att avkoda. |
| byteCount | int | Inmatningsbuffertens storlek. |
| chars | char_t * | Destinationens teckenbuffert. |
| charCount | int | Destinationens arraystorlek. |
| flush | **bool** | Om true, rensar internt avkodartillstånd efter beräkning. |
| bytesUsed | int\& | Referens till variabel för att lagra antalet lästa byte. |
| charsUsed | int\& | Referens till variabel för att lagra antalet skrivna tecken. |
| completed | **bool**\& | Referens till variabel som ska sättas till true om inmatningsbufferten är uttömd och till false annars. |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [Decoder](../)
* Namnrymd [System::Text](../../)
* Library [Aspose.Slides](../../../)