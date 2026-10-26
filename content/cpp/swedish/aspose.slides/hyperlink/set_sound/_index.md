---
title: set_Sound()
second_title: Aspose.Slides för C++ API-referens
description: Representerar hyperlänkens uppspelningsljud. Skriv IAudio.
type: docs
weight: 300
url: /sv/aspose.slides/hyperlink/set_sound/
---
## Hyperlink::set_Sound(System::SharedPtr\<IAudio\>) metod


Representerar hyperlänkens uppspelningsljud. Skriv [IAudio](../../iaudio/).

```cpp
void Aspose::Slides::Hyperlink::set_Sound(System::SharedPtr<IAudio> value) override
```

## Anmärkningar



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Hämta den första formens hyperlänk
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Extrahera hyperlänkens ljud i en byte-array
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IAudio](../../iaudio/)
* Klass [Hyperlink](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)