---
title: ChartDataPointLevelsManager
second_title: Référence API Aspose.Slides pour Java
description: Conteneur des niveaux de points de données.
type: docs
url: /fr/com.aspose.slides/chartdatapointlevelsmanager/
---
**Héritage:**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées:**
[com.aspose.slides.IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
```
public class ChartDataPointLevelsManager extends DomObject<ChartDataPoint> implements IChartDataPointLevelsManager
```

Conteneur des niveaux de points de données. Appliqué aux séries Treeamp et Sunburst. L'indexation des niveaux de points de données commence à zéro.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Renvoie l'objet IChartDataPointLevel pour le niveau défini. |
| [getCount()](#getCount--) | Renvoie le nombre de niveaux de points de données. |
### get_Item(int level) {#get-Item-int-}
```
public final IChartDataPointLevel get_Item(int level)
```


Renvoie l'objet IChartDataPointLevel pour le niveau défini.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| level | int |  |

**Renvoie:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public final int getCount()
```


Renvoie le nombre de niveaux de points de données.

**Renvoie:**
int