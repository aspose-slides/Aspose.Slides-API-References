---
title: get_ReadOnlyRecommended()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient la recommandation en lecture seule. Lecture bool.
type: docs
weight: 79
url: /fr/aspose.slides/iprotectionmanager/get_readonlyrecommended/
---
## IProtectionManager::get_ReadOnlyRecommended() méthode


Obtient la recommandation en lecture seule. Lecture **bool**.

```cpp
virtual bool Aspose::Slides::IProtectionManager::get_ReadOnlyRecommended()=0
```

## Remarques



```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Classe [IProtectionManager](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)