---
title: set_Sound()
second_title: Aspose.Slides dla C++ Referencja API
description: Reprezentuje odtwarzany dźwięk hiperłącza. Zapisz IAudio.
type: docs
weight: 196
url: /pl/aspose.slides/ihyperlink/set_sound/
---
## IHyperlink::set_Sound(System::SharedPtr\<IAudio\>) metoda


Reprezentuje odtwarzany dźwięk hiperłącza. Zapisz [IAudio](../../iaudio/).

```cpp
virtual void Aspose::Slides::IHyperlink::set_Sound(System::SharedPtr<IAudio> value)=0
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
* Klasa [IHyperlink](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)