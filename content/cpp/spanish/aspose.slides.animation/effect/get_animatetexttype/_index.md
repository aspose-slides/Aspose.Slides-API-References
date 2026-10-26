---
title: get_AnimateTextType()
second_title: Referencia de la API de Aspose.Slides para C++
description: Define un tipo de texto animado para el efecto. El texto de la forma puede animarse por letra, por palabra o de una sola vez. Lea AnimateTextType.
type: docs
weight: 274
url: /es/aspose.slides.animation/effect/get_animatetexttype/
---
## Effect::get_AnimateTextType() método


Define un tipo de texto animado para el efecto. El texto de la forma puede animarse por letra, por palabra o todo a la vez. Lea [AnimateTextType](../../animatetexttype/).

```cpp
Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::Effect::get_AnimateTextType() override
```

## Observaciones



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Obtener el primer efecto de la primera diapositiva.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Cambiar el tipo de texto animado del efecto a "Por letra"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Ver también

* Enumeración [AnimateTextType](../../animatetexttype/)
* Clase [Effect](../)
* Espacio de nombres [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)