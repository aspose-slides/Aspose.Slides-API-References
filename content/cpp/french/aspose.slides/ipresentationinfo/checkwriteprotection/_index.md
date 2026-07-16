---
title: CheckWriteProtection()
second_title: Référence de l'API Aspose.Slides pour C++
description: Vérifie si le mot de passe de modification est correct pour une présentation protégée en écriture.
type: docs
weight: 66
url: /fr/aspose.slides/ipresentationinfo/checkwriteprotection/
---
## IPresentationInfo::CheckWriteProtection(System::String) méthode

Vérifie si le mot de passe de modification est correct pour une présentation protégée en écriture.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckWriteProtection(System::String password)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Le mot de passe à vérifier. |

### Valeur de retour

True if the presentation is write protected and the password is correct. False otherwise.

## Remarques

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```

1. Vous devez vérifier la propriété [IPresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) avant d’appeler cette méthode.
1. Lorsque le mot de passe est null ou vide, cette méthode renvoie false.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [IPresentationInfo](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)