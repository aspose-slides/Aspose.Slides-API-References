---
title: GetCharCount()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يعيد عدد الأحرف المطلوبة لفك تشفير المخزن المؤقت.
type: docs
weight: 40
url: /ar/system.text/icudecoder/getcharcount/
---
## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) طريقة

Gets the number of characters needed to decode a buffer.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | البايتات لفك الترميز. |
| index | int | [Buffer](../../../system/buffer/) الإزاحة. |
| count | int | عدد البايتات لفك الترميز. |

### قيمة الإرجاع

Number of characters required to decode the buffer.

## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) طريقة

Gets the number of characters needed to decode a buffer.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | البايتات لفك الترميز. |
| index | int | [Buffer](../../../system/buffer/) الإزاحة. |
| count | int | عدد البايتات لفك الترميز. |
| flush | **bool** | إذا كان true، ينظف حالة الفاكشف الداخلية بعد الحساب. |

### قيمة الإرجاع

Number of characters required to decode the buffer.

## ICUDecoder::GetCharCount(const uint8_t *, int, bool) طريقة

Gets the number of characters needed to decode a buffer.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | البايتات لفك الترميز. |
| count | int | عدد البايتات لفك الترميز. |
| flush | **bool** | إذا كان true، ينظف حالة الفاكشف الداخلية بعد الحساب. |

### قيمة الإرجاع

Number of characters required to decode the buffer.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* الفئة [ICUDecoder](../)
* النطاق [System::Text](../../)
* المكتبة [Aspose.Slides](../../../)