---
title: RemoveUnusedMasterSlides()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بضغط العرض التقديمي عن طريق إزالة الشرائح الرئيسة غير المستخدمة.
type: docs
weight: 1
url: /ar/aspose.slides.lowcode/compress/removeunusedmasterslides/
---
## طريقة Compress::RemoveUnusedMasterSlides(System::SharedPtr\<Presentation\>) 

يقوم بضغط [Presentation](../../../aspose.slides/presentation/) عن طريق إزالة الشرائح الرئيسة غير المستخدمة.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedMasterSlides(System::SharedPtr<Presentation> pres)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | مثيل العرض التقديمي |
## ملاحظات




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## انظر أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Presentation](../../../aspose.slides/presentation/)
* فئة [Compress](../)
* نطاق أسماء [Aspose::Slides::LowCode](../../)
* مكتبة [Aspose.Slides](../../../)