---
title: get_SensitivityLabels()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Sammlung von Sensitivitätskennzeichnungen zurück, die auf das Präsentationsdokument angewendet wurden. Nur lesbar ISensitivityLabelCollection.
type: docs
weight: 391
url: /de/aspose.slides/ipresentation/get_sensitivitylabels/
---
## IPresentation::get_SensitivityLabels() Methode

Gibt die Sammlung von Sensitivitätskennzeichnungen zurück, die auf das Präsentationsdokument angewendet wurden. Nur lesbar [ISensitivityLabelCollection](../../isensitivitylabelcollection/).

```cpp
virtual System::SharedPtr<ISensitivityLabelCollection> Aspose::Slides::IPresentation::get_SensitivityLabels()=0
```

## Bemerkungen



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<ISensitivityLabelCollection> sensitivityLabels = pres->get_SensitivityLabels();

// Druckt die angewendeten Beschriftungen
for (auto&& sensitivityLabel : sensitivityLabels)
{
    System::Console::WriteLine(System::String(u"Label Id ") + sensitivityLabel->get_Id() + u" from Azure AD site " + sensitivityLabel->get_SiteId());
}

// Neue Beschriftung hinzufügen
System::String labelIdString = u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}";
// ID des Sensitivitätskennzeichens aus der Richtlinie abrufen
System::Guid siteIdGuid = System::Guid::Parse(u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}");
// Azure AD Site-Identifier aus der Richtlinie abrufen
auto label = sensitivityLabels->Add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType::Privileged);
label->get_ContentMarkTypes()->Add(SensitivityLabelContentType::Footer);

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISensitivityLabelCollection](../../isensitivitylabelcollection/)
* Klasse [IPresentation](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)