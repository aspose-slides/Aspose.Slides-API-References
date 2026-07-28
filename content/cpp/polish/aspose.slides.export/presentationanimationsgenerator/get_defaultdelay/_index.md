---
title: get_DefaultDelay()
second_title: Aspose.Slides for C++ – referencja API
description: Pobiera domyślny czas opóźnienia [ms].
type: docs
weight: 1
url: /pl/aspose.slides.export/presentationanimationsgenerator/get_defaultdelay/
---
## PresentationAnimationsGenerator::get_DefaultDelay() const metoda


Pobiera domyślny czas opóźnienia [ms].

```cpp
int32_t Aspose::Slides::Export::PresentationAnimationsGenerator::get_DefaultDelay() const
```

## Uwagi




```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_DefaultDelay(1000); // 1s
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## Zobacz także

* Klasa [PresentationAnimationsGenerator](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)