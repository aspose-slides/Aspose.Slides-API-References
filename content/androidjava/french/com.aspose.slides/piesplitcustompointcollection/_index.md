---
title: PieSplitCustomPointCollection
second_title: Aspose.Slides pour Android via Référence API Java
description: Représente une collection de points pour le point de séparation dans un graphique à anneau ou un graphique à anneau imbriqué avec une division personnalisée.
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

Représente une collection de points pour le point de séparation dans un graphique à anneau ou un graphique à anneau imbriqué avec une division personnalisée.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Renvoie le point de données du graphique pour l'index spécifié. |
| [add(int dataPointIndex)](#add-int-) | Ajoute un point de données à son index dans la collection de points de la série parente. |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | Ajoute un point de données à la collection. |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | Supprime l'élément de la collection. |
| [remove(int dataPointIndex)](#remove-int-) | Supprime l'élément de la collection par son index dans la collection de points de la série parente. |
| [clear()](#clear--) | Supprime tous les éléments du [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | Détermine si le [IGenericCollection](../../com.aspose.slides/igenericcollection) contient une valeur spécifique. |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | Copie les éléments du [IGenericCollection](../../com.aspose.slides/igenericcollection) vers un tableau, en commençant à un index de tableau particulier. |
| [size()](#size--) | Renvoie ou définit le nombre de points de données du graphique. |
| [isReadOnly()](#isReadOnly--) | Obtient une valeur indiquant si le [IGenericCollection](../../com.aspose.slides/igenericcollection) est en lecture seule. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie une racine de synchronisation. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur Java pour l'ensemble de la collection. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Renvoie le point de données du graphique pour l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice. |

**Renvoie :**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Point de données du graphique.
### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

Ajoute un point de données à son index dans la collection de points de la série parente.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| dataPointIndex | int | Index du point de données dans la collection de points de la série parente. |

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
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Point de données à retirer. |

**Renvoie :**
boolean - true si l'élément a été supprimé avec succès ; sinon, false. Cette méthode renvoie également false si l'élément n'a pas été trouvé dans le System.Collections.Generic.List\{T\}.
### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

Supprime l'élément de la collection par son index dans la collection de points de la série parente.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| dataPointIndex | int | Index du point de données dans la collection de points de la série parente. |

### clear() {#clear--}
```
public final void clear()
```

Supprime tous les éléments du [IGenericCollection](../../com.aspose.slides/igenericcollection).

### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```

Détermine si le [IGenericCollection](../../com.aspose.slides/igenericcollection) contient une valeur spécifique.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | L'objet à rechercher dans le [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Renvoie :**
boolean - true si l'élément est trouvé dans le [IGenericCollection](../../com.aspose.slides/igenericcollection) ; sinon, false.
### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

Copie les éléments du [IGenericCollection](../../com.aspose.slides/igenericcollection) vers un tableau, en commençant à un index de tableau particulier.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | Le tableau unidimensionnel qui est la destination des éléments copiés depuis [IGenericCollection](../../com.aspose.slides/igenericcollection). Le tableau doit être indexé à partir de zéro. |
| arrayIndex | int | L'index de base zéro dans le tableau à partir duquel la copie commence. |

### size() {#size--}
```
public final int size()
```

Renvoie ou définit le nombre de points de données du graphique. Entier en lecture seule.

**Renvoie :**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Obtient une valeur indiquant si le [IGenericCollection](../../com.aspose.slides/igenericcollection) est en lecture seule. Booléen en lecture seule.

**Renvoie :**
boolean - true si le [IGenericCollection](../../com.aspose.slides/igenericcollection) est en lecture seule ; sinon, false.
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Booléen en lecture seule.

**Renvoie :**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Renvoie une racine de synchronisation. Objet en lecture seule.

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

Renvoie un itérateur Java pour l'ensemble de la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Un java.util.Iterator pour l'ensemble de la collection.