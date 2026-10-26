---
title: ChartCategoryCollection
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente la collection de
type: docs
url: /fr/com.aspose.slides/chartcategorycollection/
---
**Héritage :**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées :**
[com.aspose.slides.IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
```
public class ChartCategoryCollection extends DomObject<ChartData> implements IChartCategoryCollection
```

Représente la collection de [ChartCategory](../../com.aspose.slides/chartcategory)
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [getUseCells()](#getUseCells--) | Si true alors la worksheet est utilisée pour stocker les catégories (ce cas prend en charge des catégories à plusieurs niveaux). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Si true alors la worksheet est utilisée pour stocker les catégories (ce cas prend en charge des catégories à plusieurs niveaux). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Renvoie le nombre de niveaux de regroupement de catégories utilisés. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Si la catégorie existe dans la collection, la renvoie. |
| [add(Object value)](#add-java.lang.Object-) | Crée un nouveau [ChartCategory](../../com.aspose.slides/chartcategory) à partir de la valeur et l'ajoute à la collection. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Recherche le [ChartCategory](../../com.aspose.slides/chartcategory) spécifié et renvoie l'index basé sur zéro de la première occurrence dans l'ensemble de la Collection. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Supprime la valeur spécifiée. |
| [removeAt(int index)](#removeAt-int-) | Supprime l'élément à l'index donné. |
| [clear()](#clear--) | Supprime tous les éléments de la collection. |
| [iterator()](#iterator--) | Renvoie un itérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |
| [size()](#size--) | Renvoie le nombre d'éléments de la collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l'accès à la List est synchronisé (thread safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie un objet pouvant être utilisé pour synchroniser l'accès à la collection. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```

Obtient l'élément à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie :**
[IChartCategory](../../com.aspose.slides/ichartcategory) - L'élément à l'index spécifié.
### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```

Si true alors la worksheet est utilisée pour stocker les catégories (ce cas prend en charge des catégories à plusieurs niveaux). Si false alors la worksheet n'est PAS utilisée pour stocker les valeurs (et ce cas ne prend pas en charge des catégories à plusieurs niveaux). Lecture/écriture boolean.

**Renvoie :**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

Si true alors la worksheet est utilisée pour stocker les catégories (ce cas prend en charge des catégories à plusieurs niveaux). Si false alors la worksheet n'est PAS utilisée pour stocker les valeurs (et ce cas ne prend pas en charge des catégories à plusieurs niveaux). Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

Renvoie le nombre de niveaux de regroupement de catégories utilisés. Est supérieur à un pour les catégories à plusieurs niveaux. Lecture seule int.

**Renvoie :**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

Si la catégorie existe dans la collection, la renvoie. Sinon crée une nouvelle catégorie de graphique à partir de [IChartDataCell](../../com.aspose.slides/ichartdatacell) et l'ajoute à la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cellule utilisée pour créer la catégorie de graphique. |

**Renvoie :**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Catégorie ajoutée ou existante.
### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```

Crée un nouveau [ChartCategory](../../com.aspose.slides/chartcategory) à partir de la valeur et l'ajoute à la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | La valeur.

--------------------

Cette méthode ajoute une worksheet nommée AUTO_DATA et y ajoute toutes les valeurs. Si vous utilisez [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) pour ajouter ou modifier des valeurs de cellule, assurez-vous de ne pas utiliser cette worksheet. Le nombre maximal de valeurs ajoutées avec cette méthode ne doit pas dépasser 16711680 |

**Renvoie :**
[IChartCategory](../../com.aspose.slides/ichartcategory) - [IChartCategory](../../com.aspose.slides/ichartcategory) ajouté.
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

Recherche le [ChartCategory](../../com.aspose.slides/chartcategory) spécifié et renvoie l'index basé sur zéro de la première occurrence dans l'ensemble de la Collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Catégorie de graphique. |

**Renvoie :**
int - L'index basé sur zéro de la première occurrence de la valeur dans l'ensemble de la CollectionBase, si trouvé ; sinon, -1.
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```

Supprime la valeur spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | La valeur. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Supprime l'élément à l'index donné.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de la catégorie à supprimer. |
### clear() {#clear--}
```
public final void clear()
```

Supprime tous les éléments de la collection.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```

Renvoie un itérateur qui parcourt la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - Un IGenericEnumerator pouvant être utilisé pour parcourir la collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```

Renvoie un itérateur java pour l'ensemble de la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - Un java.util.Iterator pour l'ensemble de la collection.
### size() {#size--}
```
public final int size()
```

Renvoie le nombre d'éléments de la collection. Lecture seule int.

**Renvoie :**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copie tous les éléments de la collection dans le tableau spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tableau cible. |
| index | int | Index de départ dans le tableau. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Renvoie une valeur indiquant si l'accès à la List est synchronisé (thread safe). Lecture seule boolean.

**Renvoie :**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Renvoie un objet pouvant être utilisé pour synchroniser l'accès à la collection. Lecture seule Object.

Renvoie la racine de synchronisation. Lecture seule Object.

**Renvoie :**
java.lang.Object