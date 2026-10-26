---
title: GetChars()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar tecknen som resultat av avkodning av en buffer.
type: docs
weight: 53
url: /sv/system.text/decoder/getchars/
---
## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) metod


Hämtar tecknen som resultat av avkodning av en buffer.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte att avkoda. |
| byteIndex | int | Inmatningsbuffertens offset. |
| byteCount | int | Inmatningsbuffertens storlek. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Målbuffert för tecken. |
| charIndex | int | Målarrayns offset. |

### Returvärde

Antal tecken som skrivits.

## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) metod


Hämtar tecknen som resultat av avkodning av en buffer.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte att avkoda. |
| byteIndex | int | Inmatningsbuffertens offset. |
| byteCount | int | Inmatningsbuffertens storlek. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Målbuffert för tecken. |
| charIndex | int | Målarrayns offset. |
| flush | **bool** | Om true, rensar internt avkodartillstånd efter beräkning. |

### Returvärde

Antal tecken som skrivits.

## Decoder::GetChars(const uint8_t *, int, char_t *, int, bool) metod


Hämtar tecknen som resultat av avkodning av en buffer.

```cpp
virtual int System::Text::Decoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | const **uint8_t** * | Byte att avkoda. |
| byteCount | int | Inmatningsbuffertens storlek. |
| chars | char_t * | Målbuffert för tecken. |
| charCount | int | Målarrayns storlek. |
| flush | **bool** | Om true, rensar internt avkodartillstånd efter beräkning. |

### Returvärde

Antal tecken som skrivits.

## Se även

* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Klass [Decoder](../)
* Namnrymd [System::Text](../../)
* Bibliotek [Aspose.Slides](../../../)