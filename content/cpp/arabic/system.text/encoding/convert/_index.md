---
title: Convert()
second_title: Aspose.Slides for C++ مرجع API
description: يقوم بتحويل البايتات بين ترميزين.
type: docs
weight: 378
url: /ar/system.text/encoding/convert/
---
## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&) طريقة

يقوم بتحويل البايتات بين ترميزين.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | ترميز المصدر. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | ترميز الوجهة. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | البايتات للتحويل. |

### قيمة الإرجاع

البايتات المحوّلة.

## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&, int, int) طريقة

يقوم بتحويل البايتات بين ترميزين.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes, int index, int count)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | ترميز المصدر. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | ترميز الوجهة. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | البايتات للتحويل. |
| index | int | بداية القطعة. |
| count | int | حجم القطعة. |

### قيمة الإرجاع

البايتات المحوّلة.

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)