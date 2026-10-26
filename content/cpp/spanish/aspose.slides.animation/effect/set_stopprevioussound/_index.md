---
title: set_StopPreviousSound()
second_title: Referencia de la API de Aspose.Slides para C++
description: Este atributo especifica si el efecto de animación detiene el sonido anterior. Escriba bool.
type: docs
weight: 209
url: /es/aspose.slides.animation/effect/set_stopprevioussound/
---
## Effect::set_StopPreviousSound(bool) método


Este atributo especifica si el efecto de animación detiene el sonido anterior. Escriba **bool**.

```cpp
void Aspose::Slides::Animation::Effect::set_StopPreviousSound(bool value) override
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
    // Cambiar el segundo efecto Mejora/Sonido a "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Ver también

* Clase [Effect](../)
* Espacio de nombres [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)