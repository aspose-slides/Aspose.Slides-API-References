---
title: StringChartValue
second_title: Référence API Aspose.Slides pour Java
description: Représente la valeur de chaîne qui peut être stockée dans un document de présentation pptx de deux manières : 1 dans la ou les cellules du classeur lié au graphique ; 2 en tant que valeur littérale.
type: docs
url: /fr/com.aspose.slides/stringchartvalue/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IStringChartValue](../../com.aspose.slides/istringchartvalue)
```
public class StringChartValue extends BaseChartValue implements IStringChartValue
```

Représente la valeur de chaîne qui peut être stockée dans un document de présentation pptx de deux manières : 1) dans la ou les cellules du classeur lié au graphique ; 2) comme valeur littérale.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAsCells()](#getAsCells--) | L'affectation d'une valeur nulle n'est pas autorisée. |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | L'affectation d'une valeur nulle n'est pas autorisée. |
| [getAsLiteralString()](#getAsLiteralString--) | Retourne ou définit la valeur en tant que chaîne littérale. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Retourne ou définit la valeur en tant que chaîne littérale. |
| [getData()](#getData--) | Retourne ou définit l'objet Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Retourne ou définit l'objet Data. |
| [toString()](#toString--) | Retourne les données de valeur de chaîne. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Définit la valeur à partir de la cellule spécifiée. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Si la propriété DataSourceType est DataSourceType.Worksheet, cette méthode renvoie l'adresse des cellules du classeur qui représentent les données de chaîne. |
### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```


L'affectation d'une valeur nulle n'est pas autorisée. La valeur retournée n'est jamais nulle. Lecture/écriture [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Retourne :**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```


L'affectation d'une valeur nulle n'est pas autorisée. La valeur retournée n'est jamais nulle. Lecture/écriture [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```


Retourne ou définit la valeur en tant que chaîne littérale. Lecture/écriture String.

**Retourne :**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```


Retourne ou définit la valeur en tant que chaîne littérale. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public Object getData()
```


Retourne ou définit l'objet Data. Lecture/écriture Object.

**Retourne :**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```


Retourne ou définit l'objet Data. Lecture/écriture Object.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```


Retourne les données de valeur de chaîne. Retourne null si DataSourceType est false et qu'aucune valeur de chaîne n'a été assignée.

**Retourne :**
java.lang.String
### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```


Définit la valeur à partir de la cellule spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cellule. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```


Si la propriété DataSourceType est DataSourceType.Worksheet, cette méthode renvoie l'adresse des cellules du classeur qui représentent les données de chaîne. Sinon, renvoie une chaîne vide.

**Retourne :**
java.lang.String