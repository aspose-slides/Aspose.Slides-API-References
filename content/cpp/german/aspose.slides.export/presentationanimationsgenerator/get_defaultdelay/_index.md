---
title: get_DefaultDelay()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Standardverzögerungszeit [ms] zurück.
type: docs
weight: 1
url: /de/aspose.slides.export/presentationanimationsgenerator/get_defaultdelay/
---
## PresentationAnimationsGenerator::get_DefaultDelay() const Methode


Gibt die Standardverzögerungszeit [ms] zurück.

```cpp
int32_t Aspose::Slides::Export::PresentationAnimationsGenerator::get_DefaultDelay() const
```

## Anmerkungen



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
* Bibliothek [Aspose.Slides](../../../)