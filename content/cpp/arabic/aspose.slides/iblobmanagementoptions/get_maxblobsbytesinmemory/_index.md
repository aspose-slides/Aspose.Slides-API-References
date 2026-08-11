---
title: get_MaxBlobsBytesInMemory()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد الحد الأقصى للحجم الإجمالي (بالبايت) الذي قد تشغله جميع BLOBs في الذاكرة. بشكل افتراضي، يتم تحميل جميع BLOBs إلى الذاكرة؛ وفقط عند بلوغ هذا الحد تُستخدم آليات بديلة (مثل الملفات المؤقتة). إبقاء BLOBs في الذاكرة يعزز الأداء لكنه قد يؤدي إلى استهلاك عالي للذاكرة. استخدم هذه الخاصية لتكييف السلوك مع بيئتك أو متطلباتك.
type: docs
weight: 79
url: /ar/aspose.slides/iblobmanagementoptions/get_maxblobsbytesinmemory/
---
## IBlobManagementOptions::get_MaxBlobsBytesInMemory() طريقة

يعرّف الحد الأقصى للحجم الإجمالي (بالبايت) الذي قد تشغله جميع BLOBs في الذاكرة. بشكل افتراضي، يتم تحميل جميع BLOBs إلى الذاكرة؛ وعند الوصول إلى هذا الحد فقط تُستخدم آليات بديلة (مثل الملفات المؤقتة). الحفاظ على BLOBs في الذاكرة يعزز الأداء لكنه قد يؤدي إلى استهلاك عالي للذاكرة. استخدم هذه الخاصية لتكييف السلوك مع بيئتك أو متطلباتك.

```cpp
virtual uint64_t Aspose::Slides::IBlobManagementOptions::get_MaxBlobsBytesInMemory()=0
```

## ملاحظات

هذه القيمة يتم تجاهلها إذا تم تعيين [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) إلى false، لأن الذاكرة تصبح الموقع الوحيد للتخزين المتاح وتحديد استخدام BLOB في الذاكرة لا يؤثر. 

القيمة الافتراضية هي 629,145,600 بايت (600 ميغابايت). 

يمكنك تعيين هذه الخاصية إلى صفر، ولكن سيظل جزء صغير من الذاكرة محجوزًا. 
## انظر أيضًا

* فئة [IBlobManagementOptions](../)
* نطاق الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)