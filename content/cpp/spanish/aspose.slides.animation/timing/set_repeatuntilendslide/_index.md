---
title: set_RepeatUntilEndSlide()
second_title: Referencia de API de Aspose.Slides para C++
description: Este atributo especifica si el efecto se repetirá hasta el final de la diapositiva. Escriba bool.
type: docs
weight: 144
url: /es/aspose.slides.animation/timing/set_repeatuntilendslide/
---
## Timing::set_RepeatUntilEndSlide(bool) método


Este atributo especifica si el efecto se repetirá hasta el final de la diapositiva. Escriba **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_RepeatUntilEndSlide(bool value) override
```

## Observaciones



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## Ver también

* Clase [Timing](../)
* Espacio de nombres [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)