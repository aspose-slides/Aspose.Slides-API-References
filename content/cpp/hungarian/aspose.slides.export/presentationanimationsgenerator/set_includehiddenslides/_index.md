---
title: set_IncludeHiddenSlides()
second_title: Aspose.Slides C++ API hivatkozás
description: Lekéri vagy beállítja, hogy a rejtett diákat bele kell-e foglalni.
type: docs
weight: 40
url: /hu/aspose.slides.export/presentationanimationsgenerator/set_includehiddenslides/
---
## PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool) metódus


Lekéri vagy beállítja, hogy a rejtett diákat bele kell-e foglalni.

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool value)
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
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)