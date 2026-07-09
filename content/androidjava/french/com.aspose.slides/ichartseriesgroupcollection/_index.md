---
title: IChartSeriesGroupCollection
second_title: Référence de l'API Java pour Aspose.Slides pour Android
description: Représente la collection de groupes de séries combinables.
type: docs
url: /fr/com.aspose.slides/ichartseriesgroupcollection/
---
**Toutes les interfaces implémentées :**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

Représente la collection de groupes de séries combinables.

--------------------

1) Chaque groupe de séries contient des séries de types combinables. Les groupes de types de séries combinables sont définis et décrits avec l’énumération CombinableSeriesTypesGroup. De plus, chaque groupe de séries contient des séries qui sont tracées soit sur les axes primaires, soit sur les axes secondaires (pas les deux cas dans un même groupe). Ainsi, le principe de regroupement des séries est un regroupement par les groupes de types mentionnés ci-dessus et par le type de traçage primaire/secondaire. 2) Un groupe de séries contient certaines propriétés de séries communes à chaque série du groupe (« series group properties »). Les « series group properties » dans la classe ChartSeriesGroup sont en lecture/écriture. Chacune des « series group properties » peut avoir une projection en lecture seule dans la classe ChartSeries.

## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | Obtient le groupe de séries par série. |
| [get_Item(int index)](#get-Item-int-) | Obtient le groupe de séries par indice. |
### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```


Obtient le groupe de séries par série.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

**Renvoie :**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```


Obtient le groupe de séries par indice.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie :**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)