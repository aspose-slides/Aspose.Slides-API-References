---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une valeur string ou double qui peut être stockée dans un document de présentation pptx de deux manières : 1) dans les cellule(s) du classeur lié au graphique ; 2) en tant que valeur littérale.
type: docs
url: /fr/com.aspose.slides/istringordoublechartvalue/
---
**Toutes les interfaces implémentées:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

Représente une valeur string ou double qui peut être stockée dans un document de présentation pptx de deux manières : 1) dans les cellule(s) du classeur lié au graphique ; 2) en tant que valeur littérale.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Renvoie ou définit la chaîne littérale si la propriété DataSourceType est DataSourceType.StringLiterals. Lecture/écriture String. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Renvoie ou définit la chaîne littérale si la propriété DataSourceType est DataSourceType.StringLiterals. Lecture/écriture String. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Renvoie ou définit le double littéral si la propriété DataSourceType est DataSourceType.DoubleLiterals. Lecture/écriture double. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Renvoie ou définit le double littéral si la propriété DataSourceType est DataSourceType.DoubleLiterals. Lecture/écriture double. |
| [toDouble()](#toDouble--) | Convertit la valeur en double. |
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

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

Renvoie ou définit le double littéral si la propriété DataSourceType est DataSourceType.DoubleLiterals. Lecture/écriture double.

**Renvoie :**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

Renvoie ou définit le double littéral si la propriété DataSourceType est DataSourceType.DoubleLiterals. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

Convertit la valeur en double.

**Renvoie :**
double - Double value double