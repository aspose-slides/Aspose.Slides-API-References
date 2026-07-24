---
title: set_Sound()
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt den wiedergegebenen Ton des Hyperlinks dar. Schreiben IAudio.
type: docs
weight: 300
url: /de/aspose.slides/hyperlink/set_sound/
---
## Hyperlink::set_Sound(System::SharedPtr\<IAudio\>) Methode

Stellt den wiedergegebenen Ton des Hyperlinks dar. Schreiben [IAudio](../../iaudio/).

```cpp
void Aspose::Slides::Hyperlink::set_Sound(System::SharedPtr<IAudio> value) override
```

## Anmerkungen



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Hole den ersten Shape-Hyperlink
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Extrahiere den Hyperlink-Sound als Byte-Array
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAudio](../../iaudio/)
* Klasse [Hyperlink](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)