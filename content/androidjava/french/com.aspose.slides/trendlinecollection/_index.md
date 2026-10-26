---
title: TrendlineCollection
second_title: Référence de l'API Aspose.Slides pour Android via Java
description: Représente une collection de Trendline
type: docs
url: /fr/com.aspose.slides/trendlinecollection/
---
**Héritage:**  
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées:**  
[com.aspose.slides.ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)  
```
public class TrendlineCollection extends DomObject<ChartSeries> implements ITrendlineCollection
```

Représente une collection de Trendline
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [add(int trendlineType)](#add-int-) | Ajoute le nouveau Trendline à la fin d'une collection et le renvoie. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Supprime la valeur spécifiée. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |
| [getCount()](#getCount--) | Obtient le nombre d'éléments réellement contenus dans la collection. |
### get_Item(int index) {#get-Item-int-}
```
public final ITrendline get_Item(int index)
```

Obtient l'élément à l'index spécifié. Lecture seule [Trendline](../../com.aspose.slides/trendline).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie :**
[ITrendline](../../com.aspose.slides/itrendline)
### add(int trendlineType) {#add-int-}
```
public final ITrendline add(int trendlineType)
```

Ajoute le nouveau Trendline à la fin d'une collection et le renvoie.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| trendlineType | int |  |

**Renvoie :**
[ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public final void remove(ITrendline value)
```

Supprime la valeur spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - Un IGenericEnumerator qui peut être utilisé pour parcourir la collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iteratorJava()
```

Renvoie un itérateur java pour l'ensemble de la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - Un java.util.Iterator pour l'ensemble de la collection.
### getCount() {#getCount--}
```
public final int getCount()
```

Renvoie le nombre d'éléments réellement contenus dans la collection. Lecture seule int.

**Renvoie :**
int