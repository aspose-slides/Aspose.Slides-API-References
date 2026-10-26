---
title: set_IncludeHiddenSlides()
second_title: Aspose.Slides لمرجع API للغة C++
description: احصل أو عيّن ما إذا كان يجب تضمين الشرائح المخفية.
type: docs
weight: 40
url: /ar/aspose.slides.export/presentationanimationsgenerator/set_includehiddenslides/
---
## PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool) طريقة

احصل أو عيّن ما إذا كان يجب تضمين الشرائح المخفية.

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool value)
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

* الفئة [PresentationAnimationsGenerator](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)