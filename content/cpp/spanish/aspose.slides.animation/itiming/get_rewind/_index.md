---
title: get_Rewind()
second_title: Referencia de API de Aspose.Slides para C++
description: Este atributo especifica si el efecto se rebobinará cuando haya terminado de reproducirse. Leer bool.
type: docs
weight: 313
url: /es/aspose.slides.animation/itiming/get_rewind/
---
## ITiming::get_Rewind() método


Este atributo especifica si el efecto se rebobinará cuando haya terminado de reproducirse. Leer **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_Rewind()=0
```

## Observaciones



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Get the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Turn the effect Timing/Rewind on.
effect->get_Timing()->set_Rewind(true);
```

## Ver también

* Clase [ITiming](../)
* Espacio de nombres [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)