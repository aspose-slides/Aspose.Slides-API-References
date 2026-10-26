---
title: WriteAllLines()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ ملف نصي جديد أو يكتب فوق الملف الموجود ويكتب جميع السلاسل من مجموعة السلاسل القابلة للتعداد المحددة إليه، كل سلسلة في سطر جديد، باستخدام الترميز المحدد.
type: docs
weight: 456
url: /ar/system.io/file/writealllines/
---
## File::WriteAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) طريقة

ينشئ ملف نصي جديد أو يكتب فوق الملف الموجود ويكتب جميع السلاسل من مجموعة السلاسل القابلة للتعداد المحددة إليه، كل سلسلة في سطر جديد، باستخدام الترميز المحدد.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | الملف لإنشائه أو الكتابة فوقه |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | مجموعة قابلة للتعداد من السلاسل |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | ترميز الأحرف المراد استخدامه |

## File::WriteAllLines(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) طريقة

ينشئ ملف نصي جديد أو يكتب فوق الملف الموجود ويكتب جميع السلاسل من مصفوفة السلاسل المحددة إليه، كل سلسلة في سطر جديد، باستخدام الترميز المحدد.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const ArrayPtr<String> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | الملف لإنشائه أو الكتابة فوقه |
| contents | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | مصفوفة سلاسل |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | ترميز الأحرف المراد استخدامه |

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [EncodingPtr](../../../system/encodingptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [String](../../../system/string/)
* فئة [IEnumerable](../../../system.collections.generic/ienumerable/)
* فئة [File](../)
* مساحة الاسم [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)