---
title: set_Sound()
second_title: Aspose.Slides för C++ API-referens
description: Representerar uppspelningsljudet för hyperlänken. Skriv IAudio.
type: docs
weight: 196
url: /sv/aspose.slides/ihyperlink/set_sound/
---
## IHyperlink::set_Sound(System::SharedPtr\<IAudio\>) metod

Representerar uppspelningsljudet för hyperlänken. Skriv [IAudio](../../iaudio/).

```cpp
virtual void Aspose::Slides::IHyperlink::set_Sound(System::SharedPtr<IAudio> value)=0
```

## Anmärkningar

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Hämta den första formens hyperlänk
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Extrahera hyperlänkens ljud som byte-array
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IAudio](../../iaudio/)
* Klass [IHyperlink](../)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)