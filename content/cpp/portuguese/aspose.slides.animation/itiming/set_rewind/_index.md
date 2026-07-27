---
title: set_Rewind()
second_title: Referência da API Aspose.Slides para C++
description: Este atributo especifica se o efeito será rebobinado ao terminar a reprodução. Escreva bool.
type: docs
weight: 326
url: /pt/aspose.slides.animation/itiming/set_rewind/
---
## ITiming::set_Rewind(bool) método


Este atributo especifica se o efeito será rebobinado ao terminar a reprodução. Escreva **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_Rewind(bool value)=0
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

* Classe [ITiming](../)
* Espaço de nomes [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)