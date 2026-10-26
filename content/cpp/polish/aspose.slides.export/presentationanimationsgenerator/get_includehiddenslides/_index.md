---
title: get_IncludeHiddenSlides()
second_title: Aspose.Slides dla C++ – odwołanie API
description: Pobiera lub ustawia, czy ukryte slajdy mają być uwzględnione.
type: docs
weight: 27
url: /pl/aspose.slides.export/presentationanimationsgenerator/get_includehiddenslides/
---
## PresentationAnimationsGenerator::get_IncludeHiddenSlides() const metoda


Pobiera lub ustawia, czy ukryte slajdy powinny być uwzględnione.

```cpp
bool Aspose::Slides::Export::PresentationAnimationsGenerator::get_IncludeHiddenSlides() const
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