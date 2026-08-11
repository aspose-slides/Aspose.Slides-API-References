---
title: GetByteCount()
second_title: مرجع API Aspose.Slides للغة C++
description: يحصل على عدد البايتات المطلوبة لترميز المخزن.
type: docs
weight: 40
url: /ar/system.text/encoder/getbytecount/
---
## Encoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) طريقة

يحصل على عدد البايتات المطلوبة لترميز المخزن.

```cpp
virtual int System::Text::Encoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | الأحرف للترميز. |
| index | int | [Buffer](../../../system/buffer/) الإزاحة. |
| count | int | عدد الأحرف للترميز. |
| flush | **bool** | إذا كان true، يتم مسح حالة الترميز الداخلية بعد الحساب. |

### قيمة الإرجاع

عدد البايتات المطلوبة لترميز المخزن.

## Encoder::GetByteCount(const char_t *, int, bool) طريقة

يحصل على عدد البايتات المطلوبة لترميز المخزن.

```cpp
virtual int System::Text::Encoder::GetByteCount(const char_t *chars, int count, bool flush)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| chars | const char_t * | الأحرف للترميز. |
| count | int | عدد الأحرف للترميز. |
| flush | **bool** | إذا كان true، يتم مسح حالة الترميز الداخلية بعد الحساب. |

### قيمة الإرجاع

عدد البايتات المطلوبة لترميز المخزن.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* الفئة [Encoder](../)
* مساحة الاسم [System::Text](../../)
* المكتبة [Aspose.Slides](../../../)