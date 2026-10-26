---
title: IChartCategoryCollection
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente une collection de
type: docs
url: /fr/com.aspose.slides/ichartcategorycollection/
---
**Toutes les interfaces implémentées :**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

Représente une collection de [IChartCategory](../../com.aspose.slides/ichartcategory)
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [getUseCells()](#getUseCells--) | Si true alors la feuille de calcul est utilisée pour stocker les catégories (ce cas prend en charge des catégories à plusieurs niveaux). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Si true alors la feuille de calcul est utilisée pour stocker les catégories (ce cas prend en charge des catégories à plusieurs niveaux). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Renvoie le nombre de niveaux de regroupement de catégorie utilisés. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Si la catégorie existe dans la collection, la retourner. |
| [add(Object value)](#add-java.lang.Object-) | Crée un nouveau [IChartCategory](../../com.aspose.slides/ichartcategory) à partir de la valeur et l'ajoute à la collection. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Recherche le [IChartCategory](../../com.aspose.slides/ichartcategory) spécifié et renvoie l'index basé sur zéro de la première occurrence dans l'ensemble de la Collection |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Supprime la valeur spécifiée. |
| [removeAt(int index)](#removeAt-int-) | Supprime l'élément à l'index donné. |
| [clear()](#clear--) | Supprime tous les éléments de la collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```

Obtient l'élément à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retour :**
[IChartCategory](../../com.aspose.slides/ichartcategory) - L'élément à l'index spécifié.
### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```

Si true alors la feuille de calcul est utilisée pour stocker les catégories (ce cas prend en charge des catégories à plusieurs niveaux). Si false alors la feuille de calcul N'EST PAS utilisée pour stocker les valeurs (et ce cas ne prend pas en charge des catégories à plusieurs niveaux). Booléen lecture/écriture.

**Retour :**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```

Si true alors la feuille de calcul est utilisée pour stocker les catégories (ce cas prend en charge des catégories à plusieurs niveaux). Si false alors la feuille de calcul N'EST PAS utilisée pour stocker les valeurs (et ce cas ne prend pas en charge des catégories à plusieurs niveaux). Booléen lecture/écriture.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```

Renvoie le nombre de niveaux de regroupement de catégorie utilisés. Est supérieur à un pour les catégories à plusieurs niveaux. Int en lecture seule.

**Retour :**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```

Si la catégorie existe dans la collection, la retourner. Sinon crée une nouvelle catégorie de graphique à partir de [IChartDataCell](../../com.aspose.slides/ichartdatacell) et l'ajoute à la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cellule utilisée pour créer la catégorie de graphique. |

**Retour :**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Catégorie ajoutée ou existante.
### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```

Crée un nouveau [IChartCategory](../../com.aspose.slides/ichartcategory) à partir de la valeur et l'ajoute à la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | La valeur.

--------------------

Cette méthode ajoute une feuille de calcul nommée AUTO_DATA et y ajoute toutes les valeurs. Si vous utilisez [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) pour ajouter ou modifier des valeurs de cellules, assurez-vous de ne pas utiliser cette feuille de calcul. Le nombre maximal de valeurs ajoutées avec cette méthode ne doit pas dépasser 16711680

**Retour :**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Ajouté [IChartCategory](../../com.aspose.slides/ichartcategory).
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```

Recherche le [IChartCategory](../../com.aspose.slides/ichartcategory) spécifié et renvoie l'index basé sur zéro de la première occurrence dans l'ensemble de la Collection

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Catégorie de graphique. |

**Retour :**
int - L'index basé sur zéro de la première occurrence de la valeur dans l'ensemble de la CollectionBase, s'il est trouvé ; sinon, -1.
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```

Supprime la valeur spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | La valeur. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Supprime l'élément à l'index donné.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de la catégorie à supprimer. |
### clear() {#clear--}
```
public abstract void clear()
```

Supprime tous les éléments de la collection.