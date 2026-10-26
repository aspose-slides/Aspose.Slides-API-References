---
title: Convert()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar byte mellan två kodningar.
type: docs
weight: 378
url: /sv/system.text/encoding/convert/
---
## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&) metod


Konverterar byte mellan två kodningar.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Källkodning. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Målkodning. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Byte att konvertera. |

### Returvärde

Konverterade byte.

## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&, int, int) metod


Konverterar byte mellan två kodningar.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes, int index, int count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Källkodning. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Målkodning. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Byte att konvertera. |
| index | int | Start på utdraget. |
| count | int | Utdragets storlek. |

### Returvärde

Konverterade byte.

## Se även

* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Typdefinition [EncodingPtr](../../../system/encodingptr/)
* Klass [Encoding](../)
* Namnrymd [System::Text](../../)
* Bibliotek [Aspose.Slides](../../../)