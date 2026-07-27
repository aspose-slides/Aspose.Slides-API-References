---
title: get_AfterAnimationType()
second_title: Referencia de API de Aspose.Slides para C++
description: Define un tipo de animación posterior para el efecto. Lea AfterAnimationType.
type: docs
weight: 222
url: /es/aspose.slides.animation/effect/get_afteranimationtype/
---
## Effect::get_AfterAnimationType() método


Define un tipo de animación posterior para el efecto. Lea [AfterAnimationType](../../afteranimationtype/).

```cpp
Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::Effect::get_AfterAnimationType() override
```

## Observaciones



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Obtener el primer efecto de la primera diapositiva.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Cambiar la animación posterior del efecto a "Ocultar en el siguiente clic del ratón"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Ver también

* Enumeración [AfterAnimationType](../../afteranimationtype/)
* Clase [Effect](../)
* Espacio de nombres [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)