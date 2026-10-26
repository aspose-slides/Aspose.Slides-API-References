---
title: set_AdvanceAfter()
second_title: Referencia de API de Aspose.Slides para C++
description: Este atributo especifica si la presentación se moverá a la diapositiva siguiente después de un tiempo determinado. Escriba bool.
type: docs
weight: 118
url: /es/aspose.slides/islideshowtransition/set_advanceafter/
---
## ISlideShowTransition::set_AdvanceAfter(bool) método


Este atributo especifica si la presentación se moverá a la diapositiva siguiente después de un tiempo determinado. Escriba **bool**.

```cpp
virtual void Aspose::Slides::ISlideShowTransition::set_AdvanceAfter(bool value)=0
```

## Observaciones



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Obtener la primera transición de diapositiva
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Verifique si la bandera Advance Slide After está activada
if (slideTransition->get_AdvanceAfter())
{
    // Obtener el valor del tiempo Advance Slide After
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Ver también

* Clase [ISlideShowTransition](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)