---
title: get_RepeatUntilNextClick()
second_title: Referencia de API de Aspose.Slides para C++
description: Este atributo especifica si el efecto se repetirá hasta el siguiente clic. Leer bool.
type: docs
weight: 157
url: /es/aspose.slides.animation/timing/get_repeatuntilnextclick/
---
## Timing::get_RepeatUntilNextClick() método

Este atributo especifica si el efecto se repetirá hasta el siguiente clic. Leer **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilNextClick() override
```
## Observaciones

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Obtiene la secuencia de efectos para la primera diapositiva
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Obtiene el primer efecto de la secuencia principal.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Cambia el Timing/Repeat del efecto a "Until End of Slide"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```
## Ver también

* Clase [Timing](../)
* Espacio de nombres [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)