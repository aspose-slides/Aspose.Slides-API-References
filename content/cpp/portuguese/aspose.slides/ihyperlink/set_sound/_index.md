---
title: set_Sound()
second_title: Referência da API Aspose.Slides para C++
description: Representa o som reproduzido do hiperlink. Escreva IAudio.
type: docs
weight: 196
url: /pt/aspose.slides/ihyperlink/set_sound/
---
## IHyperlink::set_Sound(System::SharedPtr\<IAudio\>) método

Representa o som reproduzido do hiperlink. Escreva [IAudio](../../iaudio/).

```cpp
virtual void Aspose::Slides::IHyperlink::set_Sound(System::SharedPtr<IAudio> value)=0
```

## Observações



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Obter o hyperlink da primeira forma
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Extrair o som do hyperlink em array de bytes
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```




## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAudio](../../iaudio/)
* Classe [IHyperlink](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)