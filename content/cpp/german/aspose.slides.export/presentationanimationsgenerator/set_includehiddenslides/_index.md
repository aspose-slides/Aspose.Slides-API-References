---
title: set_IncludeHiddenSlides()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest oder setzt, ob versteckte Folien einbezogen werden sollen.
type: docs
weight: 40
url: /de/aspose.slides.export/presentationanimationsgenerator/set_includehiddenslides/
---
## PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool) Methode


Liest oder setzt, ob versteckte Folien einbezogen werden sollen.

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool value)
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