---
title: set_Rewind()
second_title: Referencia de la API de Aspose.Slides para C++
description: Este atributo especifica si el efecto se rebobinará al terminar de reproducirse. Escriba bool.
type: docs
weight: 326
url: /es/aspose.slides.animation/itiming/set_rewind/
---
## ITiming::set_Rewind(bool) método


Este atributo especifica si el efecto se rebobinará al terminar de reproducirse. Escriba **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_Rewind(bool value)=0
```

## Observaciones



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Obtiene la secuencia de efectos para la primera diapositiva
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Obtiene el primer efecto de la secuencia principal.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Activa el Timing/Rewind del efecto.
effect->get_Timing()->set_Rewind(true);
```

## Ver también

* Clase [ITiming](../)
* Espacio de nombres [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)