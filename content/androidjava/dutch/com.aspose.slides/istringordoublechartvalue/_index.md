---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides voor Android via Java API Referentie
description: Stelt een string- of double-waarde voor die in een pptx-presentatiedocument op twee manieren kan worden opgeslagen: 1 in cel/cellen van de werkmap die bij een grafiek horen; 2 als letterlijke waarde.
type: docs
url: /nl/com.aspose.slides/istringordoublechartvalue/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

Represent string or double value which can be stored in pptx presentation document in two ways: 1) in cell/cells of workbook related to chart; 2) as literal value.
## Methods

| Method | Description |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Retourneert of stelt de letterlijke string in als de DataSourceType-eigenschap DataSourceType.StringLiterals is. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Retourneert of stelt de letterlijke string in als de DataSourceType-eigenschap DataSourceType.StringLiterals is. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Retourneert of stelt de letterlijke double in als de DataSourceType-eigenschap DataSourceType.DoubleLiterals is. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Retourneert of stelt de letterlijke double in als de DataSourceType-eigenschap DataSourceType.DoubleLiterals is. |
| [toDouble()](#toDouble--) | Converteert waarde naar double. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```


Retourneert of stelt de letterlijke string in als de DataSourceType-eigenschap DataSourceType.StringLiterals is. Lezen/Schrijven String.

**Retour:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```


Retourneert of stelt de letterlijke string in als de DataSourceType-eigenschap DataSourceType.StringLiterals is. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```


Retourneert of stelt de letterlijke double in als de DataSourceType-eigenschap DataSourceType.DoubleLiterals is. Lezen/Schrijven double.

**Retour:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```


Retourneert of stelt de letterlijke double in als de DataSourceType-eigenschap DataSourceType.DoubleLiterals is. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Converteert waarde naar double.

**Retour:**
double - Double value double