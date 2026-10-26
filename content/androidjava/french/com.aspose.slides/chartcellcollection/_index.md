---
title: ChartCellCollection
second_title: Référence API Java via Aspose.Slides pour Android
description: Représente une collection de cellules contenant des données.
type: docs
url: /fr/com.aspose.slides/chartcellcollection/
---
**Héritage:**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

Représente une collection de cellules contenant des données.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Renvoie l'adresse de l'ensemble de cellules dans le classeur. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Chaîne de concaténation des valeurs de toutes les cellules. |
| [get_Item(int index)](#get-Item-int-) | Renvoie une cellule (IChartDataCell) par index. |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | Ajoute une nouvelle cellule à la collection. |
| [add(Object value)](#add-java.lang.Object-) | Crée [ChartDataCell](../../com.aspose.slides/chartdatacell) à partir de la valeur spécifiée et l'ajoute à la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime une cellule de la collection par index. |
| [getCount()](#getCount--) | Obtient le nombre de cellules dans la collection. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'intégralité de la collection. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```

Renvoie l'adresse de l'ensemble de cellules dans le classeur.

**Renvoie :**
java.lang.String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```

Chaîne de concaténation des valeurs de toutes les cellules.

**Renvoie :**
java.lang.String
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```

Renvoie une cellule (IChartDataCell) par index.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index d'une cellule. |

**Renvoie :**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell avec des données.
### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```

Ajoute une nouvelle cellule à la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nouvelle cellule à ajouter. |
### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```

Crée [ChartDataCell](../../com.aspose.slides/chartdatacell) à partir de la valeur spécifiée et l'ajoute à la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | La valeur.

--------------------

Cette méthode ajoute une feuille de calcul nommée AUTO_DATA et y ajoute toutes les valeurs. Si vous utilisez [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) pour ajouter ou modifier des valeurs Cell, assurez-vous de ne pas utiliser cette feuille de calcul. Le nombre maximal de valeurs ajoutées avec cette méthode ne doit pas dépasser 16711680 |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Supprime une cellule de la collection par index.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index d'une cellule à supprimer. |
### getCount() {#getCount--}
```
public final int getCount()
```

Obtient le nombre de cellules dans la collection. Lecture seule int.

**Renvoie :**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - Un IGenericEnumerator pouvant être utilisé pour parcourir la collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```

Renvoie un itérateur java pour l'intégralité de la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - Un java.util.Iterator pour l'intégralité de la collection.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Renvoie l'objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie :**
com.aspose.slides.IDOMObject