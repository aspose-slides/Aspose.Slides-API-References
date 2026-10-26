---
title: get_DefaultDelay()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: डिफ़ॉल्ट विलंब समय [ms] प्राप्त करता है।
type: docs
weight: 1
url: /hi/aspose.slides.export/presentationanimationsgenerator/get_defaultdelay/
---
## PresentationAnimationsGenerator::get_DefaultDelay() const विधि

डिफ़ॉल्ट विलंब समय [ms] प्राप्त करता है।

```cpp
int32_t Aspose::Slides::Export::PresentationAnimationsGenerator::get_DefaultDelay() const
```

## टिप्पणियाँ



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_DefaultDelay(1000); // 1s
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## संबंधित देखें

* क्लास [PresentationAnimationsGenerator](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)