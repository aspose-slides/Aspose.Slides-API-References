---
title: get_Sound()
second_title: Aspose.Slides för C++ API-referens
description: Representerar det spelade ljudet för hyperlänken. Läs IAudio.
type: docs
weight: 183
url: /sv/aspose.slides/ihyperlink/get_sound/
---
## IHyperlink::get_Sound() metod

Representerar det spelade ljudet för hyperlänken. Läs [IAudio](../../iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IHyperlink::get_Sound()=0
```

## Anmärkningar



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Hämta den första formens hyperlänk
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Extrahera hyperlänksljudet i en byte-array
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```




## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IAudio](../../iaudio/)
* Klass [IHyperlink](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)