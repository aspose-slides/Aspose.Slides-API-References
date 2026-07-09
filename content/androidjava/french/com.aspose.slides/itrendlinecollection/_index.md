---
title: ITrendlineCollection
second_title: Référence de l'API Java pour Aspose.Slides sur Android
description: Représente une collection de TrendlineEx
type: docs
url: /fr/com.aspose.slides/itrendlinecollection/
---
**Toutes les interfaces implémentées :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ITrendlineCollection extends System.Collections.Generic.IGenericEnumerable<ITrendline>
```

Représente une collection de TrendlineEx
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [getCount()](#getCount--) | Obtient le nombre d'éléments réellement contenus dans la collection. |
| [add(int trendlineType)](#add-int-) | Ajoute la nouvelle Trendline à la fin d'une collection et la renvoie. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Supprime la valeur spécifiée. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```

Obtient l'élément à l'index spécifié. Lecture seule [ITrendline](../../com.aspose.slides/itrendline).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie :**
[ITrendline](../../com.aspose.slides/itrendline)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Obtient le nombre d'éléments réellement contenus dans la collection. Lecture seule int.

**Renvoie :**
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```

Ajoute la nouvelle Trendline à la fin d'une collection et la renvoie.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| trendlineType | int | Type de Trendline [TrendlineType](../../com.aspose.slides/trendlinetype) |

**Renvoie :**
[ITrendline](../../com.aspose.slides/itrendline) - Nouvelle Trendline [ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public abstract void remove(ITrendline value)
```

Supprime la valeur spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) | Trendline à supprimer [ITrendline](../../com.aspose.slides/itrendline) |