---
title: get_RepeatUntilEndSlide()
second_title: Referência da API Aspose.Slides para C++
description: Este atributo especifica se o efeito será repetido até o final do slide. Leia bool.
type: docs
weight: 131
url: /pt/aspose.slides.animation/timing/get_repeatuntilendslide/
---
## Timing::get_RepeatUntilEndSlide() método

Este atributo especifica se o efeito será repetido até o final do slide. Leia **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilEndSlide() override
```

## Observações

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## Ver também

* Classe [Timing](../)
* Espaço de nomes [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)