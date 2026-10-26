---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/
weight: 20
---
## max_blobs_bytes_in_memory خاصية
يحدد الحد الأقصى للحجم الكلي (بالبايت) الذي قد تحتله جميع BLOBs في الذاكرة. بشكل افتراضي، يتم تحميل جميع BLOBs
            إلى الذاكرة؛ ولا تُستَخدم آليات بديلة (مثل الملفات المؤقتة) إلا عندما يُبلّغ هذا الحد. إبقاء BLOBs في الذاكرة
            يعزز الأداء لكنه قد يؤدي إلى استهلاك عالي للذاكرة. استخدم هذه الخاصية لتكييف السلوك مع بيئتك أو متطلباتك.

### ملاحظات
يتم تجاهل هذه الخاصية إذا تم تعيين [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/ar/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) إلى false، لأن الذاكرة هي
            الموقع الوحيد المتاح للتخزين ولا يؤثر تحديد استخدام BLOB في الذاكرة.

### التعريف:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```

### انظر أيضًا
* فئة [`IBlobManagementOptions`](/slides/python-net/ar/aspose.slides/iblobmanagementoptions)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)