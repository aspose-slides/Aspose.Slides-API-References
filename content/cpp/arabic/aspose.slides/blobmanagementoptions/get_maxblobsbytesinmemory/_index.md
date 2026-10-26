---
title: get_MaxBlobsBytesInMemory()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحدد الحد الأقصى للحجم الإجمالي (بالبايت) الذي قد تشغله جميع الـBLOBs في الذاكرة. بشكل افتراضي، يتم تحميل جميع الـBLOBs إلى الذاكرة؛ فقط عندما يتم الوصول إلى هذا الحد تُستخدم آليات بديلة (مثل الملفات المؤقتة). الحفاظ على الـBLOBs في الذاكرة يزيد من الأداء لكنه قد يؤدي إلى استهلاك عالي للذاكرة. استخدم هذه الخاصية لتكييف السلوك مع بيئتك أو متطلباتك.
type: docs
weight: 79
url: /ar/aspose.slides/blobmanagementoptions/get_maxblobsbytesinmemory/
---
## BlobManagementOptions::get_MaxBlobsBytesInMemory() طريقة

يحدد الحد الأقصى للحجم الإجمالي (بالبايت) الذي قد تشغله جميع الـBLOBs في الذاكرة. بشكل افتراضي، يتم تحميل جميع الـBLOBs إلى الذاكرة؛ فقط عندما يتم الوصول إلى هذا الحد تُستخدم آليات بديلة (مثل الملفات المؤقتة). الحفاظ على الـBLOBs في الذاكرة يزيد من الأداء لكنه قد يؤدي إلى استهلاك عالي للذاكرة. استخدم هذه الخاصية لتكييف السلوك مع بيئتك أو متطلباتك.

```cpp
uint64_t Aspose::Slides::BlobManagementOptions::get_MaxBlobsBytesInMemory() override
```

## ملاحظات

يتم تجاهل هذه القيمة إذا تم تعيين [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) إلى false، لأن الذاكرة تكون حينها الموقع الوحيد للتخزين المتاح وتحديد استخدام الـBLOB في الذاكرة لا يؤثر.

القيمة الافتراضية هي 629,145,600 بايت (600 ميغابايت).

يمكنك تعيين هذه الخاصية إلى الصفر، ولكن سيظل يتم حجز كمية صغيرة قليلة من الذاكرة.

## انظر أيضًا

* فئة [BlobManagementOptions](../)
* نطاق الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)