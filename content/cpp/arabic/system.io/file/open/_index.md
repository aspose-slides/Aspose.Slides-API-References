---
title: Open()
second_title: Aspose.Slides لمرجع API C++
description: يفتح الملف المحدد في الوضع المحدد للقراءة والكتابة دون مشاركة.
type: docs
weight: 235
url: /ar/system.io/file/open/
---
## File::Open(const String\&, FileMode) طريقة

يفتح الملف المحدد في الوضع المحدد للقراءة والكتابة دون مشاركة.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode)
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسار الملف الذي سيتم فتحه |
| mode | [FileMode](../../filemode/) | يوضح الوضع الذي يتم فتح الملف فيه |

### قيمة الإرجاع

كائن [FileStream](../../filestream/) مرتبط بالملف المفتوح

## File::Open(const String\&, FileMode, FileAccess, FileShare) طريقة

يفتح الملف المحدد في الوضع المحدد، مع نوع الوصول المحدد وخيار المشاركة.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::None)
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسار الملف الذي سيتم فتحه |
| mode | [FileMode](../../filemode/) | يوضح الوضع الذي يتم فتح الملف فيه |
| access | [FileAccess](../../fileaccess/) | نوع الوصول المطلوب |
| share | [FileShare](../../fileshare/) | نوع الوصول الذي تملكه كائنات [FileStream](../../filestream/) الأخرى للملف المفتوح |

### قيمة الإرجاع

كائن [FileStream](../../filestream/) مرتبط بالملف المفتوح

## انظر أيضاً

* تعداد [FileMode](../../filemode/)
* تعداد [FileAccess](../../fileaccess/)
* تعداد [FileShare](../../fileshare/)
* تعريف نوع [FileStreamPtr](../../../system/filestreamptr/)
* فئة [String](../../../system/string/)
* فئة [File](../)
* نطاق [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)