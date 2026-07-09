---
title: ILegendEntryCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Représente la collection de légendes.
type: docs
url: /fr/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

Représente la collection de légendes.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtient les propriétés de l'entrée de légende correspondante à Chart.ChartData.Series[0].DataPoints[index] dans le cas d'un type de graphique provenant de cette liste : ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie ; ou correspondante à Chart.ChartData.Series[index] pour les autres types de graphiques. |
| [getCount()](#getCount--) | Obtient le nombre d'éléments réellement contenus dans la collection. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```

Obtient les propriétés de l'entrée de légende correspondante à Chart.ChartData.Series[0].DataPoints[index] dans le cas d'un type de graphique provenant de cette liste : ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie ; ou correspondante à Chart.ChartData.Series[index] pour les autres types de graphiques.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie :**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getCount() {#getCount--}
```
public abstract int getCount()
```

Obtient le nombre d'éléments réellement contenus dans la collection. Lecture seule int.

**Renvoie :**
int