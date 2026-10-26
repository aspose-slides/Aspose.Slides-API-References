---
title: get_ReadOnlyRecommended()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient la recommandation de lecture seule. Renvoie un booléen.
type: docs
weight: 79
url: /fr/aspose.slides/protectionmanager/get_readonlyrecommended/
---
## ProtectionManager::get_ReadOnlyRecommended() méthode

Obtient la recommandation de lecture seule. Renvoie **bool**.

```cpp
bool Aspose::Slides::ProtectionManager::get_ReadOnlyRecommended() override
```

## Remarques

Le code d'exemple suivant montre comment définir un PowerPoint [Presentation](../../presentation/) en lecture seule dans C# en utilisant [Aspose.Slides](../../). 
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Classe [ProtectionManager](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)