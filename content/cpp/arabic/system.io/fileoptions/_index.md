---
title: FileOptions
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل خيارات متقدمة لإنشاء كائن FileStream.
type: docs
weight: 521
url: /ar/system.io/fileoptions/
---
## FileOptions تعداد

يمثل خيارات متقدمة لإنشاء كائن [FileStream](../filestream/).

```cpp
enum class FileOptions
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | 0 | بدون خيارات إضافية. |
| Encrypted | 16384 | الملف مشفر. غير مُنفّذ. |
| DeleteOnClose | 67108864 | يجب حذف الملف تلقائيًا عندما لا يكون قيد الاستخدام بعد الآن. |
| SequentialScan | 134217728 | يجب الوصول إلى الملف بشكل تسلسلي. |
| RandomAccess | 268435456 | يتم الوصول إلى الملف عشوائيًا. |
| Asynchronous | 1073741824 | يمكن استخدام الملف في عمليات الإدخال/الإخراج غير المتزامنة. |
| WriteThrough | n/a | يجب أن يتم جميع عمليات الكتابة مباشرة إلى القرص متجاوزة أي ذاكرة تخزين مؤقت وسيطة. |

## انظر أيضًا

* النطاق [System::IO](../)
* المكتبة [Aspose.Slides](../../)