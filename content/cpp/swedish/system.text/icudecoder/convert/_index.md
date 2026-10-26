---
title: Convert()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar byte till tecken.
type: docs
weight: 66
url: /sv/system.text/icudecoder/convert/
---
## ICUDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) metod

Konverterar byte till tecken.

```cpp
virtual void System::Text::ICUDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte att avkoda. |
| byteIndex | int | Inmatningsbuffertens offset. |
| byteCount | int | Inmatningsbuffertens storlek. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Målbuffert för tecken. |
| charIndex | int | Målarayens offset. |
| charCount | int | Målarayens storlek. |
| flush | **bool** | Om true, rensar det interna avkodartillståndet efter beräkning. |
| bytesUsed | int\& | Referens till variabel för att lagra antal lästa byte. |
| charsUsed | int\& | Referens till variabel för att lagra antal skrivna tecken. |
| completed | **bool**\& | Referens till variabel som ska sättas till true om inmatningsbufferten är uttömd och annars false. |

## ICUDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) metod

Konverterar byte till tecken.

```cpp
virtual void System::Text::ICUDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | const **uint8_t** * | Byte att avkoda. |
| byteCount | int | Inmatningsbuffertens storlek. |
| chars | char_t * | Målbuffert för tecken. |
| charCount | int | Målarayens storlek. |
| flush | **bool** | Om true, rensar det interna avkodartillståndet efter beräkning. |
| bytesUsed | int\& | Referens till variabel för att lagra antal lästa byte. |
| charsUsed | int\& | Referens till variabel för att lagra antal skrivna tecken. |
| completed | **bool**\& | Referens till variabel som ska sättas till true om inmatningsbufferten är uttömd och annars false. |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* klass [ICUDecoder](../)
* namnrymd [System::Text](../../)
* bibliotek [Aspose.Slides](../../../)