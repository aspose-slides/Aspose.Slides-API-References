---
title: get_IncludeHiddenSlides()
second_title: Aspose.Slides for C++ API referencia
description: Megadja vagy beállítja, hogy a rejtett diák legyenek-e beleértve.
type: docs
weight: 27
url: /hu/aspose.slides.export/presentationanimationsgenerator/get_includehiddenslides/
---
## PresentationAnimationsGenerator::get_IncludeHiddenSlides() const metódus

Get or sets if hidden slides should be included.

```cpp
bool Aspose::Slides::Export::PresentationAnimationsGenerator::get_IncludeHiddenSlides() const
```

## Megjegyzések



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_IncludeHiddenSlides(false);
// ...
animationsGenerator->Run(presentation->get_Slides());
```


## Lásd még
* Osztály [PresentationAnimationsGenerator](../)
* Névterület [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)