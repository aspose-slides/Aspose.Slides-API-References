---
title: get_Sound()
second_title: Aspose.Slides för C++ API-referens
description: Representerar ljudet som spelas för hyperlänken. Läs IAudio.
type: docs
weight: 287
url: /sv/aspose.slides/hyperlink/get_sound/
---
## Hyperlink::get_Sound() metod

Representerar ljudet som spelas för hyperlänken. Läs [IAudio](../../iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Hyperlink::get_Sound() override
```

## Anmärkningar

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Hämta hyperlänken för den första formen
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Extrahera hyperlänkens ljud i byte-array
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IAudio](../../iaudio/)
* Klass [Hyperlink](../)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)