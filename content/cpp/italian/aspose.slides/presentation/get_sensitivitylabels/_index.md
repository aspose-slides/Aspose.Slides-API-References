---
title: get_SensitivityLabels()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce la collezione di etichette di sensibilità applicate al documento della presentazione. Sola lettura ISensitivityLabelCollection.
type: docs
weight: 378
url: /it/aspose.slides/presentation/get_sensitivitylabels/
---
## Presentation::get_SensitivityLabels() metodo


Restituisce la collezione di etichette di sensibilità applicate al documento della presentazione. Sola lettura [ISensitivityLabelCollection](../../isensitivitylabelcollection/).

```cpp
System::SharedPtr<ISensitivityLabelCollection> Aspose::Slides::Presentation::get_SensitivityLabels() override
```

## Note



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<ISensitivityLabelCollection> sensitivityLabels = pres->get_SensitivityLabels();

// Stampa le etichette applicate
for (auto&& sensitivityLabel : sensitivityLabels)
{
    System::Console::WriteLine(System::String(u"Label Id ") + sensitivityLabel->get_Id() + u" from Azure AD site " + sensitivityLabel->get_SiteId());
}

// Aggiungi la nuova etichetta
System::String labelIdString = u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}";
// Ottieni l'Id dell'etichetta di sensibilità dalla policy
System::Guid siteIdGuid = System::Guid::Parse(u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}");
// Ottieni l'identificatore del sito Azure AD dalla policy
auto label = sensitivityLabels->Add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType::Privileged);
label->get_ContentMarkTypes()->Add(SensitivityLabelContentType::Footer);

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISensitivityLabelCollection](../../isensitivitylabelcollection/)
* Classe [Presentation](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)