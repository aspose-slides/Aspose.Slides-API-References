---
title: Zip64Mode
second_title: Aspose.Slides لـ C++ مرجع API
description: يحدد متى يتم استخدام امتدادات تنسيق ZIP64 لملف OpenXML.
type: docs
weight: 1119
url: /ar/aspose.slides.export/zip64mode/
---
## Zip64Mode تعداد

يحدد متى يتم استخدام امتدادات تنسيق ZIP64 لملف OpenXML.

```cpp
enum class Zip64Mode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Never | 0 | عدم استخدام امتدادات تنسيق ZIP64. |
| IfNecessary | 1 | استخدام امتدادات تنسيق ZIP64 إذا كان ذلك ضروريًا. |
| Always | 2 | استخدام امتدادات تنسيق ZIP64 دائمًا. |

## ملاحظات

ملف OpenXML هو أرشيف ZIP له حد 4 GB (2^32 بايت) على حجم الملف غير المضغوط، حجم الملف المضغوط، وإجمالي حجم الأرشيف، بالإضافة إلى حد 65,535 (2^16-1) ملفًا في الأرشيف. تزيد امتدادات تنسيق ZIP64 هذه الحدود إلى 2^64.

## انظر أيضًا

* فضاء الاسم [Aspose::Slides::Export](../)
* مكتبة [Aspose.Slides](../../)