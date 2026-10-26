---
title: GetChars()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar tecknen som bildas genom att avkoda en buffer.
type: docs
weight: 53
url: /sv/system.text/icudecoder/getchars/
---
## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) metod

Hämtar tecknen som bildas genom att avkoda en buffer.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte att avkoda. |
| byteIndex | int | Indata buffertoffset. |
| byteCount | int | Storlek på indatabuffert. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Målbuffert för tecken. |
| charIndex | int | Målarrayens förskjutning. |

### Returvärde

Antal tecken som skrivits.

## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) metod

Hämtar tecknen som bildas genom att avkoda en buffer.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte att avkoda. |
| byteIndex | int | Indata buffertoffset. |
| byteCount | int | Storlek på indatabuffert. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Målbuffert för tecken. |
| charIndex | int | Målarrayens förskjutning. |
| flush | **bool** | Om true, rensar det interna avkodartillståndet efter beräkning. |

### Returvärde

Antal tecken som skrivits.

## ICUDecoder::GetChars(const uint8_t *, int, char_t *, int, bool) metod

Hämtar tecknen som bildas genom att avkoda en buffer.

```cpp
virtual int System::Text::ICUDecoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | const **uint8_t** * | Byte att avkoda. |
| byteCount | int | Storlek på indatabuffert. |
| chars | char_t * | Målbuffert för tecken. |
| charCount | int | Målarrayens storlek. |
| flush | **bool** | Om true, rensar det interna avkodartillståndet efter beräkning. |

### Returvärde

Antal tecken som skrivits.

## Se också

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [ICUDecoder](../)
* Namnrymd [System::Text](../../)
* Bibliotek [Aspose.Slides](../../../)