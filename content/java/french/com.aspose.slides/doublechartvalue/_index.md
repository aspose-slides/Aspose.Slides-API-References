---
title: DoubleChartValue
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une valeur double qui peut être stockée dans un document de présentation pptx de deux manières 1) dans la ou les cellules du classeur liées au graphique 2) en tant que valeur littérale.
type: docs
url: /fr/com.aspose.slides/doublechartvalue/
---
**Héritage:**  
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)  
```
public class DoubleChartValue extends BaseChartValue implements IDoubleChartValue
```

Représente une valeur double qui peut être stockée dans un document de présentation pptx de deux manières : 1) dans la ou les cellules du classeur liées au graphique ; 2) en tant que valeur littérale.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAsCell()](#getAsCell--) | Renvoie ou définit la cellule de données du graphique. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Renvoie ou définit la cellule de données du graphique. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Renvoie ou définit la valeur en tant que double littéral. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Renvoie ou définit la valeur en tant que double littéral. |
| [getData()](#getData--) | Renvoie ou définit l'objet Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Renvoie ou définit l'objet Data. |
| [toDouble()](#toDouble--) | Convertit en double. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Renvoie ou définit la cellule de données du graphique. Lecture/écriture [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Retour:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Renvoie ou définit la cellule de données du graphique. Lecture/écriture [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

Renvoie ou définit la valeur en tant que double littéral. Lecture/écriture double.

**Retour:**  
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

Renvoie ou définit la valeur en tant que double littéral. Lecture/écriture double.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getData() {#getData--}
```
public Object getData()
```

Renvoie ou définit l'objet Data. Lecture/écriture Object.

**Retour:**  
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Renvoie ou définit l'objet Data. Lecture/écriture Object.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |
### toDouble() {#toDouble--}
```
public final double toDouble()
```

Convertit en double.

**Retour:**  
double - Renvoie LiteralDouble si DataSourceType est égal à DoubleLiterals. Si DataSourceType est égal à Worksheet, renvoie la valeur de cellule convertie en double avec succès, sinon renvoie NaN.