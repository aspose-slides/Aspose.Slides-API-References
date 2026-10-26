---
title: get_Rewind()
second_title: Referencia de API de Aspose.Slides for C++
description: Este atributo especifica si el efecto se rebobinará cuando termine de reproducirse. Lee bool.
type: docs
weight: 235
url: /es/aspose.slides.animation/timing/get_rewind/
---
## Timing::get_Rewind() método


Este atributo especifica si el efecto se rebobinará cuando termine de reproducirse. Lee **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_Rewind() override
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

* Clase [Timing](../)
* Espacio de nombres [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)