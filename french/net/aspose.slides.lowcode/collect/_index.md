---
title: Collect
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente un ensemble de méthodes destinées à collecter des objets modèles de différents types à partirPresentation../aspose.slides/presentation .
type: docs
weight: 7190
url: /fr/net/aspose.slides.lowcode/collect/
---
## Collect class

Représente un ensemble de méthodes destinées à collecter des objets modèles de différents types à partir[`Presentation`](../../aspose.slides/presentation) .

```csharp
public static class Collect
```

## Méthodes

| Nom | La description |
| --- | --- |
| static [Shapes](../../aspose.slides.lowcode/collect/shapes)(Presentation) | Collecte toutes les instances de[`Shape`](../../aspose.slides/shape) dans le[`Presentation`](../../aspose.slides/presentation) . |

### Exemples

```csharp
using (Presentation pres = new Presentation("pres.pptx"))
{
    foreach (Shape shape in Collect.Shapes(pres))
    {
        // ... modifier la mise en forme de la forme ou d'autres propriétés
    }
}    
```

### Voir également

* espace de noms [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->