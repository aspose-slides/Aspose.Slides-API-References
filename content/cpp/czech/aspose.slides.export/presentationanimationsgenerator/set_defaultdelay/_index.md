---
title: set_DefaultDelay()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Nastaví výchozí dobu zpoždění [ms].
type: docs
weight: 14
url: /cs/aspose.slides.export/presentationanimationsgenerator/set_defaultdelay/
---
## PresentationAnimationsGenerator::set_DefaultDelay(int32_t) metoda


Nastaví výchozí dobu zpoždění [ms].

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_DefaultDelay(int32_t value)
```

## Poznámky



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_DefaultDelay(1000); // 1 s
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## Viz také

* Třída [PresentationAnimationsGenerator](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)