---
title: IStringChartValue
second_title: Aspose.Slides für Android über die Java API Referenz
description: Stellt einen Zeichenfolgenwert dar, der im pptx-Präsentationsdokument auf zwei Arten gespeichert werden kann - 1 in Zelle(n) des Arbeitsblatts, das dem Diagramm zugeordnet ist, 2 als Literalwert.
type: docs
url: /de/com.aspose.slides/istringchartvalue/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

Stellt einen Zeichenfolgenwert dar, der im pptx-Präsentationsdokument auf zwei Arten gespeichert werden kann: 1) in Zelle(n) des Arbeitsblatts, das dem Diagramm zugeordnet ist; 2) als Literalwert.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Gibt die Literalzeichenfolge zurück oder setzt sie, wenn die Eigenschaft DataSourceType den Wert DataSourceType.StringLiterals hat. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Gibt die Literalzeichenfolge zurück oder setzt sie, wenn die Eigenschaft DataSourceType den Wert DataSourceType.StringLiterals hat. |
| [toString()](#toString--) | Gibt die Zeichenkettenrepräsentation zurück. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Setzt den Wert aus der angegebenen Zelle. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Wenn die Eigenschaft DataSourceType den Wert DataSourceType.Worksheet hat, gibt diese Methode die Adresse der Zellen im Arbeitsbuch zurück, die die Zeichenfolgendaten darstellen. |

### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

Gibt die Literalzeichenfolge zurück oder setzt sie, wenn die Eigenschaft DataSourceType den Wert DataSourceType.StringLiterals hat. Lese-/Schreibzugriff String.

**Rückgabe:**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

Gibt die Literalzeichenfolge zurück oder setzt sie, wenn die Eigenschaft DataSourceType den Wert DataSourceType.StringLiterals hat. Lese-/Schreibzugriff String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public abstract String toString()
```

Gibt die Zeichenkettenrepräsentation zurück.

**Rückgabe:**
java.lang.String - String representation of a value

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```

Setzt den Wert aus der angegebenen Zelle.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```

Wenn die Eigenschaft DataSourceType den Wert DataSourceType.Worksheet hat, gibt diese Methode die Adresse der Zellen im Arbeitsbuch zurück, die die Zeichenfolgendaten darstellen. Andernfalls wird eine leere Zeichenfolge zurückgegeben.

**Rückgabe:**
java.lang.String - String value