---
title: set_Sound()
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta il suono riprodotto dell'ipervincolo. Scrivi IAudio.
type: docs
weight: 300
url: /it/aspose.slides/hyperlink/set_sound/
---
## Hyperlink::set_Sound(System::SharedPtr\<IAudio\>) method

Rappresenta il suono riprodotto dell'ipervincolo. Scrivi [IAudio](../../iaudio/).

```cpp
void Aspose::Slides::Hyperlink::set_Sound(System::SharedPtr<IAudio> value) override
```

## Osservazioni


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Recupera il collegamento ipertestuale della prima forma
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Estrai il suono del collegamento ipertestuale in un array di byte
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudio](../../iaudio/)
* Class [Hyperlink](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)