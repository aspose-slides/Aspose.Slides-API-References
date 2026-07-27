---
title: get_RepeatUntilNextClick()
second_title: Aspose.Slides para C++ Referência da API
description: Este atributo especifica se o efeito será repetido até o próximo clique. Leia bool.
type: docs
weight: 157
url: /pt/aspose.slides.animation/itiming/get_repeatuntilnextclick/
---
## ITiming::get_RepeatUntilNextClick() método

Este atributo especifica se o efeito será repetido até o próximo clique. Leia **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilNextClick()=0
```

## Observações

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Obtém a sequência de efeitos para o primeiro slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Obtém o primeiro efeito da sequência principal.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Altera o Timing/Repeat do efeito para "Until End of Slide"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## Veja Também

* Classe [ITiming](../)
* Espaço de nomes [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)