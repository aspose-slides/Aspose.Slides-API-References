---
title: get_IncludeHiddenSlides()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: छुपी हुई स्लाइड्स को शामिल किया जाना चाहिए या नहीं, इसे प्राप्त या निर्धारित करता है।
type: docs
weight: 27
url: /hi/aspose.slides.export/presentationanimationsgenerator/get_includehiddenslides/
---
## PresentationAnimationsGenerator::get_IncludeHiddenSlides() const विधि

छुपी हुई स्लाइड्स को शामिल किया जाना चाहिए या नहीं, इसे प्राप्त या निर्धारित करता है।

```cpp
bool Aspose::Slides::Export::PresentationAnimationsGenerator::get_IncludeHiddenSlides() const
```

## टिप्पणी

```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_IncludeHiddenSlides(false);
// ...
animationsGenerator->Run(presentation->get_Slides());
```

## देखें भी

* क्लास [PresentationAnimationsGenerator](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)