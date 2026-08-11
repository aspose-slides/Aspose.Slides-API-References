---
title: get_IncludeHiddenSlides()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: احصل أو اضبط ما إذا كان يجب تضمين الشرائح المخفية.
type: docs
weight: 27
url: /ar/aspose.slides.export/presentationanimationsgenerator/get_includehiddenslides/
---
## PresentationAnimationsGenerator::get_IncludeHiddenSlides() const طريقة


احصل أو اضبط ما إذا كان يجب تضمين الشرائح المخفية.

```cpp
bool Aspose::Slides::Export::PresentationAnimationsGenerator::get_IncludeHiddenSlides() const
```

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_IncludeHiddenSlides(false);
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## انظر أيضًا

* فئة [PresentationAnimationsGenerator](../)
* نطاق [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)