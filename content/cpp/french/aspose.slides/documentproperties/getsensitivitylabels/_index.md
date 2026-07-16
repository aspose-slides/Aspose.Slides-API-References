---
title: GetSensitivityLabels()
second_title: Référence API Aspose.Slides pour C++
description: Obtient un tableau d'étiquettes de sensibilité à partir des propriétés de document personnalisées (Microsoft Information Protection SDK Metadata).
type: docs
weight: 859
url: /fr/aspose.slides/documentproperties/getsensitivitylabels/
---
## DocumentProperties::GetSensitivityLabels() méthode


Obtient un tableau d'étiquettes de sensibilité à partir des propriétés de document personnalisées (Microsoft Information Protection SDK Metadata).

```cpp
System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::DocumentProperties::GetSensitivityLabels() override
```

## Remarques


Le code suivant montre comment déplacer les informations d'étiquettes de sensibilité des propriétés de document personnalisées vers la collection SensitivityLabels moderne :
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// Obtenir les étiquettes de sensibilité à partir des propriétés de document personnalisées
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // Ajouter l'étiquette à la collection
    // Ici vous pouvez ajouter une vérification de la validité des informations de l'étiquette (l'étiquette est disponible, etc.)
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISensitivityLabel](../../isensitivitylabel/)
* Classe [DocumentProperties](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)