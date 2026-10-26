---
title: get_AfterAnimationType()
second_title: Referencia de API de Aspose.Slides para C++
description: Define un tipo de animación posterior para el efecto. Lea AfterAnimationType.
type: docs
weight: 222
url: /es/aspose.slides.animation/ieffect/get_afteranimationtype/
---
## IEffect::get_AfterAnimationType() método


Define un tipo de animación posterior para el efecto. Lea [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::IEffect::get_AfterAnimationType()=0
```

## Observaciones



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Obtenga el primer efecto de la primera diapositiva.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Cambie la animación posterior del efecto a "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Ver también

* Enum [AfterAnimationType](../../afteranimationtype/)
* Clase [IEffect](../)
* Espacio de nombres [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)