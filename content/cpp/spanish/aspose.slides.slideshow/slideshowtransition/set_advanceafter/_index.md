---
title: set_AdvanceAfter()
second_title: Referencia de API de Aspose.Slides para C++
description: Este atributo especifica si la presentación se moverá a la diapositiva siguiente después de un tiempo determinado. Escriba bool.
type: docs
weight: 118
url: /es/aspose.slides.slideshow/slideshowtransition/set_advanceafter/
---
## SlideShowTransition::set_AdvanceAfter(bool) método

Este atributo especifica si la presentación se moverá a la diapositiva siguiente después de un tiempo determinado. Escriba **bool**.

```cpp
void Aspose::Slides::SlideShow::SlideShowTransition::set_AdvanceAfter(bool value) override
```

## Comentarios

```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Obtenga la primera transición de diapositiva
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Verifique si el indicador Advance Slide After está activado
if (slideTransition->get_AdvanceAfter())
{
    // Obtenga el valor del tiempo de Advance Slide After
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Ver también

* Clase [SlideShowTransition](../)
* Espacio de nombres [Aspose::Slides::SlideShow](../../)
* Biblioteca [Aspose.Slides](../../../)