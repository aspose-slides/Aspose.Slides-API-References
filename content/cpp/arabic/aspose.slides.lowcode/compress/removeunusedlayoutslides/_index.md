---
title: RemoveUnusedLayoutSlides()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بضغط العرض التقديمي عن طريق إزالة شرائح التخطيط غير المستخدمة.
type: docs
weight: 14
url: /ar/aspose.slides.lowcode/compress/removeunusedlayoutslides/
---
## Compress::RemoveUnusedLayoutSlides(System::SharedPtr\<Presentation\>) طريقة


يقوم بضغط الـ [Presentation](../../../aspose.slides/presentation/) عن طريق إزالة شرائح التخطيط غير المستخدمة.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedLayoutSlides(System::SharedPtr<Presentation> pres)
```


### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | مثيل العرض التقديمي |
## ملاحظات




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedLayoutSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## انظر أيضا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [Presentation](../../../aspose.slides/presentation/)
* فئة [Compress](../)
* نطاق [Aspose::Slides::LowCode](../../)
* مكتبة [Aspose.Slides](../../../)