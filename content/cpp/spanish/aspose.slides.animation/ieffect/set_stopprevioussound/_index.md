---
title: set_StopPreviousSound()
second_title: Referencia de API de Aspose.Slides para C++
description: Este atributo especifica si el efecto de animación detiene el sonido anterior. Escriba bool.
type: docs
weight: 209
url: /es/aspose.slides.animation/ieffect/set_stopprevioussound/
---
## IEffect::set_StopPreviousSound(bool) método

Este atributo especifica si el efecto de animación detiene el sonido anterior. Escriba **bool**.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_StopPreviousSound(bool value)=0
```
## Observaciones

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Get the first effect of the second slide.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // Cambiar el segundo efecto Enhancements/Sound a "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Ver también

* Clase [IEffect](../)
* Espacio de nombres [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)