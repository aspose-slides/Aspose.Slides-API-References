---
title: IChartSeriesGroupCollection
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente la collection de groupes de séries combinables.
type: docs
url: /fr/com.aspose.slides/ichartseriesgroupcollection/
---
**Toutes les interfaces implémentées:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

Représente la collection de groupes de séries combinables.

--------------------

1) Chaque groupe de séries contient des séries avec des types combinables. Les groupes de types de séries combinables sont définis et décrits avec l’énumération CombinableSeriesTypesGroup. De plus, chaque groupe de séries contient des séries qui sont tracées soit sur les axes principaux, soit sur les axes secondaires (pas les deux cas dans un même groupe). Ainsi, le principe du groupement des séries est un regroupement par les types de groupe mentionnés ci-dessus et par le type de tracé principal/secondaire. 2) Un groupe de séries contient certaines propriétés de séries communes à chaque série du groupe (« propriétés du groupe de séries »). Les « propriétés du groupe de séries » dans la classe ChartSeriesGroup sont lecture/écriture. Chacune des « propriétés du groupe de séries » peut avoir une projection en lecture seule dans la classe ChartSeries.

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

**Retour :**
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

**Retour :**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)