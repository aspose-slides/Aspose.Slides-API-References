---
title: GetSensitivityLabels()
second_title: Aspose.Slides per C++ Riferimento API
description: Restituisce un array di etichette di sensibilità dalle proprietà personalizzate del documento (Microsoft Information Protection SDK Metadata).
type: docs
weight: 872
url: /it/aspose.slides/idocumentproperties/getsensitivitylabels/
---
## IDocumentProperties::GetSensitivityLabels() metodo

Restituisce un array di etichette di sensibilità dalle proprietà personalizzate del documento (Microsoft Information Protection SDK Metadata).

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::IDocumentProperties::GetSensitivityLabels()=0
```

## Note

Il codice seguente mostra come trasferire le informazioni delle etichette di sensibilità dalle proprietà personalizzate del documento alla moderna collezione SensitivityLabels: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// Ottieni le etichette di sensibilità dalle proprietà personalizzate del documento
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // Aggiungi l'etichetta alla collezione
    // Qui puoi aggiungere un controllo sulla validità delle informazioni dell'etichetta (l'etichetta è disponibile, ecc)
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISensitivityLabel](../../isensitivitylabel/)
* Classe [IDocumentProperties](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)