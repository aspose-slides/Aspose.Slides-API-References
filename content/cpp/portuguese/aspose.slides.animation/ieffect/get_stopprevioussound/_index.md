---
title: get_StopPreviousSound()
second_title: Referência da API Aspose.Slides para C++
description: Este atributo especifica se o efeito de animação interrompe o som anterior. Leia bool.
type: docs
weight: 196
url: /pt/aspose.slides.animation/ieffect/get_stopprevioussound/
---
## IEffect::get_StopPreviousSound() método


Este atributo especifica se o efeito de animação interrompe o som anterior. Leia **bool**.

```cpp
virtual bool Aspose::Slides::Animation::IEffect::get_StopPreviousSound()=0
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
    // Altera o aprimoramento/áudio do segundo efeito para "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Veja também

* Classe [IEffect](../)
* Espaço de nomes [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)