---
title: CheckPassword
second_title: Référence de l'API Aspose.Sildes pour .NET
description: Vérifie si un mot de passe est correct pour une présentation protégée par un mot de passe ouvert.
type: docs
weight: 50
url: /fr/aspose.slides/presentationinfo/checkpassword/
---

## PresentationInfo.CheckPassword method

Vérifie si un mot de passe est correct pour une présentation protégée par un mot de passe ouvert.

```csharp
public bool CheckPassword(string password)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| password | String | Le mot de passe à vérifier. |

### Valeur de retour

Vrai si la présentation est protégée par un mot de passe ouvert et que le mot de passe est correct, et faux sinon.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException |  |
| NotSupportedException |  |

### Remarques

Lorsque le mot de passe est nul ou vide, cette méthode renvoie faux.

### Exemples

```csharp
[C#]
IPresentationInfo info = PresentationFactory.Instance.GetPresentationInfo(presentationFilePath);
bool isPasswordCorrect = info.CheckPassword("my_password");
```

### Voir Aussi

* class [PresentationInfo](../../presentationinfo)
* namespace [Aspose.Slides](../../presentationinfo)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->