---
title: set_RepeatUntilEndSlide()
second_title: Referência de API Aspose.Slides para C++
description: Este atributo especifica se o efeito será repetido até o final do slide. Escreva bool.
type: docs
weight: 144
url: /pt/aspose.slides.animation/timing/set_repeatuntilendslide/
---
## Timing::set_RepeatUntilEndSlide(bool) método


Este atributo especifica se o efeito será repetido até o final do slide. Escreva **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_RepeatUntilEndSlide(bool value) override
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

## Veja Também

* Classe [Timing](../)
* Espaço de nomes [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)