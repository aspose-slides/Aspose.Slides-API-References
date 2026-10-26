---
title: Convert()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar tecken till byte.
type: docs
weight: 66
url: /sv/system.text/icuencoder/convert/
---
## ICUEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) metod

Konverterar tecken till byte.

```cpp
virtual void System::Text::ICUEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tecken att koda. |
| charIndex | int | Indatatbuffertens förskjutning. |
| charCount | int | Indatatbuffertens storlek. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Målbuffert för byte. |
| byteIndex | int | Destinationens arrayförskjutning. |
| byteCount | int | Destinationens arraystorlek. |
| flush | **bool** | Om true, rensar det interna kodarens tillstånd efter beräkning. |
| charsUsed | int\& | Referens till variabel för att lagra antalet lästa tecken. |
| bytesUsed | int\& | Referens till variabel för att lagra antalet skrivna byte. |
| completed | **bool**\& | Referens till variabel som ska sättas till true om indatabufferten är uttömd och till false annars. |

## ICUEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) metod

Konverterar tecken till byte.

```cpp
virtual void System::Text::ICUEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Tecken att koda. |
| charCount | int | Indatatbuffertens storlek. |
| bytes | **uint8_t** * | Målbuffert för byte. |
| byteCount | int | Destinationens arraystorlek. |
| flush | **bool** | Om true, rensar det interna kodarens tillstånd efter beräkning. |
| charsUsed | int\& | Referens till variabel för att lagra antalet lästa tecken. |
| bytesUsed | int\& | Referens till variabel för att lagra antalet skrivna byte. |
| completed | **bool**\& | Referens till variabel som ska sättas till true om indatabufferten är uttömd och till false annars. |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [ICUEncoder](../)
* Namnrymd [System::Text](../../)
* Bibliotek [Aspose.Slides](../../../)