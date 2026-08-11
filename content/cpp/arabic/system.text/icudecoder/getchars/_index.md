---
title: GetChars()
second_title: Aspose.Slides لواجهة برمجة تطبيقات C++
description: احصل على الأحرف الناتجة عن فك ترميز المخزن المؤقت.
type: docs
weight: 53
url: /ar/system.text/icudecoder/getchars/
---
## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) طريقة

احصل على الأحرف التي تنتج عن فك ترميز مخزن مؤقت.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes to decode. |
| byteIndex | int | Input buffer offset. |
| byteCount | int | Input buffer size. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Destination character buffer. |
| charIndex | int | Destination array offset. |

### قيمة الإرجاع

عدد الأحرف المكتوبة.

## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) طريقة

احصل على الأحرف التي تنتج عن فك ترميز مخزن مؤقت.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes to decode. |
| byteIndex | int | Input buffer offset. |
| byteCount | int | Input buffer size. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Destination character buffer. |
| charIndex | int | Destination array offset. |
| flush | **bool** | إذا كان true، ينظف حالة فك الترميز الداخلية بعد الحساب. |

### قيمة الإرجاع

عدد الأحرف المكتوبة.

## ICUDecoder::GetChars(const uint8_t *, int, char_t *, int, bool) طريقة

احصل على الأحرف التي تنتج عن فك ترميز مخزن مؤقت.

```cpp
virtual int System::Text::ICUDecoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes to decode. |
| byteCount | int | Input buffer size. |
| chars | char_t * | Destination character buffer. |
| charCount | int | Destination array size. |
| flush | **bool** | إذا كان true، ينظف حالة فك الترميز الداخلية بعد الحساب. |

### قيمة الإرجاع

عدد الأحرف المكتوبة.

## انظر أيضاً

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)