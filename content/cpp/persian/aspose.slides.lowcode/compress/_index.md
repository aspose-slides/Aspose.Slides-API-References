---
title: Compress
second_title: مرجع API Aspose.Slides برای C++
description: نمایانگر گروهی از متدها است که برای فشرده‌سازی Presentation منظور شده‌اند.
type: docs
weight: 14
url: /fa/aspose.slides.lowcode/compress/
---
## کلاس Compress

نمایانگر یک گروه از متدها است که برای فشرده‌سازی [Presentation](../../aspose.slides/presentation/) منظور شده‌اند.

```cpp
class Compress
```

## متدها

| متد | توضیح |
| --- | --- |
|  [Compress](./compress/)() |  |
| static void [CompressEmbeddedFonts](./compressembeddedfonts/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | با حذف کاراکترهای استفاده‌نشده از فونت‌های جاسازی‌شده، فشرده‌سازی [Presentation](../../aspose.slides/presentation/) را انجام می‌دهد. |
| static void [RemoveUnusedLayoutSlides](./removeunusedlayoutslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | با حذف اسلایدهای چیدمان استفاده‌نشده، فشرده‌سازی [Presentation](../../aspose.slides/presentation/) را انجام می‌دهد. |
| static void [RemoveUnusedMasterSlides](./removeunusedmasterslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | با حذف اسلایدهای مستر استفاده‌نشده، فشرده‌سازی [Presentation](../../aspose.slides/presentation/) را انجام می‌دهد. |
## توضیحات

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## مراجعه

* فضای نام [Aspose::Slides::LowCode](../)
* کتابخانه [Aspose.Slides](../../)