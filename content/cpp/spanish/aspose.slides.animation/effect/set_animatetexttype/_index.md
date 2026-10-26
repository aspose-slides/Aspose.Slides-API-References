---
title: set_AnimateTextType()
second_title: Referencia de API de Aspose.Slides para C++
description: Define un tipo de animación de texto para el efecto. El texto de la forma puede animarse por letra, por palabra o todo a la vez. Escriba AnimateTextType.
type: docs
weight: 287
url: /es/aspose.slides.animation/effect/set_animatetexttype/
---
## Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) método


Define un tipo de animación de texto para el efecto. El texto de la forma puede animarse por letra, por palabra o todo de una vez. Escriba [AnimateTextType](../../animatetexttype/).

```cpp
void Aspose::Slides::Animation::Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value) override
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
* Clase [Effect](../)
* Espacio de nombres [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)