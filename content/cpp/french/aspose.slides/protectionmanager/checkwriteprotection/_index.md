---
title: CheckWriteProtection()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine si une présentation est protégée par un mot de passe pour être modifiée.
type: docs
weight: 157
url: /fr/aspose.slides/protectionmanager/checkwriteprotection/
---
## ProtectionManager::CheckWriteProtection(System::String) méthode

Détermine si une présentation est protégée par un mot de passe pour être modifiée.

```cpp
bool Aspose::Slides::ProtectionManager::CheckWriteProtection(System::String password) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Le mot de passe à vérifier. |

### Valeur de retour

True si le mot de passe est valide ; sinon, false.

## Remarques

```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```

1. Vous devez vérifier la propriété [ProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) avant d'appeler cette méthode.
1. Lorsque le mot de passe est nul ou vide, cette méthode renvoie false.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [ProtectionManager](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)