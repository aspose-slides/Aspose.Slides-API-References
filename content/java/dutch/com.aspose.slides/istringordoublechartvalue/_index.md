---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides voor Java API Referentie
description: Stelt een string- of double-waarde voor die op twee manieren in een pptx-presentatiedocument kan worden opgeslagen: 1) in cel/cellen van een werkboek gerelateerd aan een diagram; 2) als letterlijke waarde.
type: docs
url: /nl/com.aspose.slides/istringordoublechartvalue/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

Stelt een string- of double-waarde voor die op twee manieren in een pptx-presentatiedocument kan worden opgeslagen: 1) in cel/cellen van een werkboek gerelateerd aan een diagram; 2) als letterlijke waarde.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Retourneert of stelt de letterlijke string in als DataSourceType-eigenschap gelijk is aan DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Retourneert of stelt de letterlijke string in als DataSourceType-eigenschap gelijk is aan DataSourceType.StringLiterals. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Retourneert of stelt de letterlijke double in als DataSourceType-eigenschap gelijk is aan DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Retourneert of stelt de letterlijke double in als DataSourceType-eigenschap gelijk is aan DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Converteert de waarde naar double. |

### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

Retourneert of stelt de letterlijke string in als DataSourceType-eigenschap gelijk is aan DataSourceType.StringLiterals. Lezen/schrijven String.

**Retour:**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

Retourneert of stelt de letterlijke string in als DataSourceType-eigenschap gelijk is aan DataSourceType.StringLiterals. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

Retourneert of stelt de letterlijke double in als DataSourceType-eigenschap gelijk is aan DataSourceType.DoubleLiterals. Lezen/schrijven double.

**Retour:**
double

### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

Retourneert of stelt de letterlijke double in als DataSourceType-eigenschap gelijk is aan DataSourceType.DoubleLiterals. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

Converteert de waarde naar double.

**Retour:**
double - Dubbele waarde double