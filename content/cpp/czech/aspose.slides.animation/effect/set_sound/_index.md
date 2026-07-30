---
title: set_Sound()
second_title: Aspose.Slides pro C++ API referenci
description: Definuje vložený zvuk pro efekt. Zapište IAudio.
type: docs
weight: 183
url: /cs/aspose.slides.animation/effect/set_sound/
---
## Effect::set_Sound(System::SharedPtr\<IAudio\>) metoda


Definuje vložený zvuk pro efekt. Zapište [IAudio](../../../aspose.slides/iaudio/).

```cpp
void Aspose::Slides::Animation::Effect::set_Sound(System::SharedPtr<IAudio> value) override
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
* Jmenný prostor [Aspose::Slides::Animation](../../)
* Knihovna [Aspose.Slides](../../../)