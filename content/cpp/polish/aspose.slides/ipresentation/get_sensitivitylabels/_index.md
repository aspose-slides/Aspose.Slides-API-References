---
title: get_SensitivityLabels()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Zwraca kolekcję etykiet poufności zastosowanych w dokumencie prezentacji. Tylko do odczytu ISensitivityLabelCollection.
type: docs
weight: 391
url: /pl/aspose.slides/ipresentation/get_sensitivitylabels/
---
## IPresentation::get_SensitivityLabels() metoda


Zwraca kolekcję etykiet poufności zastosowanych w dokumencie prezentacji. Tylko do odczytu [ISensitivityLabelCollection](../../isensitivitylabelcollection/).

```cpp
virtual System::SharedPtr<ISensitivityLabelCollection> Aspose::Slides::IPresentation::get_SensitivityLabels()=0
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
// Pobierz identyfikator etykiety poufności z polityki
System::Guid siteIdGuid = System::Guid::Parse(u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}");
// Pobierz identyfikator witryny Azure AD z polityki
auto label = sensitivityLabels->Add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType::Privileged);
label->get_ContentMarkTypes()->Add(SensitivityLabelContentType::Footer);

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ISensitivityLabelCollection](../../isensitivitylabelcollection/)
* Klasa [IPresentation](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)