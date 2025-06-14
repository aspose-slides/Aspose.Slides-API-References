---
title: CopyTo
second_title: Référence API Aspose.Slides pour .NET
description: Copie les éléments de l'ICollection dans un tableau à partir d'un index particulier du tableau.
type: docs
weight: 80
url: /fr/aspose.slides/paragraphcollection/copyto/
---

## Méthode ParagraphCollection.CopyTo

Copie les éléments de l'ICollection dans un tableau, en commençant à un index particulier du tableau.

```csharp
public void CopyTo(IParagraph[] array, int arrayIndex)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| array | IParagraph[] | Le tableau unidimensionnel qui est la destination des éléments copiés depuis l'ICollection. Le tableau doit avoir un index basé sur zéro. |
| arrayIndex | Int32 | L'index basé sur zéro dans *array* à partir duquel la copie commence. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *array* est nul. |
| ArgumentOutOfRangeException | *arrayIndex* est inférieur à 0. |
| ArgumentException | Le nombre d'éléments dans l'ICollection source est supérieur à l'espace disponible de *arrayIndex* jusqu'à la fin du tableau de destination *array*. |

### Voir Aussi

* interface [IParagraph](../../iparagraph)
* class [ParagraphCollection](../../paragraphcollection)
* namespace [Aspose.Slides](../../paragraphcollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->