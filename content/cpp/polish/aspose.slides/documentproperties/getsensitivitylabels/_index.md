---
title: GetSensitivityLabels()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca tablicę sensitivity labels z niestandardowych właściwości dokumentu (Microsoft Information Protection SDK Metadata).
type: docs
weight: 859
url: /pl/aspose.slides/documentproperties/getsensitivitylabels/
---
## DocumentProperties::GetSensitivityLabels() metoda


Zwraca tablicę sensitivity labels z niestandardowych właściwości dokumentu (Microsoft Information Protection SDK Metadata).

```cpp
System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::DocumentProperties::GetSensitivityLabels() override
```

## Uwagi


Poniższy kod pokazuje, jak przenieść informacje o sensitivity labels z niestandardowych właściwości dokumentu do nowoczesnej kolekcji SensitivityLabels: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// Pobierz sensitivity labels z niestandardowych właściwości dokumentu
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // Dodaj etykietę do kolekcji
    // Tutaj możesz dodać sprawdzenie poprawności informacji o etykiecie (etykieta jest dostępna, itp)
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [ISensitivityLabel](../../isensitivitylabel/)
* Klasa [DocumentProperties](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)