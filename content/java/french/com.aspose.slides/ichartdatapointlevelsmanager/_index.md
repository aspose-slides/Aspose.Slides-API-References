---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides pour Java Référence de l'API
description: Conteneur de niveaux de points de données.
type: docs
url: /fr/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

Conteneur de niveaux de points de données. Appliqué aux séries Treeamp et Sunburst. L'indexation des niveaux de points de données commence à zéro.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Renvoie l'objet IChartDataPointLevel pour le niveau défini. |
| [getCount()](#getCount--) | Renvoie le nombre de niveaux de points de données. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
```

Renvoie l'objet IChartDataPointLevel pour le niveau défini.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| level | int |  |

**Renvoie :**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Renvoie le nombre de niveaux de points de données.

**Renvoie :**
int