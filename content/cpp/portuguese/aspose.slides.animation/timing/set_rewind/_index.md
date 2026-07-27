---
title: set_Rewind()
second_title: Aspose.Slides para Referência da API C++
description: Este atributo especifica se o efeito será retrocedido ao terminar a reprodução. Escreva bool.
type: docs
weight: 248
url: /pt/aspose.slides.animation/timing/set_rewind/
---
## Timing::set_Rewind(bool) método

Este atributo especifica se o efeito será retrocedido ao terminar a reprodução. Escreva **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_Rewind(bool value) override
```

## Observações



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Get the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Turn the effect Timing/Rewind on.
effect->get_Timing()->set_Rewind(true);
```

## Ver também

* Classe [Timing](../)
* Espaço de nomes [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)