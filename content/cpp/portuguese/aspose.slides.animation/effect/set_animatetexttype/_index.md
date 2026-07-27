---
title: set_AnimateTextType()
second_title: Aspose.Slides para C++ Referência da API
description: Define um tipo de texto animado para o efeito. O texto da forma pode ser animado por letra, por palavra ou tudo de uma vez. Escreva AnimateTextType.
type: docs
weight: 287
url: /pt/aspose.slides.animation/effect/set_animatetexttype/
---
## Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) método

Define um tipo de animação de texto para o efeito. O texto da forma pode ser animado por letra, por palavra ou tudo de uma vez. Escreva [AnimateTextType](../../animatetexttype/).

```cpp
void Aspose::Slides::Animation::Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value) override
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
* Espaço de nomes [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)