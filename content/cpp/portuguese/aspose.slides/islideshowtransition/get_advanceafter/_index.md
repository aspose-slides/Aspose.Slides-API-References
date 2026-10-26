---
title: get_AdvanceAfter()
second_title: Aspose.Slides para C++ – Referência da API
description: Este atributo especifica se a apresentação de slides avançará para o próximo slide após um determinado tempo. Leia bool.
type: docs
weight: 105
url: /pt/aspose.slides/islideshowtransition/get_advanceafter/
---
## ISlideShowTransition::get_AdvanceAfter() método


Este atributo especifica se a apresentação de slides avançará para o próximo slide após um determinado tempo. Leia **bool**.

```cpp
virtual bool Aspose::Slides::ISlideShowTransition::get_AdvanceAfter()=0
```

## Observações



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Obtém a primeira transição de slide
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Verifica se a bandeira Advance Slide After está marcada
if (slideTransition->get_AdvanceAfter())
{
    // Obtém o valor do tempo de Advance Slide After
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Veja também

* Classe [ISlideShowTransition](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)