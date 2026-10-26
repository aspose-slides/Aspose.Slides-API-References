---
title: SetWriteProtection()
second_title: Aspose.Slides pour la référence API C++
description: Définit la protection en écriture pour cette présentation avec le mot de passe spécifié.
type: docs
weight: 131
url: /fr/aspose.slides/protectionmanager/setwriteprotection/
---
## ProtectionManager::SetWriteProtection(System::String) méthode


Définissez la protection en écriture pour cette présentation avec le mot de passe spécifié.

```cpp
void Aspose::Slides::ProtectionManager::SetWriteProtection(System::String password) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Le mot de passe. |
## Remarques



Le code d'exemple suivant montre comment définir une protection en écriture pour une présentation. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [ProtectionManager](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)