---
title: get_Sound()
second_title: Aspose.Slides pro C++ - referenční API
description: Představuje přehrávaný zvuk hypertextového odkazu. Přečtěte si IAudio.
type: docs
weight: 183
url: /cs/aspose.slides/ihyperlink/get_sound/
---
## IHyperlink::get_Sound() metoda


Představuje přehrávaný zvuk hypertextového odkazu. Přečtěte si [IAudio](../../iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IHyperlink::get_Sound()=0
```

## Poznámky



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Získá první hypertextový odkaz tvaru
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
* Třída [IHyperlink](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)