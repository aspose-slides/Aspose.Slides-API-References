---
title: get_Sound()
second_title: Aspose.Slides pro C++ API Reference
description: Definuje vložený zvuk pro efekt. Přečtěte si IAudio.
type: docs
weight: 170
url: /cs/aspose.slides.animation/effect/get_sound/
---
## Effect::get_Sound() metoda


Definuje vložený zvuk pro efekt. Přečtěte si [IAudio](../../../aspose.slides/iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Animation::Effect::get_Sound() override
```

## Poznámky



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// Získá sekvenci efektů pro snímek
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // Extrahuje zvuk efektu do pole bajtů
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```




## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IAudio](../../../aspose.slides/iaudio/)
* Třída [Effect](../)
* Obor názvů [Aspose::Slides::Animation](../../)
* Knihovna [Aspose.Slides](../../../)