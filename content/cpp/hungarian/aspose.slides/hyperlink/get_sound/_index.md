---
title: get_Sound()
second_title: Aspose.Slides C++ API referencia
description: A hiperhivatkozás lejátszott hangját képviseli. Olvassa el IAudio.
type: docs
weight: 287
url: /hu/aspose.slides/hyperlink/get_sound/
---
## Hyperlink::get_Sound() metódus

A hiperhivatkozás lejátszott hangját képviseli. Olvassa el [IAudio](../../iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Hyperlink::get_Sound() override
```

## Megjegyzések

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Az első alakzat hiperhivatkozásának lekérése
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // A hiperhivatkozás hangjának kinyerése bájt tömbbe
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAudio](../../iaudio/)
* Osztály [Hyperlink](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)