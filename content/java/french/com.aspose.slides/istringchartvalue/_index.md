---
title: IStringChartValue
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une valeur de chaîne pouvant être stockée dans un document de présentation pptx de deux manières : 1) dans la/les cellule(s) du classeur lié au graphique ; 2) en tant que valeur littérale.
type: docs
url: /fr/com.aspose.slides/istringchartvalue/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

Représente la valeur de chaîne qui peut être stockée dans un document de présentation pptx de deux manières : 1) dans la/les cellule(s) du classeur lié au graphique ; 2) en tant que valeur littérale.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Renvoie ou définit la chaîne littérale si la propriété DataSourceType est DataSourceType.StringLiterals. Lecture/écriture String. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Renvoie ou définit la chaîne littérale si la propriété DataSourceType est DataSourceType.StringLiterals. Lecture/écriture String. |
| [toString()](#toString--) | Renvoie la String représentation. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Définit la valeur à partir de la cellule spécifiée. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Si la propriété DataSourceType est DataSourceType.Worksheet, alors cette méthode renvoie l'adresse des cellules dans le classeur qui représentent les données de chaîne. |

### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```


Renvoie ou définit la chaîne littérale si la propriété DataSourceType est DataSourceType.StringLiterals. Lecture/écriture String.

**Renvoie :**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```


Renvoie ou définit la chaîne littérale si la propriété DataSourceType est DataSourceType.StringLiterals. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public abstract String toString()
```


Renvoie la String représentation.

**Renvoie :**
java.lang.String - String représentation d'une valeur String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```


Définit la valeur à partir de la cellule spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cellule. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```


Si la propriété DataSourceType est DataSourceType.Worksheet, alors cette méthode renvoie l'adresse des cellules dans le classeur qui représentent les données de chaîne. Sinon, renvoie une chaîne vide.

**Renvoie :**
java.lang.String - String valeur String