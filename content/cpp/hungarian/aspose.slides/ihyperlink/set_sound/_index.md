---
title: set_Sound()
second_title: Aspose.Slides C++ API-referencia
description: A hivatkozás lejátszott hangját képviseli. Írja IAudio.
type: docs
weight: 196
url: /hu/aspose.slides/ihyperlink/set_sound/
---
## IHyperlink::set_Sound(System::SharedPtr\<IAudio\>) metódus


A hivatkozás lejátszott hangját képviseli. Írja [IAudio](../../iaudio/).

```cpp
virtual void Aspose::Slides::IHyperlink::set_Sound(System::SharedPtr<IAudio> value)=0
```

## Megjegyzések



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Az első alakzat hivatkozásának lekérése
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // A hivatkozás hangjának kinyerése bájt tömbben
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```




## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IAudio](../../iaudio/)
* Osztály [IHyperlink](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)