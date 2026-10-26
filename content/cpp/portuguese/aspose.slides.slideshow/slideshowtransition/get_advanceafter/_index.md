---
title: get_AdvanceAfter()
second_title: Aspose.Slides para C++ Referência da API
description: Este atributo especifica se a apresentação de slides avançará para o próximo slide após um determinado tempo. Leia bool.
type: docs
weight: 105
url: /pt/aspose.slides.slideshow/slideshowtransition/get_advanceafter/
---
## SlideShowTransition::get_AdvanceAfter() método

Este atributo especifica se a apresentação de slides avançará para o próximo slide após um determinado tempo. Leia **bool**.

```cpp
bool Aspose::Slides::SlideShow::SlideShowTransition::get_AdvanceAfter() override
```

## Observações

```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Obter a primeira transição de slide
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Verifique se a flag Advance Slide After está marcada
if (slideTransition->get_AdvanceAfter())
{
    // Obter o valor de Advance Slide After Time
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Veja também

* Classe [SlideShowTransition](../)
* Espaço de nomes [Aspose::Slides::SlideShow](../../)
* Biblioteca [Aspose.Slides](../../../)