---
title: RemoveUnusedLayoutSlides()
second_title: مرجع API Aspose.Slides برای C++
description: فشرده‌سازی ارائه را با حذف اسلایدهای طرح‌بندی استفاده نشده انجام می‌دهد.
type: docs
weight: 14
url: /fa/aspose.slides.lowcode/compress/removeunusedlayoutslides/
---
## Compress::RemoveUnusedLayoutSlides(System::SharedPtr\<Presentation\>) متد


فشرده‌سازی [Presentation](../../../aspose.slides/presentation/) را با حذف اسلایدهای طرح‌بندی استفاده نشده انجام می‌دهد.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedLayoutSlides(System::SharedPtr<Presentation> pres)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | نمونه ارائه |
## توضیحات




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedLayoutSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Presentation](../../../aspose.slides/presentation/)
* کلاس [Compress](../)
* فضای‌نام [Aspose::Slides::LowCode](../../)
* کتابخانه [Aspose.Slides](../../../)