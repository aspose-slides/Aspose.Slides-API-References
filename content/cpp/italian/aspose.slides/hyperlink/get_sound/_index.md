---
title: get_Sound()
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta il suono in riproduzione del collegamento ipertestuale. Leggi IAudio.
type: docs
weight: 287
url: /it/aspose.slides/hyperlink/get_sound/
---
## Hyperlink::get_Sound() metodo

Rappresenta il suono in riproduzione del collegamento ipertestuale. Leggi [IAudio](../../iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Hyperlink::get_Sound() override
```

## Osservazioni

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Ottieni il collegamento ipertestuale della prima forma
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
* Classe [Hyperlink](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)