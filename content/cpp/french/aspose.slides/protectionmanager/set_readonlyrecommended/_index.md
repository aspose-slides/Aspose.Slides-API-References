---
title: set_ReadOnlyRecommended()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit la recommandation de lecture seule. Écrire bool.
type: docs
weight: 92
url: /fr/aspose.slides/protectionmanager/set_readonlyrecommended/
---
## ProtectionManager::set_ReadOnlyRecommended(bool) méthode

Définit la recommandation de lecture seule. Écrire **bool**.

```cpp
void Aspose::Slides::ProtectionManager::set_ReadOnlyRecommended(bool value) override
```

## Remarques

Le code d'exemple suivant montre comment définir un PowerPoint [Presentation](../../presentation/) en lecture seule en C# en utilisant [Aspose.Slides](../../).
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Classe [ProtectionManager](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)