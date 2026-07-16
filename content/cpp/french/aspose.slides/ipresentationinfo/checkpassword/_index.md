---
title: CheckPassword()
second_title: Référence de l'API Aspose.Slides pour C++
description: Vérifie si un mot de passe est correct pour une présentation protégée par un mot de passe ouvert.
type: docs
weight: 53
url: /fr/aspose.slides/ipresentationinfo/checkpassword/
---
## IPresentationInfo::CheckPassword(System::String) méthode

Vérifie si un mot de passe est correct pour une présentation protégée par un mot de passe ouvert.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckPassword(System::String password)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Le mot de passe à vérifier. |

### Valeur de retour

True si la présentation est protégée par un mot de passe ouvert et que le mot de passe est correct, et false sinon.

## Remarques

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```

Lorsque le mot de passe est nul ou vide, cette méthode renvoie false.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [IPresentationInfo](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)