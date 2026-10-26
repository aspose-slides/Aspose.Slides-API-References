---
title: set_StopPreviousSound()
second_title: Referência da API Aspose.Slides para C++
description: Este atributo especifica se o efeito de animação interrompe o som anterior. Escreva bool.
type: docs
weight: 209
url: /pt/aspose.slides.animation/ieffect/set_stopprevioussound/
---
## IEffect::set_StopPreviousSound(bool) método


Este atributo especifica se o efeito de animação interrompe o som anterior. Escreva **bool**.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_StopPreviousSound(bool value)=0
```

## Observações



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Obtém o primeiro efeito do primeiro slide.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Obtém o primeiro efeito do segundo slide.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // Altera a propriedade Enhancements/Sound do segundo efeito para "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Ver também

* Classe [IEffect](../)
* Espaço de nomes [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)