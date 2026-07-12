---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt einen String- oder Double-Wert dar, der in einem pptx-Präsentationsdokument auf zwei Arten gespeichert werden kann: 1) in Zelle/Zellen des Arbeitsbuchs, das mit einem Diagramm verknüpft ist; 2) als Literalwert.
type: docs
url: /de/com.aspose.slides/istringordoublechartvalue/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

Stellt einen String- oder Double-Wert dar, der in einer pptx-Präsentationsdatei auf zwei Arten gespeichert werden kann: 1) in Zelle/Zellen des Arbeitsbuchs, das mit einem Diagramm verknüpft ist; 2) als Literalwert.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Returns or sets the literal string if DataSourceType property is DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Returns or sets the literal string if DataSourceType property is DataSourceType.StringLiterals. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Returns or sets the literal double if DataSourceType property is DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Returns or sets the literal double if DataSourceType property is DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Converts value to double. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

Gibt den Literal-String zurück oder setzt ihn, wenn die DataSourceType-Eigenschaft DataSourceType.StringLiterals ist. Lesen/Schreiben String.

**Rückgabewert:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

Gibt den Literal-String zurück oder setzt ihn, wenn die DataSourceType-Eigenschaft DataSourceType.StringLiterals ist. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

Gibt den Literal-Double zurück oder setzt ihn, wenn die DataSourceType-Eigenschaft DataSourceType.DoubleLiterals ist. Lesen/Schreiben double.

**Rückgabewert:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

Gibt den Literal-Double zurück oder setzt ihn, wenn die DataSourceType-Eigenschaft DataSourceType.DoubleLiterals ist. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

Konvertiert den Wert in double.

**Rückgabewert:**
double - Double-Wert double