---
title: get_Sound()
second_title: Aspose.Slides für C++ API Referenz
description: Stellt den abspielenden Ton des Hyperlinks dar. Lesen Sie IAudio.
type: docs
weight: 287
url: /de/aspose.slides/hyperlink/get_sound/
---
## Hyperlink::get_Sound() Methode

Stellt den abspielenden Ton des Hyperlinks dar. Lesen Sie [IAudio](../../iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Hyperlink::get_Sound() override
```

## Bemerkungen

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Hole den Hyperlink der ersten Form
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