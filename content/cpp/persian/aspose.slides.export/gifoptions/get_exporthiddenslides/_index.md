---
title: get_ExportHiddenSlides()
second_title: مرجع API Aspose.Slides برای C++
description: تشخیص می‌دهد که آیا اسلایدهای مخفی صادر می‌شوند یا خیر. مقدار پیش‌فرض false است.
type: docs
weight: 27
url: /fa/aspose.slides.export/gifoptions/get_exporthiddenslides/
---
## GifOptions::get_ExportHiddenSlides() متد


تشخیص می‌دهد که آیا اسلایدهای مخفی صادر می‌شوند یا خیر. مقدار پیش‌فرض false است.

```cpp
bool Aspose::Slides::Export::GifOptions::get_ExportHiddenSlides() override
```

## توضیحات



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## موارد مرتبط

* کلاس [GifOptions](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)