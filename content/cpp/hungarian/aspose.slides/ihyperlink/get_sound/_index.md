---
title: get_Sound()
second_title: Aspose.Slides C++ API referenciához
description: A hiperhivatkozás lejátszott hangját jelöli. Olvassa el IAudio.
type: docs
weight: 183
url: /hu/aspose.slides/ihyperlink/get_sound/
---
## IHyperlink::get_Sound() metódus


A hiperhivatkozás lejátszott hangját képviseli. Olvassa el [IAudio](../../iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IHyperlink::get_Sound()=0
```

## Megjegyzések


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Az első alakzat hiperhivatkozása
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Kinyeri a hiperhivatkozás hangját bájttömbben
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```


## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAudio](../../iaudio/)
* Osztály [IHyperlink](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)