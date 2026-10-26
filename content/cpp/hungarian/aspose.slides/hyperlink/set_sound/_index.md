---
title: set_Sound()
second_title: Aspose.Slides C++ API referencia
description: A hiperhivatkozás lejátszott hangját jelenti. Írja IAudio.
type: docs
weight: 300
url: /hu/aspose.slides/hyperlink/set_sound/
---
## Hyperlink::set_Sound(System::SharedPtr\<IAudio\>) metódus


A hiperhivatkozás lejátszott hangját jelenti. Írja [IAudio](../../iaudio/).

```cpp
void Aspose::Slides::Hyperlink::set_Sound(System::SharedPtr<IAudio> value) override
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
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)