---
title: get_AfterAnimationType()
second_title: Referência da API Aspose.Slides para C++
description: Define um tipo de animação posterior para o efeito. Leia AfterAnimationType.
type: docs
weight: 222
url: /pt/aspose.slides.animation/effect/get_afteranimationtype/
---
## Effect::get_AfterAnimationType() método


Define um tipo de animação posterior para o efeito. Leia [AfterAnimationType](../../afteranimationtype/).

```cpp
Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::Effect::get_AfterAnimationType() override
```

## Observações



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Obtenha o primeiro efeito do primeiro slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Altere a animação posterior do efeito para "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Ver Também

* Enum [AfterAnimationType](../../afteranimationtype/)
* Class [Effect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)