---
title: set_AdvanceAfter()
second_title: Referência da API Aspose.Slides para C++
description: Este atributo especifica se a apresentação será avançada para o próximo slide após um determinado tempo. Escreva bool.
type: docs
weight: 118
url: /pt/aspose.slides/islideshowtransition/set_advanceafter/
---
## ISlideShowTransition::set_AdvanceAfter(bool) método


Este atributo especifica se a apresentação será avançada para o próximo slide após um determinado tempo. Escreva **bool**.

```cpp
virtual void Aspose::Slides::ISlideShowTransition::set_AdvanceAfter(bool value)=0
```

## Observações



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Obter a primeira transição de slide
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Verificar se a bandeira Advance Slide After está marcada
if (slideTransition->get_AdvanceAfter())
{
    // Obter o valor de tempo Advance Slide After
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Veja também

* Classe [ISlideShowTransition](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)