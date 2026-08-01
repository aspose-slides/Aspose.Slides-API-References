---
title: get_DefaultDelay()
second_title: Aspose.Slides voor C++ API-referentie
description: Verkrijgt de standaardvertragingstijd [ms].
type: docs
weight: 1
url: /nl/aspose.slides.export/presentationanimationsgenerator/get_defaultdelay/
---
## PresentationAnimationsGenerator::get_DefaultDelay() const methode


Verkrijgt de standaardvertragingstijd [ms].

```cpp
int32_t Aspose::Slides::Export::PresentationAnimationsGenerator::get_DefaultDelay() const
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