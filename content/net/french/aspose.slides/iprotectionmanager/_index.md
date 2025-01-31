---
title: IProtectionManager
second_title: Référence de l'API Aspose.Slides pour .NET
description: Présentation gestion de la protection par mot de passe.
type: docs
weight: 6290
url: /fr/aspose.slides/iprotectionmanager/
---
## IProtectionManager interface

Présentation gestion de la protection par mot de passe.

```csharp
public interface IProtectionManager
```

## Propriétés

| Nom | La description |
| --- | --- |
| [EncryptDocumentProperties](../../aspose.slides/iprotectionmanager/encryptdocumentproperties) { get; set; } | Cette propriété a du sens si la présentation est protégée par un mot de passe. Si vrai, les propriétés du document sont chiffrées dans le fichier de présentation. Si faux, les propriétés du document sont publiques tandis que la présentation est chiffrée. Lecture/écritureBoolean . |
| [EncryptionPassword](../../aspose.slides/iprotectionmanager/encryptionpassword) { get; } | Renvoie le mot de passe de chiffrement. Lecture seuleString . |
| [IsEncrypted](../../aspose.slides/iprotectionmanager/isencrypted) { get; } | Obtient une valeur indiquant si cette instance est chiffrée. Lecture seuleBoolean . |
| [IsOnlyDocumentPropertiesLoaded](../../aspose.slides/iprotectionmanager/isonlydocumentpropertiesloaded) { get; } | Cette propriété a du sens si le fichier de présentation est protégé par un mot de passe et que les propriétés du document de ce fichier sont publiques. La valeur true signifie que seules les propriétés du document sont chargées à partir d'un fichier de présentation chiffré sans utiliser de mot de passe. La valeur false signifie que toute la présentation cryptée est chargée avec l'utilisation du bon mot de passe, non seulement les propriétés du document sont chargées. Si la présentation n'est pas cryptée, la valeur de la propriété est toujours fausse. Si les propriétés du document d'un fichier crypté ne sont pas publiques, la valeur de la propriété est toujours false. Si PresentationEx.EncryptDocumentProperties est vrai, la valeur de la propriété IsOnlyDocumentPropertiesLoaded est toujours fausse. Lecture seuleBoolean . |
| [IsWriteProtected](../../aspose.slides/iprotectionmanager/iswriteprotected) { get; } | Obtient une valeur indiquant si cette présentation est protégée en écriture. Lecture seuleBoolean . |
| [ReadOnlyRecommended](../../aspose.slides/iprotectionmanager/readonlyrecommended) { get; set; } | Obtient ou définit une recommandation en lecture seule. Lecture/écritureBoolean . |

## Méthodes

| Nom | La description |
| --- | --- |
| [CheckWriteProtection](../../aspose.slides/iprotectionmanager/checkwriteprotection)(string) | Détermine si une présentation est un mot de passe protégé pour modifier. |
| [Encrypt](../../aspose.slides/iprotectionmanager/encrypt)(string) | Crypte la présentation avec le mot de passe spécifié. |
| [RemoveEncryption](../../aspose.slides/iprotectionmanager/removeencryption)() | Supprime le cryptage. |
| [RemoveWriteProtection](../../aspose.slides/iprotectionmanager/removewriteprotection)() | Supprime la protection en écriture pour cette présentation. |
| [SetWriteProtection](../../aspose.slides/iprotectionmanager/setwriteprotection)(string) | Définir la protection en écriture pour cette présentation avec le mot de passe spécifié. |

### Voir également

* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
