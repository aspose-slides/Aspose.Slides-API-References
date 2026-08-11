---
title: Copy()
second_title: مرجع API الخاص بـ Aspose.Slides للـ C++
description: ينسخ الملف المحدد إلى الموقع المحدد. إذا كان ملف الوجهة موجودًا بالفعل، تحدد إحدى المعلمات ما إذا كان يجب استبداله.
type: docs
weight: 40
url: /ar/system.io/file/copy/
---
## File::Copy(const String\&, const String\&, bool) طريقة

ينسخ الملف المحدد إلى الموقع المحدد. إذا كان ملف الوجهة موجودًا بالفعل، تحدد إحدى المعلمات ما إذا كان يجب استبداله.

```cpp
static void System::IO::File::Copy(const String &sourceFileName, const String &destFileName, bool overwrite=false)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | مسار الملف لتنسخه |
| destFileName | const [String](../../../system/string/)\& | مسار الموقع الجديد للملف المنسوخ |
| overwrite | **bool** | True إذا كان يجب استبدال ملف الوجهة الموجود، false إذا يجب أن يفشل النسخ إذا كان ملف الوجهة موجودًا مسبقًا |

## انظر أيضًا

* فئة [String](../../../system/string/)
* فئة [File](../)
* نطاق [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)