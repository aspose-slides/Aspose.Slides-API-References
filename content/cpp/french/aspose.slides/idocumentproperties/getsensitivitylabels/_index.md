---
title: GetSensitivityLabels()
second_title: Référence API Aspose.Slides pour C++
description: Récupère un tableau d'étiquettes de sensibilité à partir des propriétés personnalisées du document (Microsoft Information Protection SDK Metadata).
type: docs
weight: 872
url: /fr/aspose.slides/idocumentproperties/getsensitivitylabels/
---
## IDocumentProperties::GetSensitivityLabels() méthode

Récupère un tableau d'étiquettes de sensibilité à partir des propriétés personnalisées du document (Microsoft Information Protection SDK Metadata).

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::IDocumentProperties::GetSensitivityLabels()=0
```

## Remarques

Le code suivant montre comment déplacer les informations d'étiquettes de sensibilité des propriétés personnalisées du document vers la collection SensitivityLabels moderne :

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// Récupérer les étiquettes de sensibilité à partir des propriétés personnalisées du document
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // Ajouter l'étiquette à la collection
    // Vous pouvez ajouter ici une vérification de la validité des informations de l'étiquette (l'étiquette est disponible, etc)
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISensitivityLabel](../../isensitivitylabel/)
* Classe [IDocumentProperties](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)