---
title: CheckPassword
second_title: Référence de l'API Aspose.Slides pour .NET
description: Vérifie si un mot de passe est correct pour une présentation protégée par un mot de passe ouvert.
type: docs
weight: 50
url: /fr/net/aspose.slides/ipresentationinfo/checkpassword/
---
## IPresentationInfo.CheckPassword method

Vérifie si un mot de passe est correct pour une présentation protégée par un mot de passe ouvert.

```csharp
public bool CheckPassword(string password)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| password | String | Le mot de passe à vérifier. |

### Return_Value

Vrai si la présentation est protégée par un mot de passe ouvert et que le mot de passe est correct et faux sinon.

### Remarques

Lorsque le mot de passe est nul ou vide, cette méthode renvoie false.

### Exemples

```csharp
[C#]
IPresentationInfo info = PresentationFactory.Instance.GetPresentationInfo("pres.pptx");
bool isPasswordCorrect = info.CheckPassword("my_password");
```

### Voir également

* interface [IPresentationInfo](../../ipresentationinfo)
* espace de noms [Aspose.Slides](../../ipresentationinfo)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->