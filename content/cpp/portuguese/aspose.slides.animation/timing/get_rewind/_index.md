---
title: get_Rewind()
second_title: Referência da API Aspose.Slides para C++
description: Este atributo especifica se o efeito será retrocedido ao terminar a reprodução. Leitura bool.
type: docs
weight: 235
url: /pt/aspose.slides.animation/timing/get_rewind/
---
## Timing::get_Rewind() método


Este atributo especifica se o efeito será retrocedido ao terminar a reprodução. Leitura **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_Rewind() override
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

## Veja Também

* Classe [Timing](../)
* Espaço de nomes [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)