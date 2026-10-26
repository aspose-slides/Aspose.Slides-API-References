---
title: CheckWriteProtection()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine si une présentation est protégée par mot de passe pour la modifier.
type: docs
weight: 157
url: /fr/aspose.slides/iprotectionmanager/checkwriteprotection/
---
## IProtectionManager::CheckWriteProtection(System::String) méthode

Détermine si une présentation est protégée par mot de passe pour la modifier.

```cpp
virtual bool Aspose::Slides::IProtectionManager::CheckWriteProtection(System::String password)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Le mot de passe à vérifier. |

### Valeur de retour

Vrai si le mot de passe est valide ; sinon, faux.

## Remarques

```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```

1. Vous devez vérifier la propriété [IProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) avant d’appeler cette méthode.
1. Lorsque le mot de passe est nul ou vide, cette méthode renvoie faux.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [IProtectionManager](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)