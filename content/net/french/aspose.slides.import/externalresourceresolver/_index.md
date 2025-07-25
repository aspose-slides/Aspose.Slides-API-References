---
title: ExternalResourceResolver
second_title: Aspose.Sildes pour .NET Référence API
description: Classe de rappel utilisée pour résoudre les ressources externes lors de l'importation de documents Html Svg. Utiliser ce résolveur pourrait créer une vulnérabilité lorsque le fichier HTML ou SVG fourni par le client oblige le logiciel serveur à obtenir un fichier local ou réseau. Utilisez avec précaution. Il est recommandé de ne pas spécifier ExternalResourceResolver du tout seuls les objets intégrés seront lus ou de créer une sous-classe qui vérifie si l'URI spécifié est valide.
type: docs
weight: 7250
url: /fr/aspose.slides.import/externalresourceresolver/
---

## Classe ExternalResourceResolver

Classe de rappel utilisée pour résoudre les ressources externes lors de l'importation de documents Html, Svg. Utiliser ce résolveur pourrait créer une vulnérabilité lorsque le fichier HTML ou SVG fourni par le client oblige le logiciel serveur à obtenir un fichier local ou réseau. Utilisez avec précaution. Il est recommandé de ne pas spécifier ExternalResourceResolver du tout (seuls les objets intégrés seront lus) ou de créer une sous-classe qui vérifie si l'URI spécifié est valide.

```csharp
public class ExternalResourceResolver : IExternalResourceResolver
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ExternalResourceResolver](externalresourceresolver)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [GetEntity](../../aspose.slides.import/externalresourceresolver/getentity)(string) | Mappe une URI à un objet contenant la ressource réelle. |
| virtual [ResolveUri](../../aspose.slides.import/externalresourceresolver/resolveuri)(string, string) | Résout l'URI absolu à partir des URI de base et relatives. |

### Voir Aussi

* interface [IExternalResourceResolver](../iexternalresourceresolver)
* namespace [Aspose.Slides.Import](../../aspose.slides.import)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->