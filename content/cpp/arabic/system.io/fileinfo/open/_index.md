---
title: Open()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يفتح الملف الذي يمثّله الكائن الحالي في الوضع المحدد للقراءة والكتابة دون مشاركة.
type: docs
weight: 183
url: /ar/system.io/fileinfo/open/
---
## FileInfo::Open(FileMode) طريقة

يفتح الملف الذي يمثّله الكائن الحالي في الوضع المحدد للقراءة والكتابة دون مشاركة.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | يحدد الوضع الذي يُفتح به الملف |

### قيمة الإرجاع

كائن [FileStream](../../filestream/) مرتبط بالملف الذي يمثّله الكائن الحالي

## FileInfo::Open(FileMode, FileAccess) طريقة

يفتح الملف الذي يمثّله الكائن الحالي في الوضع المحدد، مع نوع الوصول المحدد ودون مشاركة.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | يحدد الوضع الذي يُفتح به الملف |
| access | [FileAccess](../../fileaccess/) | نوع الوصول المطلوب |

### قيمة الإرجاع

كائن [FileStream](../../filestream/) مرتبط بالملف الذي يمثّله الكائن الحالي

## FileInfo::Open(FileMode, FileAccess, FileShare) طريقة

يفتح الملف الذي يمثّله الكائن الحالي في الوضع المحدد، مع نوع الوصول المحدد وخيار المشاركة.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access, FileShare share)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | يحدد الوضع الذي يُفتح به الملف |
| access | [FileAccess](../../fileaccess/) | نوع الوصول المطلوب |
| share | [FileShare](../../fileshare/) | نوع الوصول الذي تملكه كائنات [FileStream](../../filestream/) الأخرى للملف المفتوح |

### قيمة الإرجاع

كائن [FileStream](../../filestream/) مرتبط بالملف الذي يمثّله الكائن الحالي

## انظر أيضاً

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* الفئة [FileInfo](../)
* النطاق [System::IO](../../)
* Library [Aspose.Slides](../../../)