---
title: Encrypt()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crypte la présentation avec le mot de passe spécifié.
type: docs
weight: 105
url: /fr/aspose.slides/protectionmanager/encrypt/
---
## ProtectionManager::Encrypt(System::String) méthode

Crypte [Presentation](../../presentation/) avec le mot de passe spécifié.

```cpp
void Aspose::Slides::ProtectionManager::Encrypt(System::String encryptionPassword) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| encryptionPassword | [System::String](../../../system/string/) | Le mot de passe. |
## Remarques

Le code d'exemple suivant montre comment crypter un PowerPoint [Presentation](../../presentation/).
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [ProtectionManager](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)