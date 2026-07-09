---
title: StringOrDoubleChartValue
second_title: Référence API Java d'Aspose.Slides pour Android
description: "Représente une valeur chaîne ou double pouvant être stockée dans un document de présentation pptx de deux manières : 1) dans la/les cellule(s) du classeur lié au graphique ; 2) en tant que valeur littérale."
type: docs
url: /fr/com.aspose.slides/stringordoublechartvalue/
---
**Héritage:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Toutes les interfaces implémentées:**
[com.aspose.slides.IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
```
public class StringOrDoubleChartValue extends BaseChartValue implements IStringOrDoubleChartValue
```

Représente une valeur chaîne ou double qui peut être stockée dans un document de présentation pptx de deux manières : 1) dans la/les cellule(s) du classeur lié au graphique ; 2) en tant que valeur littérale.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAsCell()](#getAsCell--) | Retourne ou définit la cellule de données du graphique. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Retourne ou définit la cellule de données du graphique. |
| [getAsLiteralString()](#getAsLiteralString--) | Retourne ou définit la valeur en tant que chaîne littérale. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Retourne ou définit la valeur en tant que chaîne littérale. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Retourne ou définit la valeur en tant que double littéral. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Retourne ou définit la valeur en tant que double littéral. |
| [getData()](#getData--) | Retourne ou définit l'objet Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Retourne ou définit l'objet Data. |
| [toDouble()](#toDouble--) | Convertit en double. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Retourne ou définit la cellule de données du graphique. Lecture/écriture [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Retour:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Retourne ou définit la cellule de données du graphique. Lecture/écriture [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

Retourne ou définit la valeur en tant que chaîne littérale. Lecture/écriture String.

**Retour:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

Retourne ou définit la valeur en tant que chaîne littérale. Lecture/écriture String.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

Retourne ou définit la valeur en tant que double littéral. Lecture/écriture double.

**Retour:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

Retourne ou définit la valeur en tant que double littéral. Lecture/écriture double.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getData() {#getData--}
```
public Object getData()
```

Retourne ou définit l'objet Data. Lecture/écriture Object.

**Retour:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Retourne ou définit l'objet Data. Lecture/écriture Object.

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
double - Double valeur.