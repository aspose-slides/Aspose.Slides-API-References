---
title: set_DefaultDelay()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in standardfördröjningstid [ms].
type: docs
weight: 14
url: /sv/aspose.slides.export/presentationanimationsgenerator/set_defaultdelay/
---
## PresentationAnimationsGenerator::set_DefaultDelay(int32_t) metod


Ställer in standardfördröjningstid [ms].

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_DefaultDelay(int32_t value)
```

## Anmärkningar



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_DefaultDelay(1000); // 1s
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## Se även

* Klass [PresentationAnimationsGenerator](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)