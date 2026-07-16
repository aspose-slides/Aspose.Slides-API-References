---
title: set_ReadOnlyRecommended()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit la recommandation en lecture seule. Écrit bool.
type: docs
weight: 92
url: /fr/aspose.slides/iprotectionmanager/set_readonlyrecommended/
---
## IProtectionManager::set_ReadOnlyRecommended(bool) méthode


Définit la recommandation en lecture seule. Écrit **bool**.

```cpp
virtual void Aspose::Slides::IProtectionManager::set_ReadOnlyRecommended(bool value)=0
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