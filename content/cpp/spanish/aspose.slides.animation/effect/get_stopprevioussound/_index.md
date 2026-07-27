---
title: get_StopPreviousSound()
second_title: Referencia de API de Aspose.Slides para C++
description: Este atributo especifica si el efecto de animación detiene el sonido anterior. Leer bool.
type: docs
weight: 196
url: /es/aspose.slides.animation/effect/get_stopprevioussound/
---
## Effect::get_StopPreviousSound() método


Este atributo especifica si el efecto de animación detiene el sonido anterior. Leer **bool**.

```cpp
bool Aspose::Slides::Animation::Effect::get_StopPreviousSound() override
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

* Clase [Effect](../)
* Espacio de nombres [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)