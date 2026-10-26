---
title: set_IncludeHiddenSlides()
second_title: مرجع API Aspose.Slides برای C++
description: دریافت یا تنظیم می‌کند که آیا اسلایدهای مخفی باید گنجانده شوند.
type: docs
weight: 40
url: /fa/aspose.slides.export/presentationanimationsgenerator/set_includehiddenslides/
---
## PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool) متد


دریافت یا تنظیم می‌کند که آیا اسلایدهای مخفی باید گنجانده شوند.

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool value)
```

## توضیحات



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_IncludeHiddenSlides(false);
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## موارد مرتبط

* کلاس [PresentationAnimationsGenerator](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)