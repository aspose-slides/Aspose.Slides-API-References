---
title: ILinkEmbedController
second_title: Référence de l'API Aspose.Slides pour .NET
description: Interface de rappel utilisée pour déterminer comment lobjet doit être traité lors de lenregistrement.
type: docs
weight: 3680
url: /fr/net/aspose.slides.export/ilinkembedcontroller/
---
## ILinkEmbedController interface

Interface de rappel utilisée pour déterminer comment l'objet doit être traité lors de l'enregistrement.

```csharp
public interface ILinkEmbedController
```

## Méthodes

| Nom | La description |
| --- | --- |
| [GetObjectStoringLocation](../../aspose.slides.export/ilinkembedcontroller/getobjectstoringlocation)(int, byte[], string, string, string) | Détermine où l'objet doit être stocké. Cette méthode est appelée une fois pour chaque identifiant d'objet. Il n'est pas garanti qu'il n'y aura pas deux objets avec les mêmes données, semanticName et contentType mais avec un identifiant différent. |
| [GetUrl](../../aspose.slides.export/ilinkembedcontroller/geturl)(int, int) | Renvoie une URL vers un objet externe. Cette méthode est toujours appelée si[`GetObjectStoringLocation`](./getobjectstoringlocation) revenuLink et peut être appelé si[`GetObjectStoringLocation`](./getobjectstoringlocation) revenuEmbed mais l'intégration est impossible. Peut être appelé plusieurs fois pour le même identifiant d'objet. |
| [SaveExternal](../../aspose.slides.export/ilinkembedcontroller/saveexternal)(int, byte[]) | Enregistre un objet externe. |

### Voir également

* espace de noms [Aspose.Slides.Export](../../aspose.slides.export)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->