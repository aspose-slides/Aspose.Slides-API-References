---
title: get_AdvanceAfter()
second_title: Referencia de API de Aspose.Slides para C++
description: Este atributo especifica si la presentación avanzará a la siguiente diapositiva después de un tiempo determinado. Leer bool.
type: docs
weight: 105
url: /es/aspose.slides/islideshowtransition/get_advanceafter/
---
## ISlideShowTransition::get_AdvanceAfter() método


Este atributo especifica si la presentación avanzará a la siguiente diapositiva después de un tiempo determinado. Leer **bool**.

```cpp
virtual bool Aspose::Slides::ISlideShowTransition::get_AdvanceAfter()=0
```

## Observaciones



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Obtener la primera transición de diapositiva
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Verificar si la bandera Advance Slide After está marcada
if (slideTransition->get_AdvanceAfter())
{
    // Obtener el valor del tiempo de avance después de la diapositiva
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Ver también

* Clase [ISlideShowTransition](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)