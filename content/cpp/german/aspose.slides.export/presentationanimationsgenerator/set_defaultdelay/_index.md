---
title: set_DefaultDelay()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt die Standardverzögerungszeit [ms].
type: docs
weight: 14
url: /de/aspose.slides.export/presentationanimationsgenerator/set_defaultdelay/
---
## PresentationAnimationsGenerator::set_DefaultDelay(int32_t) Methode

Setzt die Standardverzögerungszeit [ms].

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_DefaultDelay(int32_t value)
```

## Hinweise



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_DefaultDelay(1000); // 1s
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## Siehe auch

* Klasse [PresentationAnimationsGenerator](../)
* Namensraum [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)