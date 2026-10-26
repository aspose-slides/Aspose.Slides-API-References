---
title: CopyTo()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينسخ الملف الذي يمثله الكائن الحالي إلى الموقع المحدد. إذا كان ملف الوجهة موجودًا بالفعل، فإن عملية النسخ تفشل.
type: docs
weight: 105
url: /ar/system.io/fileinfo/copyto/
---
## FileInfo::CopyTo(const String\&) الطريقة

ينسخ الملف الذي يمثله الكائن الحالي إلى الموقع المحدد. إذا كان ملف الوجهة موجودًا بالفعل، فإن النسخ يفشل.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | اسم ملف الوجهة |

### قيمة الإرجاع

كائن [FileInfo](../) يمثل النسخة

## FileInfo::CopyTo(const String\&, bool) الطريقة

ينسخ الملف الذي يمثله الكائن الحالي إلى الموقع المحدد. يحدد أحد المعاملات ما إذا كان يجب استبدال ملف الوجهة الموجود.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName, bool overwrite)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | اسم ملف الوجهة |
| overwrite | **bool** | True إذا كان يجب استبدال ملف الوجهة الموجود، false إذا يجب أن يفشل النسخ إذا كان ملف الوجهة موجودًا بالفعل |

### قيمة الإرجاع

كائن [FileInfo](../) يمثل النسخة

## انظر أيضًا

* تعريف نوع [FileInfoPtr](../../../system/fileinfoptr/)
* فئة [String](../../../system/string/)
* فئة [FileInfo](../)
* نطاق [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)