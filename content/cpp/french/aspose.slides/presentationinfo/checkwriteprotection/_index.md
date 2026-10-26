---
title: CheckWriteProtection()
second_title: Référence API Aspose.Slides pour C++
description: Vérifie si le mot de passe de modification est correct pour une présentation protégée en écriture.
type: docs
weight: 66
url: /fr/aspose.slides/presentationinfo/checkwriteprotection/
---
## PresentationInfo::CheckWriteProtection(System::String) méthode


Vérifie si le mot de passe de modification est correct pour une présentation protégée en écriture.

```cpp
bool Aspose::Slides::PresentationInfo::CheckWriteProtection(System::String password) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Le mot de passe à vérifier. |

### Valeur de retour

Vrai si la présentation est protégée en écriture et que le mot de passe est correct. Faux sinon.

## Remarques



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```



1. Vous devez vérifier la propriété [PresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) avant d'appeler cette méthode.
1. Lorsque le mot de passe est nul ou vide, cette méthode renvoie faux.



## Voir aussi

* Classe [String](../../../system/string/)
* Classe [PresentationInfo](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)