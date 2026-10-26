---
title: set_DefaultDelay()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: डिफ़ॉल्ट देरी समय सेट करता है [ms].
type: docs
weight: 14
url: /hi/aspose.slides.export/presentationanimationsgenerator/set_defaultdelay/
---
## PresentationAnimationsGenerator::set_DefaultDelay(int32_t) विधि


डिफ़ॉल्ट देरी समय को सेट करता है [ms].

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_DefaultDelay(int32_t value)
```

## टिप्पणियाँ



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_DefaultDelay(1000); // 1 सेकंड
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## और देखें

* क्लास [PresentationAnimationsGenerator](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)