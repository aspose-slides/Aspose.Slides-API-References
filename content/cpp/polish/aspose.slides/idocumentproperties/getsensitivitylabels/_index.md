---
title: GetSensitivityLabels()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Zwraca tablicę etykiet wrażliwości z własnych właściwości dokumentu (Microsoft Information Protection SDK Metadata).
type: docs
weight: 872
url: /pl/aspose.slides/idocumentproperties/getsensitivitylabels/
---
## IDocumentProperties::GetSensitivityLabels() metoda

Zwraca tablicę etykiet wrażliwości z własnych właściwości dokumentu (Microsoft Information Protection SDK Metadata).

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::IDocumentProperties::GetSensitivityLabels()=0
```
## Uwagi

Poniższy kod pokazuje, jak przenieść informacje o etykietach wrażliwości z własnych właściwości dokumentu do nowoczesnej kolekcji SensitivityLabels: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// Pobierz etykiety wrażliwości z własnych właściwości dokumentu
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // Dodaj etykietę do kolekcji
    // Tutaj możesz dodać sprawdzenie poprawności informacji o etykiecie (etykieta jest dostępna, itp.)
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```
## Zobacz również

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [ISensitivityLabel](../../isensitivitylabel/)
* Klasa [IDocumentProperties](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)