---
title: set_Sound()
second_title: Aspose.Slides pro C++ referenční příručku API
description: Představuje přehrávaný zvuk hypertextového odkazu. Zapište IAudio.
type: docs
weight: 196
url: /cs/aspose.slides/ihyperlink/set_sound/
---
## IHyperlink::set_Sound(System::SharedPtr\<IAudio\>) metoda

Představuje přehrávaný zvuk hypertextového odkazu. Zapište [IAudio](../../iaudio/).

```cpp
virtual void Aspose::Slides::IHyperlink::set_Sound(System::SharedPtr<IAudio> value)=0
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
* třída [IAudio](../../iaudio/)
* třída [IHyperlink](../)
* jmenný prostor [Aspose::Slides](../../)
* knihovna [Aspose.Slides](../../../)