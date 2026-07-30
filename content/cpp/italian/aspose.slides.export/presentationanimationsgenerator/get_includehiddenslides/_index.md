---
title: get_IncludeHiddenSlides()
second_title: Riferimento API Aspose.Slides per C++
description: Ottiene o imposta se le diapositive nascoste devono essere incluse.
type: docs
weight: 27
url: /it/aspose.slides.export/presentationanimationsgenerator/get_includehiddenslides/
---
## PresentationAnimationsGenerator::get_IncludeHiddenSlides() const metodo

Ottiene o imposta se le diapositive nascoste devono essere incluse.

```cpp
bool Aspose::Slides::Export::PresentationAnimationsGenerator::get_IncludeHiddenSlides() const
```

## Osservazioni



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_IncludeHiddenSlides(false);
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## Vedi anche

* Classe [PresentationAnimationsGenerator](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)