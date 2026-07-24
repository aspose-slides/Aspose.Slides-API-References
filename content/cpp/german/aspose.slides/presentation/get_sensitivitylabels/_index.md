---
title: get_SensitivityLabels()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Sammlung von Sensitivitätskennzeichnungen zurück, die auf das Präsentationsdokument angewendet wurden. Nur lesbar ISensitivityLabelCollection.
type: docs
weight: 378
url: /de/aspose.slides/presentation/get_sensitivitylabels/
---
## Presentation::get_SensitivityLabels() Methode

Gibt die Sammlung von Sensitivitätskennzeichnungen zurück, die auf das Präsentationsdokument angewendet wurden. Nur lesbar [ISensitivityLabelCollection](../../isensitivitylabelcollection/).

```cpp
System::SharedPtr<ISensitivityLabelCollection> Aspose::Slides::Presentation::get_SensitivityLabels() override
```

## Hinweise



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<ISensitivityLabelCollection> sensitivityLabels = pres->get_SensitivityLabels();

// Die angewendeten Kennzeichnungen ausgeben
for (auto&& sensitivityLabel : sensitivityLabels)
{
    System::Console::WriteLine(System::String(u"Label Id ") + sensitivityLabel->get_Id() + u" from Azure AD site " + sensitivityLabel->get_SiteId());
}

// Die neue Kennzeichnung hinzufügen
System::String labelIdString = u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}";
// Hole die Sensitivitätskennzeichnungs-ID aus der Richtlinie
System::Guid siteIdGuid = System::Guid::Parse(u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}");
// Hole den Azure AD Site-Identifikator aus der Richtlinie
auto label = sensitivityLabels->Add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType::Privileged);
label->get_ContentMarkTypes()->Add(SensitivityLabelContentType::Footer);

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISensitivityLabelCollection](../../isensitivitylabelcollection/)
* Klasse [Presentation](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)