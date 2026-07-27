---
title: set_Rewind()
second_title: Referencia de API de Aspose.Slides para C++
description: Este atributo especifica si el efecto retrocederá al terminar de reproducirse. Escriba bool.
type: docs
weight: 248
url: /es/aspose.slides.animation/timing/set_rewind/
---
## Timing::set_Rewind(bool) método


Este atributo especifica si el efecto retrocederá al terminar de reproducirse. Escriba **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_Rewind(bool value) override
```

## Comentarios



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