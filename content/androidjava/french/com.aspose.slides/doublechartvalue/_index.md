---
title: DoubleChartValue
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une valeur double qui peut être stockée dans un document de présentation pptx de deux manières : 1) dans la/les cellule(s) du classeur lié au graphique ; 2) en tant que valeur littérale.
type: docs
url: /fr/com.aspose.slides/doublechartvalue/
---
**Héritage :**  
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Toutes les interfaces implémentées :**  
[com.aspose.slides.IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)  
```
public class DoubleChartValue extends BaseChartValue implements IDoubleChartValue
```

Représente une valeur double qui peut être stockée dans un document de présentation pptx de deux manières : 1) dans la/les cellule(s) du classeur associé au graphique ; 2) en tant que valeur littérale.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getAsCell()](#getAsCell--) | Retourne ou définit la cellule de données du graphique. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Retourne ou définit la cellule de données du graphique. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Retourne ou définit la valeur en tant que double littéral. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Retourne ou définit la valeur en tant que double littéral. |
| [getData()](#getData--) | Retourne ou définit l’objet Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Retourne ou définit l’objet Data. |
| [toDouble()](#toDouble--) | Convertit en double. |

### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Retourne ou définit la cellule de données du graphique. Lecture/écriture [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Retourne :**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Retourne ou définit la cellule de données du graphique. Lecture/écriture [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

Retourne ou définit la valeur en tant que double littéral. Lecture/écriture double.

**Retourne :**  
double

### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

Retourne ou définit la valeur en tant que double littéral. Lecture/écriture double.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getData() {#getData--}
```
public Object getData()
```

Retourne ou définit l’objet Data. Lecture/écriture Object.

**Retourne :**  
java.lang.Object

### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Retourne ou définit l’objet Data. Lecture/écriture Object.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### toDouble() {#toDouble--}
```
public final double toDouble()
```

Convertit en double.

**Retourne :**  
double - Retourne LiteralDouble si DataSourceType est égal à DoubleLiterals. Si DataSourceType est égal à Worksheet, retourne la valeur de cellule convertie avec succès en double, sinon retourne NaN.