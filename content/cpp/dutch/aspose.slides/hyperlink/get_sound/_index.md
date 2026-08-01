---
title: get_Sound()
second_title: Aspose.Slides voor C++ API-referentie
description: Geeft het afspelen van het geluid van de hyperlink weer. Lees IAudio.
type: docs
weight: 287
url: /nl/aspose.slides/hyperlink/get_sound/
---
## Hyperlink::get_Sound() methode


Geeft het afspelen van het geluid van de hyperlink weer. Lees [IAudio](../../iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Hyperlink::get_Sound() override
```

## Opmerkingen



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Haal de eerste shape hyperlink op
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Extraheer het hyperlinkgeluid in byte array
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAudio](../../iaudio/)
* Klasse [Hyperlink](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)