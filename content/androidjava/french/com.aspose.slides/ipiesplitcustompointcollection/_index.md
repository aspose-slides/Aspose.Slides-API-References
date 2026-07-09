---
title: IPieSplitCustomPointCollection
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente une collection de points qui doivent être dessinés dans la deuxième part ou barre d'un graphique en anneau sur un graphique barre-en-anneau ou anneau-sur-anneau avec une division personnalisée.
type: docs
url: /fr/com.aspose.slides/ipiesplitcustompointcollection/
---
**Toutes les interfaces implémentées :**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

Représente une collection de points qui doivent être dessinés dans la deuxième part ou barre d’un graphique en anneau sur un graphique barre-en-anneau ou anneau-sur-anneau avec une division personnalisée.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Renvoie le point de données du graphique par indice. |
| [add(int dataPointIndex)](#add-int-) | Ajoute le point de données par son indice dans la collection de points de la série parent. |
| [remove(int dataPointIndex)](#remove-int-) | Supprime l’élément de la collection par son indice dans la collection de points de la série parent. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

Renvoie le point de données du graphique par indice.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice du point de données. |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Point de données du graphique.
### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```

Ajoute le point de données par son indice dans la collection de points de la série parent.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| dataPointIndex | int | Indice du point de données dans la collection de points de la série parent. |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```

Supprime l’élément de la collection par son indice dans la collection de points de la série parent.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| dataPointIndex | int | Indice du point de données dans la collection de points de la série parent.. |