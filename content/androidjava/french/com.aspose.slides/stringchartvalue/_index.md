---
title: StringChartValue
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une valeur de chaîne qui peut être stockée dans un document de présentation pptx de deux manières : 1) dans la ou les cellules du classeur liées au graphique ; 2) comme valeur littérale.
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

Représente une valeur de chaîne qui peut être stockée dans un document de présentation pptx de deux manières : 1) dans la ou les cellules du classeur lié au graphique ; 2) comme valeur littérale.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAsCells()](#getAsCells--) | L'affectation d'une valeur null n'est pas autorisée. |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | L'affectation d'une valeur null n'est pas autorisée. |
| [getAsLiteralString()](#getAsLiteralString--) | Renvoie ou définit la valeur comme chaîne littérale. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Renvoie ou définit la valeur comme chaîne littérale. |
| [getData()](#getData--) | Renvoie ou définit l'objet Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Renvoie ou définit l'objet Data. |
| [toString()](#toString--) | Renvoie les données de valeur de chaîne. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Définit la valeur à partir de la cellule spécifiée. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Si la propriété DataSourceType est DataSourceType.Worksheet, cette méthode renvoie l'adresse des cellules du classeur qui représentent les données de chaîne. |

### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```

L'affectation d'une valeur null n'est pas autorisée. La valeur retournée n'est jamais nulle. Lecture/écriture [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Renvoie :**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

L'affectation d'une valeur null n'est pas autorisée. La valeur retournée n'est jamais nulle. Lecture/écriture [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

Renvoie ou définit la valeur comme chaîne littérale. Lecture/écriture String.

**Renvoie :**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

Renvoie ou définit la valeur comme chaîne littérale. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public Object getData()
```

Renvoie ou définit l'objet Data. Lecture/écriture Object.

**Renvoie :**
java.lang.Object

### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Renvoie ou définit l'objet Data. Lecture/écriture Object.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```

Renvoie les données de valeur de chaîne. Renvoie null si DataSourceType est false et aucune valeur de chaîne n'a été assignée.

**Renvoie :**
java.lang.String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```

Définit la valeur à partir de la cellule spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```

Si la propriété DataSourceType est DataSourceType.Worksheet, cette méthode renvoie l'adresse des cellules du classeur qui représentent les données de chaîne. Sinon, renvoie une chaîne vide.

**Renvoie :**
java.lang.String