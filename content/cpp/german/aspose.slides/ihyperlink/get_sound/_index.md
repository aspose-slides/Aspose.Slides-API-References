---
title: get_Sound()
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt den wiedergegebenen Ton des Hyperlinks dar. Lesen Sie IAudio.
type: docs
weight: 183
url: /de/aspose.slides/ihyperlink/get_sound/
---
## IHyperlink::get_Sound() Methode

Stellt den wiedergegebenen Ton des Hyperlinks dar. Lesen Sie [IAudio](../../iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IHyperlink::get_Sound()=0
```

## Hinweise



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Den ersten Shape-Hyperlink abrufen
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Extrahiere den Hyperlink-Sound in ein Byte-Array
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```




## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAudio](../../iaudio/)
* Klasse [IHyperlink](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)