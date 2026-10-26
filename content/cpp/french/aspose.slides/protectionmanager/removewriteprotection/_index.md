---
title: RemoveWriteProtection()
second_title: Référence de l'API Aspose.Slides pour C++
description: Supprime la protection en écriture de cette présentation.
type: docs
weight: 144
url: /fr/aspose.slides/protectionmanager/removewriteprotection/
---
## ProtectionManager::RemoveWriteProtection() méthode


Supprime la protection en écriture de cette présentation.

```cpp
void Aspose::Slides::ProtectionManager::RemoveWriteProtection() override
```

## Remarques


Ce code d'exemple montre comment supprimer la protection en écriture d'un PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"write-protection-removed.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Classe [ProtectionManager](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)