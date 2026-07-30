---
title: set_IncludeHiddenSlides()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Získá nebo nastaví, zda mají být zahrnuty skryté snímky.
type: docs
weight: 40
url: /cs/aspose.slides.export/presentationanimationsgenerator/set_includehiddenslides/
---
## PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool) metoda


Získá nebo nastaví, zda mají být zahrnuty skryté snímky.

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool value)
```

## Poznámky



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_IncludeHiddenSlides(false);
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## Viz také

* Třída [PresentationAnimationsGenerator](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)