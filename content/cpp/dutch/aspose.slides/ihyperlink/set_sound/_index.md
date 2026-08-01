---
title: set_Sound()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt het afspelende geluid van de hyperlink voor. Schrijf IAudio.
type: docs
weight: 196
url: /nl/aspose.slides/ihyperlink/set_sound/
---
## IHyperlink::set_Sound(System::SharedPtr\<IAudio\>) methode


Stelt het afspelende geluid van de hyperlink voor. Schrijf [IAudio](../../iaudio/).

```cpp
virtual void Aspose::Slides::IHyperlink::set_Sound(System::SharedPtr<IAudio> value)=0
```

## Opmerkingen


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Haal de eerste vormhyperlink op
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Extraheer het hyperlinkgeluid in een byte-array
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```



## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAudio](../../iaudio/)
* Klasse [IHyperlink](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)