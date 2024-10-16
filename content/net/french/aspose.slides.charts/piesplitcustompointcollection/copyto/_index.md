---
title: CopyTo
second_title: Référence de l'API Aspose.Slides pour .NET
description: Copie les éléments duICollection à unArray  à partir dun certainArray index.
type: docs
weight: 90
url: /fr/aspose.slides.charts/piesplitcustompointcollection/copyto/
---
## PieSplitCustomPointCollection.CopyTo method

Copie les éléments duICollection à unArray , à partir d'un certainArray index.

```csharp
public void CopyTo(IChartDataPoint[] array, int arrayIndex)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| array | IChartDataPoint[] | Le unidimensionnelArray qui est la destination des éléments copiés à partir deICollection . LaArray doit avoir une indexation de base zéro. |
| arrayIndex | Int32 | L'indice de base zéro dans*array* à laquelle la copie commence. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *array* est nul. |
| ArgumentOutOfRangeException | *arrayIndex* est inférieur à 0. |
| ArgumentException | Le nombre d'éléments dans la sourceICollection est supérieur à l'espace disponible de*arrayIndex* jusqu'au bout de la destination*array*. |

### Voir également

* interface [IChartDataPoint](../../ichartdatapoint)
* class [PieSplitCustomPointCollection](../../piesplitcustompointcollection)
* espace de noms [Aspose.Slides.Charts](../../piesplitcustompointcollection)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
