---
title: get_Sound()
second_title: Odwołanie API Aspose.Slides dla C++
description: Reprezentuje odtwarzany dźwięk hiperłącza. Przeczytaj IAudio.
type: docs
weight: 287
url: /pl/aspose.slides/hyperlink/get_sound/
---
## Hyperlink::get_Sound() metoda


Reprezentuje odtwarzany dźwięk hiperłącza. Przeczytaj [IAudio](../../iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Hyperlink::get_Sound() override
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

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IAudio](../../iaudio/)
* Klasa [Hyperlink](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)