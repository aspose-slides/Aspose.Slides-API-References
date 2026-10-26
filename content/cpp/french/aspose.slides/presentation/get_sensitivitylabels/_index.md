---
title: get_SensitivityLabels()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie la collection d'étiquettes de sensibilité appliquées au document de présentation. Lecture seule ISensitivityLabelCollection.
type: docs
weight: 378
url: /fr/aspose.slides/presentation/get_sensitivitylabels/
---
## Presentation::get_SensitivityLabels() méthode

Renvoie la collection d’étiquettes de sensibilité appliquées au document de présentation. Lecture seule [ISensitivityLabelCollection](../../isensitivitylabelcollection/).

```cpp
System::SharedPtr<ISensitivityLabelCollection> Aspose::Slides::Presentation::get_SensitivityLabels() override
```

## Remarques

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<ISensitivityLabelCollection> sensitivityLabels = pres->get_SensitivityLabels();

// Affiche les étiquettes appliquées
for (auto&& sensitivityLabel : sensitivityLabels)
{
    System::Console::WriteLine(System::String(u"Label Id ") + sensitivityLabel->get_Id() + u" from Azure AD site " + sensitivityLabel->get_SiteId());
}

// Ajoute la nouvelle étiquette
System::String labelIdString = u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}";
// Récupère l'ID de l'étiquette de sensibilité depuis la politique
System::Guid siteIdGuid = System::Guid::Parse(u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}");
// Récupère l'identifiant du site Azure AD depuis la politique
auto label = sensitivityLabels->Add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType::Privileged);
label->get_ContentMarkTypes()->Add(SensitivityLabelContentType::Footer);

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISensitivityLabelCollection](../../isensitivitylabelcollection/)
* Classe [Presentation](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)