---
title: get_AnimateTextType()
second_title: Referência da API Aspose.Slides para C++
description: Define um tipo de texto animado para o efeito. O texto da forma pode ser animado por letra, por palavra ou tudo de uma vez. Leia AnimateTextType.
type: docs
weight: 274
url: /pt/aspose.slides.animation/effect/get_animatetexttype/
---
## Effect::get_AnimateTextType() método


Define um tipo de texto animado para o efeito. O texto da forma pode ser animado por letra, por palavra ou tudo de uma vez. Leia [AnimateTextType](../../animatetexttype/).

```cpp
Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::Effect::get_AnimateTextType() override
```

## Observações



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Veja Também

* Enum [AnimateTextType](../../animatetexttype/)
* Classe [Effect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)