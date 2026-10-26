---
title: set_Sound()
second_title: Referência da API Aspose.Slides para C++
description: Representa o som de reprodução do hyperlink. Escreva IAudio.
type: docs
weight: 300
url: /pt/aspose.slides/hyperlink/set_sound/
---
## Hyperlink::set_Sound(System::SharedPtr\<IAudio\>) método


Representa o som de reprodução do hyperlink. Escreva [IAudio](../../iaudio/).

```cpp
void Aspose::Slides::Hyperlink::set_Sound(System::SharedPtr<IAudio> value) override
```

## Observações



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Obtém o hyperlink da primeira forma
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Extrai o som do hyperlink em array de bytes
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAudio](../../iaudio/)
* Classe [Hyperlink](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)