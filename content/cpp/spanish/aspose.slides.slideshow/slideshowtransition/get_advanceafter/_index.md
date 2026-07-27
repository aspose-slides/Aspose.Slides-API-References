---
title: get_AdvanceAfter()
second_title: Referencia de API de Aspose.Slides para C++
description: Este atributo especifica si la presentación se moverá a la diapositiva siguiente después de un cierto tiempo. Leer bool.
type: docs
weight: 105
url: /es/aspose.slides.slideshow/slideshowtransition/get_advanceafter/
---
## SlideShowTransition::get_AdvanceAfter() método


Este atributo especifica si la presentación se moverá a la diapositiva siguiente después de un cierto tiempo. Leer **bool**.

```cpp
bool Aspose::Slides::SlideShow::SlideShowTransition::get_AdvanceAfter() override
```

## Observaciones



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Obtener la primera transición de diapositiva
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Comprobar si la bandera Advance Slide After está marcada
if (slideTransition->get_AdvanceAfter())
{
    // Obtener el valor del tiempo Advance Slide After
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Ver también

* Clase [SlideShowTransition](../)
* Espacio de nombres [Aspose::Slides::SlideShow](../../)
* Biblioteca [Aspose.Slides](../../../)