---
title: AppendAllLines()
second_title: Aspose.Slides لمرجع API C++
description: يضيف السلاسل من مجموعة السلاسل المحددة إلى الملف المحدد باستخدام الترميز المحدد عن طريق كتابة كل سلسلة في سطر جديد. إذا لم يكن الملف المحدد موجودًا، يتم إنشاؤه. يتم إغلاق الملف بعد كتابة جميع السلاسل.
type: docs
weight: 1
url: /ar/system.io/file/appendalllines/
---
## File::AppendAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) طريقة

Appends strings from the specified collection of strings to the specified file using the specified encoding by writing each string in a new line. If the specified file does not exist, it is created. The file is closed after writing all strings.

```cpp
static void System::IO::File::AppendAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسار الملف لإضافة السلاسل إليه |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | السلاسل المراد كتابتها إلى الملف |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | ترميز الأحرف المراد استخدامه |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* فئة [String](../../../system/string/)
* فئة [IEnumerable](../../../system.collections.generic/ienumerable/)
* فئة [File](../)
* نطاق [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)