---
title: get_Sound()
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta il suono riprodotto del collegamento ipertestuale. Leggi IAudio.
type: docs
weight: 183
url: /it/aspose.slides/ihyperlink/get_sound/
---
## IHyperlink::get_Sound() metodo


Rappresenta il suono riprodotto del collegamento ipertestuale. Leggi [IAudio](../../iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IHyperlink::get_Sound()=0
```

## Osservazioni



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Ottieni il primo collegamento ipertestuale della forma
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
* Class [IHyperlink](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)