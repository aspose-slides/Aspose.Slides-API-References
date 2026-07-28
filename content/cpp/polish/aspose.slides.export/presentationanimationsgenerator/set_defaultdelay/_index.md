---
title: set_DefaultDelay()
second_title: Aspose.Slides dla C++ – odwołanie API
description: Ustawia domyślny czas opóźnienia [ms].
type: docs
weight: 14
url: /pl/aspose.slides.export/presentationanimationsgenerator/set_defaultdelay/
---
## PresentationAnimationsGenerator::set_DefaultDelay(int32_t) metoda


Ustawia domyślny czas opóźnienia [ms].

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_DefaultDelay(int32_t value)
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