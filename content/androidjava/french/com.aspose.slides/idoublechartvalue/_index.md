---
title: IDoubleChartValue
second_title: Référence de l'API Java pour Aspose.Slides pour Android
description: Représente une valeur double qui peut être stockée dans un document de présentation pptx de deux manières: 1) dans les cellules d'un classeur lié à un graphique; 2) en tant que valeur littérale.
type: docs
url: /fr/com.aspose.slides/idoublechartvalue/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

Représente une valeur double qui peut être stockée dans un document de présentation pptx de deux manières : 1) dans les cellules d’un classeur lié à un graphique ; 2) en tant que valeur littérale.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Renvoie ou définit la valeur double littérale si DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Renvoie ou définit la valeur double littérale si DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Convertit en double. |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

Renvoie ou définit la valeur double littérale si DataSourceType = Charts.DataSourceType.DoubleLiterals. Lecture/écriture double.

**Renvoie :**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

Renvoie ou définit la valeur double littérale si DataSourceType = Charts.DataSourceType.DoubleLiterals. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

Convertit en double.

**Renvoie :**
double - Valeur double.