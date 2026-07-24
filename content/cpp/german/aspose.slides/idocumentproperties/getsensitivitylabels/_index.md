---
title: GetSensitivityLabels()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft ein Array von Sensitivitätskennzeichnungen aus den benutzerdefinierten Dokumenteigenschaften ab (Microsoft Information Protection SDK Metadata).
type: docs
weight: 872
url: /de/aspose.slides/idocumentproperties/getsensitivitylabels/
---
## IDocumentProperties::GetSensitivityLabels() Methode

Ruft ein Array von Sensitivitätskennzeichnungen aus den benutzerdefinierten Dokumenteigenschaften ab (Microsoft Information Protection SDK Metadata).

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::IDocumentProperties::GetSensitivityLabels()=0
```

## Anmerkungen

Der folgende Code zeigt, wie die Sensitivitätskennzeichnungen-Informationen von den benutzerdefinierten Dokumenteigenschaften in die moderne SensitivityLabels collection verschoben werden können:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// Sensitivitätskennzeichnungen aus den benutzerdefinierten Dokumenteigenschaften abrufen
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // Kennzeichnung zur Sammlung hinzufügen
    // Hier können Sie eine Prüfung der Gültigkeit der Label-Informationen hinzufügen (das Label ist verfügbar, usw.)
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISensitivityLabel](../../isensitivitylabel/)
* Klasse [IDocumentProperties](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)