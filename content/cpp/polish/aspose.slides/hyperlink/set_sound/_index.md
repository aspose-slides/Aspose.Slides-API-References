---
title: set_Sound()
second_title: Aspose.Slides dla C++ – Referencja API
description: Reprezentuje dźwięk odtwarzany w hiperłączu. Zapisz IAudio.
type: docs
weight: 300
url: /pl/aspose.slides/hyperlink/set_sound/
---
## Hyperlink::set_Sound(System::SharedPtr\<IAudio\>) metoda


Reprezentuje dźwięk odtwarzany w hiperłączu. Zapisz [IAudio](../../iaudio/).

```cpp
void Aspose::Slides::Hyperlink::set_Sound(System::SharedPtr<IAudio> value) override
```

## Uwagi



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Pobierz hiperłącze pierwszego kształtu
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Wyodrębnij dźwięk hiperłącza jako tablicę bajtów
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IAudio](../../iaudio/)
* Klasa [Hyperlink](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)