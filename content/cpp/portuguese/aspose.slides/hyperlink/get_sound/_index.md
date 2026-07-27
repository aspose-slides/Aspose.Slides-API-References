---
title: get_Sound()
second_title: Referência da API Aspose.Slides para C++
description: Representa o som de reprodução do hyperlink. Leia IAudio.
type: docs
weight: 287
url: /pt/aspose.slides/hyperlink/get_sound/
---
## Hyperlink::get_Sound() método

Representa o som de reprodução do hyperlink. Leia [IAudio](../../iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Hyperlink::get_Sound() override
```

## Observações

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Obtenha o hyperlink da primeira forma
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Extraia o som do hyperlink em um array de bytes
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAudio](../../iaudio/)
* Classe [Hyperlink](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)