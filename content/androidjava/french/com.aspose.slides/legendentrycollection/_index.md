---
title: LegendEntryCollection
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente la collection de légendes.
type: docs
url: /fr/com.aspose.slides/legendentrycollection/
---
**Héritage:** 
java.lang.Object

**Toutes les interfaces implémentées:** 
[com.aspose.slides.ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)
```
public class LegendEntryCollection implements ILegendEntryCollection
```

Représente la collection de légendes.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtient les propriétés de l'entrée de légende correspondant à Chart.ChartData.Series[0].DataPoints[index] dans le cas d'un type de graphique de cette liste : ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie ; ou correspondant à Chart.ChartData.Series[index] pour les autres types de graphiques. |
| [getCount()](#getCount--) | Obtient le nombre d'entrées de légende. |

### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```

Obtient les propriétés de l'entrée de légende correspondant à Chart.ChartData.Series[0].DataPoints[index] dans le cas d'un type de graphique de cette liste : ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie ; ou correspondant à Chart.ChartData.Series[index] pour les autres types de graphiques.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public final int getCount()
```

Obtient le nombre d'entrées de légende. Lecture seule int.

**Renvoie:**
int