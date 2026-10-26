---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides برای C++ مرجع API
description: تعیین می‌کند که آیا اسلایدهای مخفی صادر شوند یا نه. مقدار پیش‌فرض false است.
type: docs
weight: 40
url: /fa/aspose.slides.export/igifoptions/set_exporthiddenslides/
---
## IGifOptions::set_ExportHiddenSlides(bool) متد

تعیین می‌کند که آیا اسلایدهای مخفی صادر شوند یا نه. مقدار پیش‌فرض false است.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_ExportHiddenSlides(bool value)=0
```

## توضیحات



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## موارد مرتبط

* کلاس [IGifOptions](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)