---
title: GetCharCount()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يُعيد عدد الأحرف المطلوبة لفك تشفير المخزن المؤقت.
type: docs
weight: 40
url: /ar/system.text/decoder/getcharcount/
---
## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) طريقة

يُعيد عدد الأحرف المطلوبة لفك تشفير المخزن المؤقت.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | البايتات التي يجب فك تشفيرها. |
| index | int | [Buffer](../../../system/buffer/) الإزاحة. |
| count | int | عدد البايتات التي يجب فك تشفيرها. |

### قيمة الإرجاع

عدد الأحرف المطلوبة لفك تشفير المخزن المؤقت.

## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) طريقة

يُعيد عدد الأحرف المطلوبة لفك تشفير المخزن المؤقت.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | البايتات التي يجب فك تشفيرها. |
| index | int | [Buffer](../../../system/buffer/) الإزاحة. |
| count | int | عدد البايتات التي يجب فك تشفيرها. |
| flush | **bool** | إذا كان true، ينظّف حالة الفك الداخلية بعد الحساب. |

### قيمة الإرجاع

عدد الأحرف المطلوبة لفك تشفير المخزن المؤقت.

## Decoder::GetCharCount(const uint8_t *, int, bool) طريقة

يُعيد عدد الأحرف المطلوبة لفك تشفير المخزن المؤقت.

```cpp
virtual int System::Text::Decoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| bytes | const **uint8_t** * | البايتات التي يجب فك تشفيرها. |
| count | int | عدد البايتات التي يجب فك تشفيرها. |
| flush | **bool** | إذا كان true، ينظّف حالة الفك الداخلية بعد الحساب. |

### قيمة الإرجاع

عدد الأحرف المطلوبة لفك تشفير المخزن المؤقت.

## انظر أيضًا

* تعريف النوع [ArrayPtr](../../../system/arrayptr/)
* فئة [Decoder](../)
* مساحة الاسم [System::Text](../../)
* مكتبة [Aspose.Slides](../../../)