---
title: IStringChartValue
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une valeur de chaîne qui peut être stockée dans un document de présentation pptx de deux manières : 1) dans la ou les cellules du classeur liées au graphique ; 2) comme valeur littérale.
type: docs
url: /fr/com.aspose.slides/istringchartvalue/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

Représente une valeur de chaîne qui peut être stockée dans un document de présentation pptx de deux manières : 1) dans la ou les cellules du classeur liées au graphique ; 2) comme valeur littérale.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Renvoie ou définit la chaîne littérale si la propriété DataSourceType est DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Renvoie ou définit la chaîne littérale si la propriété DataSourceType est DataSourceType.StringLiterals. |
| [toString()](#toString--) | Renvoie la représentation sous forme de chaîne. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Définit la valeur à partir de la cellule spécifiée. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Si la propriété DataSourceType est DataSourceType.Worksheet alors cette méthode renvoie l'adresse des cellules dans le classeur qui représentent les données de chaîne. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

Renvoie ou définit la chaîne littérale si la propriété DataSourceType est DataSourceType.StringLiterals. Lecture/écriture Chaîne.

**Renvoie :**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

Renvoie ou définit la chaîne littérale si la propriété DataSourceType est DataSourceType.StringLiterals. Lecture/écriture Chaîne.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### toString() {#toString--}
```
public abstract String toString()
```

Renvoie la représentation sous forme de chaîne.

**Renvoie :**
java.lang.String - Représentation sous forme de chaîne d'une valeur String
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

Si la propriété DataSourceType est DataSourceType.Worksheet alors cette méthode renvoie l'adresse des cellules dans le classeur qui représentent les données de chaîne. Sinon, retourne une chaîne vide.

**Renvoie :**
java.lang.String - Valeur de chaîne String