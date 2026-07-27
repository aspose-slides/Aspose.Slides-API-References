---
title: get_RepeatUntilEndSlide()
second_title: Referencia de API de Aspose.Slides para C++
description: Este atributo especifica si el efecto se repetirá hasta el final de la diapositiva. Leer bool.
type: docs
weight: 131
url: /es/aspose.slides.animation/itiming/get_repeatuntilendslide/
---
## ITiming::get_RepeatUntilEndSlide() método



Este atributo especifica si el efecto se repetirá hasta el final de la diapositiva. Leer **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilEndSlide()=0
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

* Clase [ITiming](../)
* Espacio de nombres [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)