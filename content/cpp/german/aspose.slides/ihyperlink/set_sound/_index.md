---
title: set_Sound()
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt den abgespielten Ton des Hyperlinks dar. Schreiben Sie IAudio.
type: docs
weight: 196
url: /de/aspose.slides/ihyperlink/set_sound/
---
## IHyperlink::set_Sound(System::SharedPtr\<IAudio\>) Methode

Stellt den abgespielten Ton des Hyperlinks dar. Schreiben Sie [IAudio](../../iaudio/).

```cpp
virtual void Aspose::Slides::IHyperlink::set_Sound(System::SharedPtr<IAudio> value)=0
```

## Anmerkungen

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Erhalte den Hyperlink der ersten Form
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Extrahiere den Hyperlink-Sound als Byte-Array
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## Siehe auch

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [IAudio](../../iaudio/)
* Klasse [IHyperlink](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)