---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Conteneur de niveaux de points de données. Appliqué aux séries Treeamp et Sunburst. L'indexation des niveaux de points de données commence à zéro.
type: docs
url: /fr/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

Conteneur de niveaux de points de données. Appliqué aux séries Treeamp et Sunburst. L'indexation des niveaux de points de données commence à zéro.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Retourne l'objet IChartDataPointLevel pour le niveau défini. |
| [getCount()](#getCount--) | Retourne le nombre de niveaux de points de données. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
```


Retourne l'objet IChartDataPointLevel pour le niveau défini.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| level | int |  |

**Retour:**  
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Retourne le nombre de niveaux de points de données.

**Retour:**  
int