---
title: GetSensitivityLabels()
second_title: Aspose.Slides per C++ Riferimento API
description: Ottiene un array di etichette di sensibilità dalle proprietà personalizzate del documento (Microsoft Information Protection SDK Metadata).
type: docs
weight: 859
url: /it/aspose.slides/documentproperties/getsensitivitylabels/
---
## DocumentProperties::GetSensitivityLabels() metodo

Ottiene un array di etichette di sensibilità dalle proprietà personalizzate del documento (Microsoft Information Protection SDK Metadata).

```cpp
System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::DocumentProperties::GetSensitivityLabels() override
```

## Osservazioni

Il codice seguente mostra come spostare le informazioni delle etichette di sensibilità dalle proprietà personalizzate del documento alla moderna collezione SensitivityLabels:

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// Ottieni le etichette di sensibilità dalle proprietà personalizzate del documento
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // Aggiungi l'etichetta alla collezione
    // Qui puoi aggiungere un controllo per la validità delle informazioni dell'etichetta (l'etichetta è disponibile, ecc.)
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Definizione di tipo [ArrayPtr](../../../system/arrayptr/)
* Definizione di tipo [SharedPtr](../../../system/sharedptr/)
* Classe [ISensitivityLabel](../../isensitivitylabel/)
* Classe [DocumentProperties](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)