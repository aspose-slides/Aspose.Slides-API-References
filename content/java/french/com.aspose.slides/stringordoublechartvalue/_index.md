---
title: StringOrDoubleChartValue
second_title: Référence API Aspose.Slides pour Java
description: Représente une valeur de chaîne ou de double pouvant être stockée dans un document de présentation pptx de deux manières : 1) dans la ou les cellules du classeur liées au graphique, 2) en tant que valeur littérale.
type: docs
url: /fr/com.aspose.slides/stringordoublechartvalue/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
```
public class StringOrDoubleChartValue extends BaseChartValue implements IStringOrDoubleChartValue
```

Représente une valeur de chaîne ou de double pouvant être stockée dans un document de présentation pptx de deux manières : 1) dans la/les cellule(s) du classeur liée(s) au graphique ; 2) en tant que valeur littérale.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAsCell()](#getAsCell--) | Renvoie ou définit la cellule de données du graphique. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Renvoie ou définit la cellule de données du graphique. |
| [getAsLiteralString()](#getAsLiteralString--) | Renvoie ou définit la valeur comme chaîne littérale. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Renvoie ou définit la valeur comme chaîne littérale. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Renvoie ou définit la valeur comme double littéral. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Renvoie ou définit la valeur comme double littéral. |
| [getData()](#getData--) | Renvoie ou définit l’objet Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Renvoie ou définit l’objet Data. |
| [toDouble()](#toDouble--) | Convertit en double. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Renvoie ou définit la cellule de données du graphique. Lecture/écriture [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Renvoie :**
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

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

Renvoie ou définit la valeur comme double littéral. Lecture/écriture double.

**Renvoie :**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

Renvoie ou définit la valeur comme double littéral. Lecture/écriture double.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getData() {#getData--}
```
public Object getData()
```

Renvoie ou définit l’objet Data. Lecture/écriture Object.

**Renvoie :**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Renvoie ou définit l’objet Data. Lecture/écriture Object.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |
### toDouble() {#toDouble--}
```
public final double toDouble()
```

Convertit en double.

**Renvoie :**
double - valeur Double.