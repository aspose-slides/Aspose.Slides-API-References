---
title: GetSensitivityLabels()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar en array av känslighetsetiketter från de anpassade dokumentegenskaperna (Microsoft Information Protection SDK Metadata).
type: docs
weight: 872
url: /sv/aspose.slides/idocumentproperties/getsensitivitylabels/
---
## IDocumentProperties::GetSensitivityLabels() metod


Hämtar en array av känslighetsetiketter från de anpassade dokumentegenskaperna (Microsoft Information Protection SDK Metadata).

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::IDocumentProperties::GetSensitivityLabels()=0
```
## Anmärkningar


Följande kod visar hur man flyttar känslighetsetikettinformation från de anpassade dokumentegenskaperna till den moderna SensitivityLabels-samlingen: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// Hämta känslighetsetiketter från de anpassade dokumentegenskaperna
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // Lägg till etiketten i samlingen
    // Här kan du lägga till en kontroll för att validera etikettinformationen (etiketten är tillgänglig, osv)
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISensitivityLabel](../../isensitivitylabel/)
* Klass [IDocumentProperties](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)