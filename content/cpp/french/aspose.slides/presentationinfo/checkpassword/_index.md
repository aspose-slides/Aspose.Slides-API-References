---
title: CheckPassword()
second_title: Référence API Aspose.Slides pour C++
description: Vérifie si un mot de passe est correct pour une présentation protégée par un mot de passe d'ouverture.
type: docs
weight: 53
url: /fr/aspose.slides/presentationinfo/checkpassword/
---
## PresentationInfo::CheckPassword(System::String) méthode

Vérifie si un password est correct pour une présentation protégée par un mot de passe d'ouverture.

```cpp
bool Aspose::Slides::PresentationInfo::CheckPassword(System::String password) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Le password à vérifier. |

### Valeur de retour

True si la présentation est protégée par un mot de passe d'ouverture et que le password est correct, sinon false.

## Remarques

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```

Lorsque le password est null ou vide, cette méthode renvoie false.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [PresentationInfo](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)