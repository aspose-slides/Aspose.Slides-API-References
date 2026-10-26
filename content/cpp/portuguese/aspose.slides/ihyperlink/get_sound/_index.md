---
title: get_Sound()
second_title: Aspose.Slides para C++ Referência da API
description: Representa o som em reprodução do hyperlink. Leia IAudio.
type: docs
weight: 183
url: /pt/aspose.slides/ihyperlink/get_sound/
---
## IHyperlink::get_Sound() método

Representa o som em reprodução do hyperlink. Leia [IAudio](../../iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IHyperlink::get_Sound()=0
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
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)