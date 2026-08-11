---
title: ReadLines()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يقوم بقراءة محتوى ملف النص المحدد سطرًا بسطر باستخدام ترميز الأحرف المحدد ويعيد مجموعة قابلة للتعداد من السلاسل حيث يمثل كل عنصر سطرًا واحدًا من محتوى الملف
type: docs
weight: 326
url: /ar/system.io/file/readlines/
---
## File::ReadLines(const String\&, const EncodingPtr\&) طريقة

يقوم بقراءة محتوى ملف النص المحدد سطرًا بسطر باستخدام ترميز الأحرف المحدد ويعيد مجموعة قابلة للتعداد من السلاسل، حيث يمثل كل عنصر سطرًا واحدًا من محتوى الملف.

```cpp
static SharedPtr<Collections::Generic::IEnumerable<String>> System::IO::File::ReadLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسار الملف للقراءة |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | ترميز الأحرف المستخدم |

### قيمة الإرجاع

مجموعة قابلة للتعداد من السلاسل تمثل محتوى الملف المحدد

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* فئة [IEnumerable](../../../system.collections.generic/ienumerable/)
* فئة [String](../../../system/string/)
* فئة [File](../)
* نطاق [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)