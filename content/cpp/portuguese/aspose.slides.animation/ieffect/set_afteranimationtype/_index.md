---
title: set_AfterAnimationType()
second_title: Aspose.Slides para C++ - Referência da API
description: Define um tipo de animação posterior para o efeito. Escreva AfterAnimationType.
type: docs
weight: 235
url: /pt/aspose.slides.animation/ieffect/set_afteranimationtype/
---
## IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) método


Define um tipo de animação posterior para o efeito. Escreva [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value)=0
```

## Observações



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Obtém o primeiro efeito do primeiro slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Altera a animação posterior do efeito para "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Veja Também

* Enum [AfterAnimationType](../../afteranimationtype/)
* Classe [IEffect](../)
* Espaço de nomes [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)