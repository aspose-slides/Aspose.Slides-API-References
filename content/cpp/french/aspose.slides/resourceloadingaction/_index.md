---
title: ResourceLoadingAction
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie le mode de chargement des ressources externes.
type: docs
weight: 6761
url: /fr/aspose.slides/resourceloadingaction/
---
## ResourceLoadingAction enum


Spécifie le mode de chargement des ressources externes.

```cpp
enum class ResourceLoadingAction
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Default | 0 | [Aspose.Slides](../) chargera la ressource externe comme d'habitude. |
| Skip | 1 | [Aspose.Slides](../) ignorera le chargement de la ressource externe. Seul le lien sans données sera stocké pour une image. |
| UserProvided | 2 | [Aspose.Slides](../) utilisera le tableau d'octets fourni par l'utilisateur dans [IResourceLoadingArgs::SetData](../iresourceloadingargs/setdata/) comme données d'image. |

## Voir aussi

* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)