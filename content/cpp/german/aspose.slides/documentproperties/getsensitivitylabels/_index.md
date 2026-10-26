---
title: GetSensitivityLabels()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft ein Array von Sensitivitätskennzeichnungen aus den benutzerdefinierten Dokumenteigenschaften ab (Microsoft Information Protection SDK Metadata).
type: docs
weight: 859
url: /de/aspose.slides/documentproperties/getsensitivitylabels/
---
## DocumentProperties::GetSensitivityLabels() Methode

Ruft ein Array von Sensitivitätskennzeichnungen aus den benutzerdefinierten Dokumenteigenschaften ab (Microsoft Information Protection SDK Metadata).

```cpp
System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::DocumentProperties::GetSensitivityLabels() override
```

## Anmerkungen

Der folgende Code zeigt, wie die Sensitivitätskennzeichnungsinformationen von den benutzerdefinierten Dokumenteigenschaften in die moderne SensitivityLabels-Sammlung verschoben werden können: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// Lese Sensitivitätskennzeichnungen aus den benutzerdefinierten Dokumenteigenschaften
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // Füge Kennzeichnung zur Sammlung hinzu
    // Hier können Sie eine Prüfung der Gültigkeit der Kennzeichnungsinformationen hinzufügen (die Kennzeichnung ist vorhanden, usw.)
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISensitivityLabel](../../isensitivitylabel/)
* Klasse [DocumentProperties](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)