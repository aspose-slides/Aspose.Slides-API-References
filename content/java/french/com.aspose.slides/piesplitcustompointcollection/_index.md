---
title: PieSplitCustomPointCollection
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une collection de points pour le point de division dans un diagramme à barres de camembert ou à camembert de camembert avec une division personnalisée.
type: docs
url: /fr/com.aspose.slides/piesplitcustompointcollection/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

Représente une collection de points pour le point de division dans un diagramme à barres de camembert ou à camembert de camembert avec une division personnalisée.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Renvoie le point de données du graphique pour l'index spécifié. |
| [add(int dataPointIndex)](#add-int-) | Ajoute un point de données par son indice dans la collection de points de la série parente. |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | Ajoute un point de données à la collection. |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | Supprime l'élément de la collection. |
| [remove(int dataPointIndex)](#remove-int-) | Supprime l'élément de la collection par son indice dans la collection de points de la série parente. |
| [clear()](#clear--) | Supprime tous les éléments de la [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | Détermine si le [IGenericCollection](../../com.aspose.slides/igenericcollection) contient une valeur spécifique. |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | Copie les éléments du [IGenericCollection](../../com.aspose.slides/igenericcollection) vers un Array, en commençant à un indice d'Array particulier. |
| [size()](#size--) | Renvoie ou définit le nombre de points de données du graphique. |
| [isReadOnly()](#isReadOnly--) | Obtient une valeur indiquant si le [IGenericCollection](../../com.aspose.slides/igenericcollection) est en lecture seule. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie une racine de synchronisation. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```


Renvoie le point de données du graphique pour l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index. |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Point de données du graphique.
### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```


Ajoute un point de données par son indice dans la collection de points de la série parente.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| dataPointIndex | int | Indice du point de données dans la collection de points de la série parente. |

### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```


Ajoute un point de données à la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Point de données à ajouter. |

### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```


Supprime l'élément de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Point de données à supprimer. |

**Renvoie :**
boolean - true si l'élément est supprimé avec succès ; sinon false. Cette méthode renvoie également false si l'élément n'a pas été trouvé dans le System.Collections.Generic.List\{T\}.
### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```


Supprime l'élément de la collection par son indice dans la collection de points de la série parente.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| dataPointIndex | int | Indice du point de données dans la collection de points de la série parente. |

### clear() {#clear--}
```
public final void clear()
```


Supprime tous les éléments de la [IGenericCollection](../../com.aspose.slides/igenericcollection).

### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```


Détermine si le [IGenericCollection](../../com.aspose.slides/igenericcollection) contient une valeur spécifique.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | L'objet à localiser dans le [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Renvoie :**
boolean - true si l'élément est trouvé dans le [IGenericCollection](../../com.aspose.slides/igenericcollection) ; sinon false.
### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```


Copie les éléments du [IGenericCollection](../../com.aspose.slides/igenericcollection) vers un Array, en commençant à un indice d'Array particulier.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | Le tableau unidimensionnel qui est la destination des éléments copiés depuis [IGenericCollection](../../com.aspose.slides/igenericcollection). Le tableau doit avoir une indexation à base zéro. |
| arrayIndex | int | L'indice de base zéro dans le tableau où commence la copie. |

### size() {#size--}
```
public final int size()
```


Renvoie ou définit le nombre de points de données du graphique. Lecture seule int.

**Renvoie :**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Obtient une valeur indiquant si le [IGenericCollection](../../com.aspose.slides/igenericcollection) est en lecture seule. Lecture seule boolean.

**Renvoie :**
boolean - true si le [IGenericCollection](../../com.aspose.slides/igenericcollection) est en lecture seule ; sinon false.
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seule boolean.

**Renvoie :**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Renvoie une racine de synchronisation. Lecture seule Object.

**Renvoie :**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```


Renvoie un énumérateur qui parcourt la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Un IGenericEnumerator qui peut être utilisé pour parcourir la collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```


Renvoie un itérateur java pour l'ensemble de la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Un java.util.Iterator pour l'ensemble de la collection.