---
title: GetSensitivityLabels()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt een array van gevoeligheidslabels op uit de aangepaste documenteigenschappen (Microsoft Information Protection SDK Metadata).
type: docs
weight: 859
url: /nl/aspose.slides/documentproperties/getsensitivitylabels/
---
## DocumentProperties::GetSensitivityLabels() methode

Haalt een array van gevoeligheidslabels op uit de aangepaste documenteigenschappen (Microsoft Information Protection SDK Metadata).

```cpp
System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::DocumentProperties::GetSensitivityLabels() override
```

## Opmerkingen

De volgende code toont hoe de informatie over gevoeligheidslabels te verplaatsen van de aangepaste documenteigenschappen naar de moderne SensitivityLabels-collectie: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// Haal gevoeligheidslabels op uit de aangepaste documenteigenschappen
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // Voeg label toe aan de collectie
    // Hier kunt u een controle toevoegen voor de geldigheid van de labelinformatie (het label is beschikbaar, enz.)
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISensitivityLabel](../../isensitivitylabel/)
* Klasse [DocumentProperties](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)