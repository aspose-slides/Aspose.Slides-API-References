---
title: Convert()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar byte till tecken.
type: docs
weight: 1
url: /sv/system.text/encodingdecoder/convert/
---
## EncodingDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) metod

Konverterar byte till tecken.

```cpp
void System::Text::EncodingDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | Byte att avkoda. |
| byteCount | int | Storlek på inmatningsbuffert. |
| chars | char_t * | Målbuffert för tecken. |
| charCount | int | Storlek på målarray. |
| flush | **bool** | Om true, rensar internt avkodartillstånd efter beräkning. |
| bytesUsed | int\& | Referens till variabel för att lagra antal lästa byte. |
| charsUsed | int\& | Referens till variabel för att lagra antal skrivna tecken. |
| completed | **bool**\& | Referens till variabel som ska sättas till true om inmatningsbufferten var uttömd och till false annars. |

## EncodingDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) metod

Konverterar byte till tecken.

```cpp
void System::Text::EncodingDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte att avkoda. |
| byteIndex | int | Offset för inmatningsbuffert. |
| byteCount | int | Storlek på inmatningsbuffert. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Målbuffert för tecken. |
| charIndex | int | Offset för målarray. |
| charCount | int | Storlek på målarray. |
| flush | **bool** | Om true, rensar internt avkodartillstånd efter beräkning. |
| bytesUsed | int\& | Referens till variabel för att lagra antal lästa byte. |
| charsUsed | int\& | Referens till variabel för att lagra antal skrivna tecken. |
| completed | **bool**\& | Referens till variabel som ska sättas till true om inmatningsbufferten var uttömd och till false annars. |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [EncodingDecoder](../)
* Namnrymd [System::Text](../../)
* Bibliotek [Aspose.Slides](../../../)