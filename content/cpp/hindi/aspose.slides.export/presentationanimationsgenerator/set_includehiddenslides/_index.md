---
title: set_IncludeHiddenSlides()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: छिपी स्लाइड्स को शामिल किया जाना चाहिए या नहीं, इसे प्राप्त या सेट करता है।
type: docs
weight: 40
url: /hi/aspose.slides.export/presentationanimationsgenerator/set_includehiddenslides/
---
## PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool) मेथड


छिपी स्लाइड्स को शामिल किया जाना चाहिए या नहीं, इसे प्राप्त या सेट करता है।

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool value)
```

## टिप्पणी



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_IncludeHiddenSlides(false);
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## देखें

* क्लास [PresentationAnimationsGenerator](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)