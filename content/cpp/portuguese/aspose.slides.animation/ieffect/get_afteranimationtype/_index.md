---
title: get_AfterAnimationType()
second_title: Referência da API Aspose.Slides para C++
description: Define um tipo de animação posterior para o efeito. Leia AfterAnimationType.
type: docs
weight: 222
url: /pt/aspose.slides.animation/ieffect/get_afteranimationtype/
---
## IEffect::get_AfterAnimationType() método


Define um tipo de animação posterior para o efeito. Leia [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::IEffect::get_AfterAnimationType()=0
```

## Observações



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Obtenha o primeiro efeito do primeiro slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Altere o efeito após a animação para "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Ver também

* Enum [AfterAnimationType](../../afteranimationtype/)
* Classe [IEffect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)