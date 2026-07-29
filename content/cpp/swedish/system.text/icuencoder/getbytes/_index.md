---
title: GetBytes()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar de byte som erhålls genom att koda en buffert.
type: docs
weight: 53
url: /sv/system.text/icuencoder/getbytes/
---
## ICUEncoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) metod

Hämtar de byte som erhålls genom att koda en buffert.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tecken att koda. |
| charIndex | int | Källarrayens offset. |
| charCount | int | Källundermängdens längd. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Målbytebuffert. |
| byteIndex | int | Målbuffertens offset. |
| flush | **bool** | Om true, rensar det interna kodartillståndet efter beräkning. |

### Returvärde

Antal bytes skrivna.

## ICUEncoder::GetBytes(const char_t *, int, uint8_t *, int, bool) metod

Hämtar de byte som erhålls genom att koda en buffert.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | const char_t * | Tecken att koda. |
| charCount | int | Källarrayens längd. |
| bytes | **uint8_t** * | Målbytebuffert. |
| byteCount | int | Målbuffertens storlek. |
| flush | **bool** | Om true, rensar det interna kodartillståndet efter beräkning. |

### Returvärde

Antal bytes skrivna.

## Se även

* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Klass [ICUEncoder](../)
* Namnrymd [System::Text](../../)
* Bibliotek [Aspose.Slides](../../../)