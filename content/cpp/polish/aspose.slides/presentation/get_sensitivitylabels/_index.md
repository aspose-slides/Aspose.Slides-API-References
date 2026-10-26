---
title: get_SensitivityLabels()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Zwraca kolekcję etykiet wrażliwości zastosowanych w dokumencie prezentacji. Tylko do odczytu ISensitivityLabelCollection.
type: docs
weight: 378
url: /pl/aspose.slides/presentation/get_sensitivitylabels/
---
## Presentation::get_SensitivityLabels() metoda

Zwraca kolekcję etykiet wrażliwości zastosowanych do dokumentu prezentacji. Tylko do odczytu [ISensitivityLabelCollection](../../isensitivitylabelcollection/).

```cpp
System::SharedPtr<ISensitivityLabelCollection> Aspose::Slides::Presentation::get_SensitivityLabels() override
```

## Uwagi

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<ISensitivityLabelCollection> sensitivityLabels = pres->get_SensitivityLabels();

// Wypisz zastosowane etykiety
for (auto&& sensitivityLabel : sensitivityLabels)
{
    System::Console::WriteLine(System::String(u"Label Id ") + sensitivityLabel->get_Id() + u" from Azure AD site " + sensitivityLabel->get_SiteId());
}

// Dodaj nową etykietę
System::String labelIdString = u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}";
// Pobierz identyfikator etykiety wrażliwości z polityki
System::Guid siteIdGuid = System::Guid::Parse(u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}");
// Pobierz identyfikator witryny Azure AD z polityki
auto label = sensitivityLabels->Add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType::Privileged);
label->get_ContentMarkTypes()->Add(SensitivityLabelContentType::Footer);

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ISensitivityLabelCollection](../../isensitivitylabelcollection/)
* Klasa [Presentation](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)