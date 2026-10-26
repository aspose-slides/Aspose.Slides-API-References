---
title: Zip64Mode
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يحدد متى يجب استخدام امتدادات تنسيق ZIP64 لملف OpenXML.
type: docs
url: /ar/com.aspose.slides/zip64mode/
---
**الوراثة:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

يحدد متى يجب استخدام امتدادات تنسيق ZIP64 لملف OpenXML.

--------------------

ملف OpenXML هو أرشيف ZIP له حد 4 GB (2^32 بايت) على حجم الملف غير المضغوط، حجم الملف المضغوط، وإجمالي حجم الأرشيف، بالإضافة إلى حد 65 535 (2^16-1) ملفًا في الأرشيف. تزيد امتدادات تنسيق ZIP64 الحدود إلى 2^64.
## الحقول

| الحقل | الوصف |
| --- | --- |
| [Never](#Never) | لا تستخدم امتدادات تنسيق ZIP64. |
| [IfNecessary](#IfNecessary) | استخدم امتدادات تنسيق ZIP64 إذا لزم الأمر. |
| [Always](#Always) | استخدم دائمًا امتدادات تنسيق ZIP64. |
### Never {#Never}
```
public static final int Never
```

لا تستخدم امتدادات تنسيق ZIP64.

### IfNecessary {#IfNecessary}
```
public static final int IfNecessary
```

استخدم امتدادات تنسيق ZIP64 إذا لزم الأمر.

### Always {#Always}
```
public static final int Always
```

استخدم دائمًا امتدادات تنسيق ZIP64.