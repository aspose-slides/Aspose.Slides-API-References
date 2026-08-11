---
title: set_MaxBlobsBytesInMemory()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد الحد الأقصى للحجم الإجمالي (بالبايت) الذي قد تشغله جميع الـ BLOBs في الذاكرة. بشكل افتراضي، يتم تحميل جميع الـ BLOBs إلى الذاكرة؛ ولا يتم اللجوء إلى آليات بديلة (مثل الملفات المؤقتة) إلا عندما يُصلَ إلى هذا الحد. الحفاظ على الـ BLOBs في الذاكرة يعزز الأداء لكنه قد يسبب استخدامًا عاليًا للذاكرة. استخدم هذه الخاصية لتخصيص السلوك وفقًا لبيئتك أو متطلباتك.
type: docs
weight: 92
url: /ar/aspose.slides/blobmanagementoptions/set_maxblobsbytesinmemory/
---
## BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) طريقة

يحدد الحد الأقصى للحجم الإجمالي (بالبايت) الذي قد تشغله جميع الـ BLOBs في الذاكرة. بشكل افتراضي، يتم تحميل جميع الـ BLOBs إلى الذاكرة؛ ولا يتم اللجوء إلى آليات بديلة (مثل الملفات المؤقتة) إلا عندما يُصلَ إلى هذا الحد. الحفاظ على الـ BLOBs في الذاكرة يعزز الأداء لكن قد يؤدي إلى استهلاك عالي للذاكرة. استخدم هذه الخاصية لتخصيص السلوك وفقًا لبيئتك أو متطلباتك.

```cpp
void Aspose::Slides::BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value) override
```

## ملاحظات

يُتجاهل هذا القيمة إذا كان [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) مضبوطًا على false، لأن الذاكرة تكون حينها الموقع الوحيد المتاح للتخزين ولا يؤثر تحديد استخدام الـ BLOB في الذاكرة. 

القيمة الافتراضية هي 629,145,600 بايت (600 ميغابايت). 

يمكنك ضبط هذه الخاصية على الصفر، لكن سيظل يتم حجز كمية صغيرة دنيا من الذاكرة. 
## انظر أيضًا

* الفئة [BlobManagementOptions](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)