---
title: get_IncludeHiddenSlides()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt op of stelt in of verborgen dia's moeten worden opgenomen.
type: docs
weight: 27
url: /nl/aspose.slides.export/presentationanimationsgenerator/get_includehiddenslides/
---
## PresentationAnimationsGenerator::get_IncludeHiddenSlides() const methode


Haalt op of stelt in of verborgen dia's moeten worden opgenomen.

```cpp
bool Aspose::Slides::Export::PresentationAnimationsGenerator::get_IncludeHiddenSlides() const
```

## Opmerkingen


```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_IncludeHiddenSlides(false);
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## Zie ook

* Klasse [PresentationAnimationsGenerator](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)