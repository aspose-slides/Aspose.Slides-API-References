---
title: get_IncludeHiddenSlides()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt an oder legt fest, ob versteckte Folien einbezogen werden sollen.
type: docs
weight: 27
url: /de/aspose.slides.export/presentationanimationsgenerator/get_includehiddenslides/
---
## PresentationAnimationsGenerator::get_IncludeHiddenSlides() const Methode

Gibt an oder legt fest, ob versteckte Folien einbezogen werden sollen.

```cpp
bool Aspose::Slides::Export::PresentationAnimationsGenerator::get_IncludeHiddenSlides() const
```

## Bemerkungen



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_IncludeHiddenSlides(false);
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## Siehe auch

* Klasse [PresentationAnimationsGenerator](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)