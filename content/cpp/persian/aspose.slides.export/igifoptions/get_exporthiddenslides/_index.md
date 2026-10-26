---
title: get_ExportHiddenSlides()
second_title: مرجع API Aspose.Slides برای C++
description: مشخص می‌کند آیا اسلایدهای پنهان صادر می‌شوند یا خیر. مقدار پیش‌فرض false است.
type: docs
weight: 27
url: /fa/aspose.slides.export/igifoptions/get_exporthiddenslides/
---
## IGifOptions::get_ExportHiddenSlides() متد


مشخص می‌کند آیا اسلایدهای پنهان صادر می‌شوند یا خیر. مقدار پیش‌فرض false است.

```cpp
virtual bool Aspose::Slides::Export::IGifOptions::get_ExportHiddenSlides()=0
```

## توضیحات



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## همچنین ببینید

* Class [IGifOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)