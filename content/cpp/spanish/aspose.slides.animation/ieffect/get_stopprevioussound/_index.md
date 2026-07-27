---
title: get_StopPreviousSound()
second_title: Referencia de API de Aspose.Slides para C++
description: Este atributo especifica si el efecto de animación detiene el sonido anterior. Lee bool.
type: docs
weight: 196
url: /es/aspose.slides.animation/ieffect/get_stopprevioussound/
---
## IEffect::get_StopPreviousSound() método


Este atributo especifica si el efecto de animación detiene el sonido anterior. Lee **bool**.

```cpp
virtual bool Aspose::Slides::Animation::IEffect::get_StopPreviousSound()=0
```

## Observaciones



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Obtenga el primer efecto de la primera diapositiva.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Obtenga el primer efecto de la segunda diapositiva.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // Cambie el segundo efecto Enhancements/Sound a "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Ver también

* Clase [IEffect](../)
* Espacio de nombres [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)