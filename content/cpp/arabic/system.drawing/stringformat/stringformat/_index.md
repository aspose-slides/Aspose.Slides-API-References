---
title: StringFormat()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: ينشئ نسخة جديدة من فئة StringFormat.
type: docs
weight: 1
url: /ar/system.drawing/stringformat/stringformat/
---
## StringFormat::StringFormat() المُنشئ

ينشئ نسخة جديدة من الفئة [StringFormat](../).

```cpp
System::Drawing::StringFormat::StringFormat()
```

## StringFormat::StringFormat(StringFormatFlags, int32_t) المُنشئ

ينشئ نسخة جديدة من الفئة [StringFormat](../) مع أعلام التنسيق المحددة واللغة.

```cpp
System::Drawing::StringFormat::StringFormat(StringFormatFlags options, int32_t language=0)
```

### المُعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [StringFormatFlags](../../stringformatflags/) | تركيبة بتية من قيم تعداد StringFormatFlags تحدد تنسيق السلسلة الذي سيمثله الكائن الذي يتم إنشاؤه |
| language | **int32_t** | لغة النص |

## StringFormat::StringFormat(const SharedPtr\<StringFormat\>\&) المُنشئ

منشئ النسخ.

```cpp
System::Drawing::StringFormat::StringFormat(const SharedPtr<StringFormat> &format)
```

### المُعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| format | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../)\>\& | كائن [StringFormat](../) للنسخ منه |

## انظر أيضًا

* التعداد [StringFormatFlags](../../stringformatflags/)
* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* الفئة [StringFormat](../)
* النطاق [System::Drawing](../../)
* المكتبة [Aspose.Slides](../../../)