---
title: GetByteCount()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحدد عدد البايتات المطلوبة لتشفير مخزن مؤقت.
type: docs
weight: 40
url: /ar/system.text/icuencoder/getbytecount/
---
## ICUEncoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) طريقة


يحدد عدد البايتات المطلوبة لتشفير مخزن مؤقت.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```


### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | الأحرف المراد تشفيرها. |
| index | int | [Buffer](../../../system/buffer/) الإزاحة. |
| count | int | عدد الأحرف المراد تشفيرها. |
| flush | **bool** | إذا كان true، يتم تنظيف حالة المشفر الداخلية بعد الحساب. |

### القيمة المرجعة

عدد البايتات المطلوبة لتشفير المخزن المؤقت.

## ICUEncoder::GetByteCount(const char_t *, int, bool) طريقة


يحدد عدد البايتات المطلوبة لتشفير مخزن مؤقت.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(const char_t *chars, int count, bool flush)
```


### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| chars | const char_t * | الأحرف المراد تشفيرها. |
| count | int | عدد الأحرف المراد تشفيرها. |
| flush | **bool** | إذا كان true، يتم تنظيف حالة المشفر الداخلية بعد الحساب. |

### القيمة المرجعة

عدد البايتات المطلوبة لتشفير المخزن المؤقت.

## راجع أيضًا

* نوع تعريف [ArrayPtr](../../../system/arrayptr/)
* فئة [ICUEncoder](../)
* نطاق [System::Text](../../)
* مكتبة [Aspose.Slides](../../../)