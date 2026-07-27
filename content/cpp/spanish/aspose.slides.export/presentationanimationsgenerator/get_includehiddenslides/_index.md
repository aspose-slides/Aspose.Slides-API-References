---
title: get_IncludeHiddenSlides()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene o establece si las diapositivas ocultas deben incluirse.
type: docs
weight: 27
url: /es/aspose.slides.export/presentationanimationsgenerator/get_includehiddenslides/
---
## PresentationAnimationsGenerator::get_IncludeHiddenSlides() const método


Obtiene o establece si las diapositivas ocultas deben incluirse.

```cpp
bool Aspose::Slides::Export::PresentationAnimationsGenerator::get_IncludeHiddenSlides() const
```

## Observaciones



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_IncludeHiddenSlides(false);
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## Ver también

* Clase [PresentationAnimationsGenerator](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)