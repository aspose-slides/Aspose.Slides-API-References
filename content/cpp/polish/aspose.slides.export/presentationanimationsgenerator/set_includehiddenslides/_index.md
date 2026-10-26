---
title: set_IncludeHiddenSlides()
second_title: Aspose.Slides dla C++ – Odwołanie API
description: Pobiera lub ustawia, czy ukryte slajdy powinny być uwzględniane.
type: docs
weight: 40
url: /pl/aspose.slides.export/presentationanimationsgenerator/set_includehiddenslides/
---
## PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool) metoda


Pobiera lub ustawia, czy ukryte slajdy powinny być uwzględniane.

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool value)
```

## Uwagi


```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_IncludeHiddenSlides(false);
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## Zobacz także

* Klasa [PresentationAnimationsGenerator](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)