---
title: CompressEmbeddedFonts()
second_title: Aspose.Slides برای C++ مرجع API
description: فشرده‌سازی ارائه را با حذف کاراکترهای استفاده‌نشده از فونت‌های تعبیه‌شده انجام می‌دهد.
type: docs
weight: 27
url: /fa/aspose.slides.lowcode/compress/compressembeddedfonts/
---
## Compress::CompressEmbeddedFonts(System::SharedPtr\<Presentation\>) متد

فشرده‌سازی [Presentation](../../../aspose.slides/presentation/) را با حذف کاراکترهای استفاده نشده از فونت‌های تعبیه‌شده انجام می‌دهد.

```cpp
static void Aspose::Slides::LowCode::Compress::CompressEmbeddedFonts(System::SharedPtr<Presentation> pres)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | نمونه ارائه |
## نکات

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::CompressEmbeddedFonts(pres);

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Presentation](../../../aspose.slides/presentation/)
* کلاس [Compress](../)
* فضای نام [Aspose::Slides::LowCode](../../)
* کتابخانه [Aspose.Slides](../../../)