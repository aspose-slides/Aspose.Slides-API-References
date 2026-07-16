---
title: Remove()
second_title: Référence API Aspose.Slides for C++
description: Supprime l'élément de la collection.
type: docs
weight: 79
url: /fr/aspose.slides.charts/piesplitcustompointcollection/remove/
---
## PieSplitCustomPointCollection::Remove(const System::SharedPtr\<IChartDataPoint\>\&) méthode

Supprime l'élément de la collection.

```cpp
bool Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(const System::SharedPtr<IChartDataPoint> &dataPoint) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| dataPoint | const [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataPoint](../../ichartdatapoint/)\>\& | Point de données à supprimer. |

### Valeur de retour

true si l'élément est supprimé avec succès ; sinon, false. Cette méthode renvoie également false si l'élément n'a pas été trouvé dans le [System::Collections::Generic::List](../../../system.collections.generic/list/){T}.

## PieSplitCustomPointCollection::Remove(int32_t) méthode

Supprime l'élément de la collection à l'aide de son indice dans la collection de points de la série parente.

```cpp
void Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(int32_t dataPointIndex) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| dataPointIndex | **int32_t** | Indice du point de données dans la collection de points de la série parente. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataPoint](../../ichartdatapoint/)
* Class [PieSplitCustomPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)