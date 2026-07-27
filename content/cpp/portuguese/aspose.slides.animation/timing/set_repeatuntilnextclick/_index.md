---
title: set_RepeatUntilNextClick()
second_title: Referência da API Aspose.Slides para C++
description: Este atributo especifica se o efeito será repetido até o próximo clique. Escreva bool.
type: docs
weight: 170
url: /pt/aspose.slides.animation/timing/set_repeatuntilnextclick/
---
## Timing::set_RepeatUntilNextClick(bool) método

Este atributo especifica se o efeito será repetido até o próximo clique. Escreva **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_RepeatUntilNextClick(bool value) override
```

## Observações



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## Ver também

* Classe [Timing](../)
* Namespace [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)