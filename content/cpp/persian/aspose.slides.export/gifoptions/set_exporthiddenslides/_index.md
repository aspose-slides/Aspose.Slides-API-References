---
title: set_ExportHiddenSlides()
second_title: مرجع API Aspose.Slides برای C++
description: مشخص می‌کند که آیا اسلایدهای مخفی صادر شوند یا نه. مقدار پیش‌فرض false است.
type: docs
weight: 40
url: /fa/aspose.slides.export/gifoptions/set_exporthiddenslides/
---
## GifOptions::set_ExportHiddenSlides(bool) متد

مشخص می‌کند که آیا اسلایدهای مخفی صادر شوند یا نه. مقدار پیش‌فرض false است.

```cpp
void Aspose::Slides::Export::GifOptions::set_ExportHiddenSlides(bool value) override
```

## توضیحات



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## مراجع

* کلاس [GifOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)