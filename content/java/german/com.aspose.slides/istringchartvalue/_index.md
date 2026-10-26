---
title: IStringChartValue
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Zeichenkettenwert dar, der in einer pptx-Präsentationsdatei auf zwei Arten gespeichert werden kann: 1) in Zelle/Zellen eines Arbeitsbuchs, das dem Diagramm zugeordnet ist, 2) als literal Wert.
type: docs
url: /de/com.aspose.slides/istringchartvalue/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

Stellt einen Zeichenkettenwert dar, der in einer pptx-Präsentationsdatei auf zwei Arten gespeichert werden kann: 1) in Zelle/Zellen eines Arbeitsbuchs, das dem Diagramm zugeordnet ist; 2) als literaler Wert.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Gibt die literal Zeichenkette zurück oder setzt sie, wenn die DataSourceType-Eigenschaft den Wert DataSourceType.StringLiterals hat. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Gibt die literal Zeichenkette zurück oder setzt sie, wenn die DataSourceType-Eigenschaft den Wert DataSourceType.StringLiterals hat. |
| [toString()](#toString--) | Gibt die Zeichenkettenrepräsentation zurück. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Setzt den Wert aus der angegebenen Zelle. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Wenn die DataSourceType-Eigenschaft den Wert DataSourceType.Worksheet hat, gibt diese Methode die Adresse der Zellen im Arbeitsbuch zurück, die die Zeichenkettendaten darstellen. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

Gibt die literal Zeichenkette zurück oder setzt sie, wenn die DataSourceType-Eigenschaft den Wert DataSourceType.StringLiterals hat. Lese-/Schreibzugriff String.

**Rückgabe:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

Gibt die literal Zeichenkette zurück oder setzt sie, wenn die DataSourceType-Eigenschaft den Wert DataSourceType.StringLiterals hat. Lese-/Schreibzugriff String.

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
java.lang.String - Zeichenkettenrepräsentation eines Wert-String
### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```

Setzt den Wert aus der angegebenen Zelle.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Zelle. |
### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```

Wenn die DataSourceType-Eigenschaft den Wert DataSourceType.Worksheet hat, gibt diese Methode die Adresse der Zellen im Arbeitsbuch zurück, die die Zeichenkettendaten darstellen. Andernfalls wird eine leere Zeichenkette zurückgegeben.

**Rückgabe:**
java.lang.String - Zeichenkettenwert String