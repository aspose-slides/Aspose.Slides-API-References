---
title: get_IncludeHiddenSlides()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Získá nebo nastaví, zda mají být zahrnuty skryté snímky.
type: docs
weight: 27
url: /cs/aspose.slides.export/presentationanimationsgenerator/get_includehiddenslides/
---
## PresentationAnimationsGenerator::get_IncludeHiddenSlides() const metoda


Získá nebo nastaví, zda mají být zahrnuty skryté snímky.

```cpp
bool Aspose::Slides::Export::PresentationAnimationsGenerator::get_IncludeHiddenSlides() const
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