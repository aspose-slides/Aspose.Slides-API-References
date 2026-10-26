---
title: set_Sound()
second_title: Riferimento API Aspose.Slides per C++
description: Rappresenta il suono in riproduzione del collegamento ipertestuale. Scrivi IAudio.
type: docs
weight: 196
url: /it/aspose.slides/ihyperlink/set_sound/
---
## IHyperlink::set_Sound(System::SharedPtr\<IAudio\>) metodo

Rappresenta il suono in riproduzione del collegamento ipertestuale. Scrivi [IAudio](../../iaudio/).

```cpp
virtual void Aspose::Slides::IHyperlink::set_Sound(System::SharedPtr<IAudio> value)=0
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
* Classe [IAudio](../../iaudio/)
* Classe [IHyperlink](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)