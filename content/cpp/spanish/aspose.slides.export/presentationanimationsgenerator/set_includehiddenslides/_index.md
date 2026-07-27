---
title: set_IncludeHiddenSlides()
second_title: Aspose.Slides para la referencia de API de C++
description: Obtiene o establece si las diapositivas ocultas deben incluirse.
type: docs
weight: 40
url: /es/aspose.slides.export/presentationanimationsgenerator/set_includehiddenslides/
---
## PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool) método

Obtiene o establece si las diapositivas ocultas deben incluirse.

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool value)
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