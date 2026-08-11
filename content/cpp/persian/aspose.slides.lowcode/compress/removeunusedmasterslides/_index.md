---
title: RemoveUnusedMasterSlides()
second_title: مرجع API Aspose.Slides برای C++
description: فشرده‌سازی ارائه را با حذف اسلایدهای مستر استفاده نشده انجام می‌دهد.
type: docs
weight: 1
url: /fa/aspose.slides.lowcode/compress/removeunusedmasterslides/
---
## Compress::RemoveUnusedMasterSlides(System::SharedPtr\<Presentation\>) متد


فشرده‌سازی [Presentation](../../../aspose.slides/presentation/) را با حذف اسلایدهای مستر استفاده نشده انجام می‌دهد.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedMasterSlides(System::SharedPtr<Presentation> pres)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | نمونهٔ ارائه |
## توضیحات




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [Compress](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)