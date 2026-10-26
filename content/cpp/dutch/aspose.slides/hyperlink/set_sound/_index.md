---
title: set_Sound()
second_title: Aspose.Slides voor C++ API-referentie
description: Geeft het afspelen van het geluid van de hyperlink weer. Schrijf IAudio.
type: docs
weight: 300
url: /nl/aspose.slides/hyperlink/set_sound/
---
## Hyperlink::set_Sound(System::SharedPtr\<IAudio\>) methode


Geeft het afspelen van het geluid van de hyperlink weer. Schrijf [IAudio](../../iaudio/).

```cpp
void Aspose::Slides::Hyperlink::set_Sound(System::SharedPtr<IAudio> value) override
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
* Klasse [Hyperlink](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)