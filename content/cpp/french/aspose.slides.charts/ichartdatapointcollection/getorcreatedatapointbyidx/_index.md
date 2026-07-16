---
title: GetOrCreateDataPointByIdx()
second_title: Référence API Aspose.Slides pour C++
description: "Si la collection contient déjà un point de données avec l'index index, alors elle renvoie ce point de données. Si la collection ne contient pas de point de données avec l'index index ==N (lorsque le nombre de points de données dans cette collection est inférieur ou égal à N), alors elle ajoute les points de données manquants et renvoie le dernier (qui possède l'index demandé). Par exemple, les index de la collection sont {0, 1, 2}, et l'index demandé est 5. Alors la méthode ajoute les points de données manquants : {0, 1, 2, 3, 4, 5}. Et renvoie le point de données avec l'index 5."
type: docs
weight: 131
url: /fr/aspose.slides.charts/ichartdatapointcollection/getorcreatedatapointbyidx/
---
## IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) méthode

Si la collection contient déjà un point de données avec l'index *index*, alors elle renvoie ce point de données. Si la collection ne contient pas de point de données avec l'index *index* ==N (lorsque le nombre de points de données dans cette collection est inférieur ou égal à N), alors elle ajoute les points de données manquants et renvoie le dernier (qui possède l'index demandé). Par exemple, les index de la collection sont {0, 1, 2}, et l'index demandé est 5. Alors la méthode ajoute les points de données manquants : {0, 1, 2, 3, 4, 5}. Et renvoie le point de données avec l'index 5.

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **uint32_t** | Index. |

### Valeur de retour

Renvoie le point de données avec l'index demandé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataPoint](../../ichartdatapoint/)
* Class [IChartDataPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)