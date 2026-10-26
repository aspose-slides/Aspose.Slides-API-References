---
title: max_blobs_bytes_in_memory property
second_title: مرجع API Aspose.Slides للـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/
weight: 30
---
## max_blobs_bytes_in_memory property
يحدد الحد الأقصى لحجم جميع الـ BLOBs (بالبايت) التي يمكن أن تحتل الذاكرة. بشكل افتراضي، جميع الـ BLOBs
            يتم تحميلها إلى الذاكرة؛ وعند بلوغ هذا الحد تُستَخدم آليات بديلة (مثل الملفات المؤقتة)
            يزيد الحفاظ على الـ BLOBs في الذاكرة من الأداء لكنه قد يؤدي إلى استهلاك عالي للذاكرة. استخدم
            هذه الخاصية لتكييف السلوك مع بيئتك أو متطلباتك.


### ملاحظات

يتم تجاهل هذه الخاصية إذا تم تعيين [`BlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/ar/aspose.slides/blobmanagementoptions/is_temporary_files_allowed) إلى false، لأن الذاكرة تصبح حينئذٍ
            الموقع الوحيد المتاح للتخزين ولا يؤثر تقييد استعمال الـ BLOBs في الذاكرة.


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
* فئة [`BlobManagementOptions`](/slides/python-net/ar/aspose.slides/blobmanagementoptions)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)