---
title: set_AdvanceAfter()
second_title: Referência da API Aspose.Slides para C++
description: Este atributo especifica se a apresentação de slides avançará para o próximo slide após um determinado tempo. Escreva bool.
type: docs
weight: 118
url: /pt/aspose.slides.slideshow/slideshowtransition/set_advanceafter/
---
## SlideShowTransition::set_AdvanceAfter(bool) método


Este atributo especifica se a apresentação de slides avançará para o próximo slide após um certo tempo. Escreva **bool**.

```cpp
void Aspose::Slides::SlideShow::SlideShowTransition::set_AdvanceAfter(bool value) override
```

## Observações


```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Obtém a primeira transição de slide
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Verifica se a flag Avançar Slide Depois está marcada
if (slideTransition->get_AdvanceAfter())
{
    // Obtém o valor do tempo de Avançar Slide Depois
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Veja também

* Classe [SlideShowTransition](../)
* Espaço de nomes [Aspose::Slides::SlideShow](../../)
* Biblioteca [Aspose.Slides](../../../)