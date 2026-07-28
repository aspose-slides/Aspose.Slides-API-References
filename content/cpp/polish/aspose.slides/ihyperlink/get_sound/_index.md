---
title: get_Sound()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Reprezentuje odtwarzany dźwięk hiperłącza. Przeczytaj IAudio.
type: docs
weight: 183
url: /pl/aspose.slides/ihyperlink/get_sound/
---
## IHyperlink::get_Sound() metoda


Reprezentuje odtwarzany dźwięk hiperłącza. Przeczytaj [IAudio](../../iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IHyperlink::get_Sound()=0
```

## Uwagi



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Pobierz pierwsze hiperłącze kształtu
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
* Klasa [IHyperlink](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)