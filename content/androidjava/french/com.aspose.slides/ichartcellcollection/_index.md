---
title: IChartCellCollection
second_title: Référence de l'API Java pour Aspose.Slides pour Android
description: Représente une collection de cellules contenant des données.
type: docs
url: /fr/com.aspose.slides/ichartcellcollection/
---
**Toutes les interfaces implémentées :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

Représente une collection de cellules contenant des données.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Renvoie l'adresse de l'ensemble de cellules dans le classeur. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Chaîne de concaténation à partir de toutes les valeurs de cellules. |
| [get_Item(int index)](#get-Item-int-) | Renvoie une cellule (IChartDataCell) par index. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Ajoute une nouvelle cellule à la collection. |
| [add(Object value)](#add-java.lang.Object-) | Crée [IChartDataCell](../../com.aspose.slides/ichartdatacell) à partir de la valeur spécifiée et l'ajoute à la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime une cellule de la collection par index. |
| [getCount()](#getCount--) | Obtient le nombre de cellules dans la collection. |
### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```

Renvoie l'adresse de l'ensemble de cellules dans le classeur.

**Renvoie :**
java.lang.String - Adresse de l'ensemble de cellules dans le classeur String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```

Chaîne de concaténation à partir de toutes les valeurs de cellules.

**Renvoie :**
java.lang.String - Chaîne résultante String
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```

Renvoie une cellule (IChartDataCell) par index.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index d'une cellule. |

**Renvoie :**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell avec données.
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract void add(IChartDataCell chartDataCell)
```

Ajoute une nouvelle cellule à la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nouvelle cellule à ajouter. |

### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```

Crée [IChartDataCell](../../com.aspose.slides/ichartdatacell) à partir de la valeur spécifiée et l'ajoute à la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | La valeur.

--------------------

Cette méthode ajoute une feuille de calcul nommée AUTO_DATA et y ajoute toutes les valeurs. Si vous utilisez [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) pour ajouter ou modifier des valeurs de Cell, assurez-vous de ne pas utiliser cette feuille de calcul. Le nombre maximal de valeurs ajoutées avec cette méthode ne doit pas dépasser 16711680 |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Supprime une cellule de la collection par index.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index d'une cellule à supprimer. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Obtient le nombre de cellules dans la collection. Lecture seule int.

**Renvoie :**
int