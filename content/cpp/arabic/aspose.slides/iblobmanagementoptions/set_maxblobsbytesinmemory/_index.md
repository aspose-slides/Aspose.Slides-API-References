---
title: set_MaxBlobsBytesInMemory()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحدد الحد الأقصى للحجم الإجمالي (بالبايت) الذي قد تشغله جميع الـ BLOBs في الذاكرة. بشكل افتراضي، يتم تحميل جميع الـ BLOBs في الذاكرة؛ فقط عندما يتم الوصول إلى هذا الحد تُستخدم آليات بديلة (مثل الملفات المؤقتة). إبقاء الـ BLOBs في الذاكرة يزيد الأداء لكنه قد يؤدي إلى استهلاك عالي للذاكرة. استخدم هذه الخاصية لتكييف السلوك مع بيئتك أو متطلباتك.
type: docs
weight: 92
url: /ar/aspose.slides/iblobmanagementoptions/set_maxblobsbytesinmemory/
---
## IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) طريقة

يحدد الحد الأقصى لحجم الذاكرة الإجمالي (بالبايت) الذي قد تشغله جميع الـ BLOBs في الذاكرة. بشكل افتراضي، يتم تحميل جميع الـ BLOBs في الذاكرة؛ فقط عندما يتم الوصول إلى هذا الحد يتم استخدام آليات بديلة (مثل الملفات المؤقتة). إبقاء الـ BLOBs في الذاكرة يزيد الأداء ولكن قد يؤدي إلى استهلاك عالي للذاكرة. استخدم هذه الخاصية لتكييف السلوك مع بيئتك أو متطلباتك.

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value)=0
```

## ملاحظات

يتم تجاهل هذه القيمة إذا تم تعيين [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) إلى false، حيث تكون الذاكرة في ذلك الوقت هي موقع التخزين الوحيد المتاح ولا يؤثر تقليل استخدام BLOB في الذاكرة.

القيمة الافتراضية هي 629,145,600 بايت (600 ميغابايت).

يمكنك تعيين هذه الخاصية إلى صفر، ولكن سيتم حجز كمية صغيرة من الذاكرة على الأقل.

## انظر أيضًا

* الفئة [IBlobManagementOptions](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)