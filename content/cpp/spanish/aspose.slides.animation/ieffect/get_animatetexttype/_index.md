---
title: get_AnimateTextType()
second_title: Referencia de la API de Aspose.Slides para C++
description: Define un tipo de texto animado para el efecto. El texto de la forma puede animarse por letra, por palabra o todo a la vez. Lea AnimateTextType.
type: docs
weight: 274
url: /es/aspose.slides.animation/ieffect/get_animatetexttype/
---
## IEffect::get_AnimateTextType() método


Define un tipo de texto animado para el efecto. El texto de la forma puede animarse por letra, por palabra o todo a la vez. Lea [AnimateTextType](../../animatetexttype/).

```cpp
virtual Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::IEffect::get_AnimateTextType()=0
```

## Observaciones



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Ver también

* Enum [AnimateTextType](../../animatetexttype/)
* Class [IEffect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)