---
title: set_AnimateTextType()
second_title: Referencia de la API de Aspose.Slides para C++
description: Define un tipo de animación de texto para el efecto. El texto de la forma puede animarse por letra, por palabra o todo a la vez. Escriba AnimateTextType.
type: docs
weight: 287
url: /es/aspose.slides.animation/ieffect/set_animatetexttype/
---
## IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) método


Define un tipo de animación de texto para el efecto. El texto de la forma puede animarse por letra, por palabra o todo a la vez. Escriba [AnimateTextType](../../animatetexttype/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value)=0
```

## Observaciones



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Obtenga el primer efecto de la primera diapositiva.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Cambie el tipo de animación de texto del efecto a "Por letra"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Ver también

* Enum [AnimateTextType](../../animatetexttype/)
* Class [IEffect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)