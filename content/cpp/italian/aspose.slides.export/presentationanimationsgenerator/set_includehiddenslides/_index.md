---
title: set_IncludeHiddenSlides()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene o imposta se le diapositive nascoste devono essere incluse.
type: docs
weight: 40
url: /it/aspose.slides.export/presentationanimationsgenerator/set_includehiddenslides/
---
## PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool) metodo

Ottiene o imposta se le diapositive nascoste devono essere incluse.

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool value)
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