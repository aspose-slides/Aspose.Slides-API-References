---
title: OpenText()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يفتح الملف الموجود المحدد للقراءة النصية باستخدام ترميز UTF-8 دون مشاركة.
type: docs
weight: 261
url: /ar/system.io/file/opentext/
---
## File::OpenText(const String\&, const EncodingPtr\&) طريقة

يفتح الملف الموجود المحدد للقراءة النصية باستخدام ترميز UTF-8 دون مشاركة.

```cpp
static StreamReaderPtr System::IO::File::OpenText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسار الملف المراد فتحه |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | ترميز الأحرف المستخدم |

### قيمة الإرجاع

مؤشر مشترك إلى كائن [StreamWriter](../../streamwriter/) مرتبط بالملف المفتوح

## انظر أيضًا

* Typedef [StreamReaderPtr](../../../system/streamreaderptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* فئة [String](../../../system/string/)
* فئة [File](../)
* مساحة الاسم [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)