---
title: get_Sound()
second_title: Aspose.Slides voor C++ API Referentie
description: Geeft het afspelende geluid van de hyperlink weer. Lees IAudio.
type: docs
weight: 183
url: /nl/aspose.slides/ihyperlink/get_sound/
---
## IHyperlink::get_Sound() methode


Geeft het afspelende geluid van de hyperlink weer. Lees [IAudio](../../iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IHyperlink::get_Sound()=0
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
* Library [Aspose.Slides](../../../)