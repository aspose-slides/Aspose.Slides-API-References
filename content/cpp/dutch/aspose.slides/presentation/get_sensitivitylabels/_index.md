---
title: get_SensitivityLabels()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de collectie van gevoeligheidslabels die op het presentatiedocument zijn toegepast. Alleen-lezen ISensitivityLabelCollection.
type: docs
weight: 378
url: /nl/aspose.slides/presentation/get_sensitivitylabels/
---
## Presentation::get_SensitivityLabels() methode

Retourneert de collectie van gevoeligheidslabels die op het presentatiedocument zijn toegepast. Alleen-lezen [ISensitivityLabelCollection](../../isensitivitylabelcollection/).

```cpp
System::SharedPtr<ISensitivityLabelCollection> Aspose::Slides::Presentation::get_SensitivityLabels() override
```

## Opmerkingen



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<ISensitivityLabelCollection> sensitivityLabels = pres->get_SensitivityLabels();

// Print de toegepaste labels
for (auto&& sensitivityLabel : sensitivityLabels)
{
    System::Console::WriteLine(System::String(u"Label Id ") + sensitivityLabel->get_Id() + u" from Azure AD site " + sensitivityLabel->get_SiteId());
}

// Voeg het nieuwe label toe
System::String labelIdString = u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}";
// Haal de gevoeligheidslabel-ID op uit het beleid
System::Guid siteIdGuid = System::Guid::Parse(u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}");
// Haal de Azure AD-site-identificator op uit het beleid
auto label = sensitivityLabels->Add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType::Privileged);
label->get_ContentMarkTypes()->Add(SensitivityLabelContentType::Footer);

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISensitivityLabelCollection](../../isensitivitylabelcollection/)
* Klasse [Presentation](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)