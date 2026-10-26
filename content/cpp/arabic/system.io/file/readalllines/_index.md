---
title: ReadAllLines()
second_title: مرجع API Aspose.Slides للـ C++
description: يقوم بقراءة محتوى ملف النص المحدد سطرًا بسطر إلى مصفوفة من السلاسل باستخدام ترميز الأحرف المحدد.
type: docs
weight: 300
url: /ar/system.io/file/readalllines/
---
## File::ReadAllLines(const String\&, const EncodingPtr\&) دالة

يقرأ محتوى ملف النص المحدد سطرًا بسطر إلى مصفوفة من السلاسل باستخدام ترميز الأحرف المحدد.

```cpp
static ArrayPtr<String> System::IO::File::ReadAllLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسار الملف الذي سيتم قراءته |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | ترميز الأحرف المستخدم |

### قيمة الإرجاع

مصفوفة من type string حيث يمثل كل عنصر سطرًا واحدًا من الملف المحدد

## راجع أيضاً

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف نوع [EncodingPtr](../../../system/encodingptr/)
* فئة [String](../../../system/string/)
* فئة [File](../)
* نطاق [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)