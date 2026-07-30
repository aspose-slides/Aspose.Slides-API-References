---
title: set_Sound()
second_title: Aspose.Slides pro C++ API Reference
description: Representuje přehrávaný zvuk hypertextového odkazu. Zapište IAudio.
type: docs
weight: 300
url: /cs/aspose.slides/hyperlink/set_sound/
---
## Hyperlink::set_Sound(System::SharedPtr\<IAudio\>) metoda


Představuje přehrávaný zvuk hypertextového odkazu. Zapište [IAudio](../../iaudio/).

```cpp
void Aspose::Slides::Hyperlink::set_Sound(System::SharedPtr<IAudio> value) override
```

## Poznámky



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Získá hypertextový odkaz první tvary
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Extrahuje zvuk hypertextového odkazu do bajtového pole
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IAudio](../../iaudio/)
* Třída [Hyperlink](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)