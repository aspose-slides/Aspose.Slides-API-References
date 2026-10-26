---
title: get_Rewind()
second_title: Referência da API Aspose.Slides para C++
description: Este atributo especifica se o efeito será rebobinado ao terminar a reprodução. Leitura bool.
type: docs
weight: 313
url: /pt/aspose.slides.animation/itiming/get_rewind/
---
## ITiming::get_Rewind() método


Este atributo especifica se o efeito será rebobinado ao terminar a reprodução. Leitura **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_Rewind()=0
```

## Observações



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Obtenha a sequência de efeitos para o primeiro slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Obtenha o primeiro efeito da sequência principal.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Ative o Timing/Rewind do efeito.
effect->get_Timing()->set_Rewind(true);
```

## Veja também

* Classe [ITiming](../)
* Namespace [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)