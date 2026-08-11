---
title: get_IncludeHiddenSlides()
second_title: Aspose.Slides برای مرجع API C++
description: دریافت یا تنظیم می‌کند که آیا اسلایدهای مخفی باید گنجانده شوند.
type: docs
weight: 27
url: /fa/aspose.slides.export/presentationanimationsgenerator/get_includehiddenslides/
---
## PresentationAnimationsGenerator::get_IncludeHiddenSlides() const متد

دریافت یا تنظیم می‌کند که آیا اسلایدهای مخفی باید گنجانده شوند.

```cpp
bool Aspose::Slides::Export::PresentationAnimationsGenerator::get_IncludeHiddenSlides() const
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