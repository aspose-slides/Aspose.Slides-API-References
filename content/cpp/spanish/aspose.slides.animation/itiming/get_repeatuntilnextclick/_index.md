---
title: get_RepeatUntilNextClick()
second_title: Referencia de la API de Aspose.Slides para C++
description: Este atributo especifica si el efecto se repetirá hasta el siguiente clic. Leer bool.
type: docs
weight: 157
url: /es/aspose.slides.animation/itiming/get_repeatuntilnextclick/
---
## ITiming::get_RepeatUntilNextClick() método

Este atributo especifica si el efecto se repetirá hasta el siguiente clic. Leer **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilNextClick()=0
```

## Observaciones

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Obtiene la secuencia de efectos para la primera diapositiva
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Obtiene el primer efecto de la secuencia principal.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Cambia el Timing/Repeat del efecto a "Hasta el final de la diapositiva"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## Ver también

* Clase [ITiming](../)
* Espacio de nombres [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)