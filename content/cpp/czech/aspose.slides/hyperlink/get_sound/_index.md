---
title: get_Sound()
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: Reprezentuje přehrávaný zvuk hypertextového odkazu. Přečtěte si IAudio.
type: docs
weight: 287
url: /cs/aspose.slides/hyperlink/get_sound/
---
## Hyperlink::get_Sound() metoda


Representuje přehrávaný zvuk hypertextového odkazu. Přečtěte si [IAudio](../../iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Hyperlink::get_Sound() override
```

## Poznámky



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Získá hypertextový odkaz prvního tvaru
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Extrahuje zvuk hypertextového odkazu do pole bajtů
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IAudio](../../iaudio/)
* Třída [Hyperlink](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)