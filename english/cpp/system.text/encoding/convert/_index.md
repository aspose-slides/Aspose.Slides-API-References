---
title: Convert()
second_title: Aspose.Slides for C++ API Reference
description: Converts bytes between two encodings.
type: docs
weight: 378
url: /cpp/system.text/encoding/convert/
---
## Encoding::Convert(const [EncodingPtr](../../../system/encodingptr/)\&, const [EncodingPtr](../../../system/encodingptr/)\&, const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\&) method


Converts bytes between two encodings.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Source encoding. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Destination encoding. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Bytes to convert. |

### Return Value

Converted bytes.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
## Encoding::Convert(const [EncodingPtr](../../../system/encodingptr/)\&, const [EncodingPtr](../../../system/encodingptr/)\&, const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\&, int, int) method


Converts bytes between two encodings.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes, int index, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Source encoding. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Destination encoding. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Bytes to convert. |
| index | int | Slice beginning. |
| count | int | Slice size. |

### Return Value

Converted bytes.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
