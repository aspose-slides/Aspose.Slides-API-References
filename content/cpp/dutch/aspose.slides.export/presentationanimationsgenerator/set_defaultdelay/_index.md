---
title: set_DefaultDelay()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de standaard vertragingstijd in [ms].
type: docs
weight: 14
url: /nl/aspose.slides.export/presentationanimationsgenerator/set_defaultdelay/
---
## PresentationAnimationsGenerator::set_DefaultDelay(int32_t) methode

Stelt de standaard vertragingstijd in [ms].

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_DefaultDelay(int32_t value)
```

## Opmerkingen



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_DefaultDelay(1000); // 1s
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## Zie ook

* Klasse [PresentationAnimationsGenerator](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)