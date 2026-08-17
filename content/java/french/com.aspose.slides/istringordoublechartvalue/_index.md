---
title: IStringOrDoubleChartValue
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une valeur de chaîne ou de double qui peut être stockée dans un document de présentation pptx de deux manières : 1) dans la ou les cellules du classeur liées au graphique ; 2) comme valeur littérale.
type: docs
url: /fr/com.aspose.slides/istringordoublechartvalue/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

Représente une valeur de chaîne ou de double qui peut être stockée dans un document de présentation pptx de deux manières : 1) dans la ou les cellules du classeur liées au graphique ; 2) comme valeur littérale.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Renvoie ou définit la chaîne littérale si la propriété DataSourceType est DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Renvoie ou définit la chaîne littérale si la propriété DataSourceType est DataSourceType.StringLiterals. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Renvoie ou définit le double littéral si la propriété DataSourceType est DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Renvoie ou définit le double littéral si la propriété DataSourceType est DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Convertit la valeur en double. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

Renvoie ou définit la chaîne littérale si la propriété DataSourceType est DataSourceType.StringLiterals. Lecture/écriture String.

**Retour:**  
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

Renvoie ou définit la chaîne littérale si la propriété DataSourceType est DataSourceType.StringLiterals. Lecture/écriture String.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

Renvoie ou définit le double littéral si la propriété DataSourceType est DataSourceType.DoubleLiterals. Lecture/écriture double.

**Retour:**  
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

Renvoie ou définit le double littéral si la propriété DataSourceType est DataSourceType.DoubleLiterals. Lecture/écriture double.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

Convertit la valeur en double.

**Retour:**  
double - Double value double