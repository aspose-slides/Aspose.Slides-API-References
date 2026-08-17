---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Zeichenketten- oder Double-Wert dar, der in einer pptx-Präsentationsdatei auf zwei Arten gespeichert werden kann: 1) in Zelle/Zellen einer Arbeitsmappe, die mit einem Diagramm verknüpft ist; 2) als Literalwert.
type: docs
url: /de/com.aspose.slides/istringordoublechartvalue/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

Stellt einen Zeichenketten- oder Double-Wert dar, der in einer pptx-Präsentationsdatei auf zwei Arten gespeichert werden kann: 1) in Zelle/Zellen einer Arbeitsmappe, die mit einem Diagramm verknüpft ist; 2) als Literalwert.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Gibt die literale Zeichenkette zurück oder legt sie fest, wenn die DataSourceType-Eigenschaft DataSourceType.StringLiterals ist. Lesen/Schreiben String. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Gibt die literale Zeichenkette zurück oder legt sie fest, wenn die DataSourceType-Eigenschaft DataSourceType.StringLiterals ist. Lesen/Schreiben String. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Gibt das literal Double zurück oder legt es fest, wenn die DataSourceType-Eigenschaft DataSourceType.DoubleLiterals ist. Lesen/Schreiben double. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Gibt das literal Double zurück oder legt es fest, wenn die DataSourceType-Eigenschaft DataSourceType.DoubleLiterals ist. Lesen/Schreiben double. |
| [toDouble()](#toDouble--) | Konvertiert den Wert zu double. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

Gibt die literale Zeichenkette zurück oder legt sie fest, wenn die DataSourceType-Eigenschaft DataSourceType.StringLiterals ist. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

Gibt die literale Zeichenkette zurück oder legt sie fest, wenn die DataSourceType-Eigenschaft DataSourceType.StringLiterals ist. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

Gibt das literal Double zurück oder legt es fest, wenn die DataSourceType-Eigenschaft DataSourceType.DoubleLiterals ist. Lesen/Schreiben double.

**Rückgabe:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

Gibt das literal Double zurück oder legt es fest, wenn die DataSourceType-Eigenschaft DataSourceType.DoubleLiterals ist. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

Konvertiert den Wert zu double.

**Rückgabe:**
double - Double-Wert double