---
title: FileShare
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد نوع الوصول الذي يمكن لكائنات FileStream الأخرى أن تحصل عليه لملف يتم فتحه.
type: docs
weight: 534
url: /ar/system.io/fileshare/
---
## FileShare تعداد

يحدد نوع الوصول الذي يمكن لكائنات [FileStream](../filestream/) الأخرى أن تحصل عليه لملف يتم فتحه.

```cpp
enum class FileShare
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | 0 | بدون وصول. |
| Read | 1 | وصول للقراءة فقط. |
| Write | 2 | وصول للكتابة فقط. |
| ReadWrite | 3 | وصول للقراءة والكتابة. |
| Delete | 4 | يمكن حذف الملف. |
| Inheritable | 16 | يجعل مقبض الملف قابلاً للتوارث من قبل عمليات الطفل. |

## انظر أيضًا

* المساحة الاسمية [System::IO](../)
* المكتبة [Aspose.Slides](../../)