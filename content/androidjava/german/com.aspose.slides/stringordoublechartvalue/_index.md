---
title: StringOrDoubleChartValue
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt einen Zeichenketten- oder Double-Wert dar, der in einer pptx-Präsentationsdatei auf zwei Arten gespeichert werden kann: 1) in Zelle/Zellen einer dem Diagramm zugeordneten Arbeitsmappe; 2) als wörtlicher Wert.
type: docs
url: /de/com.aspose.slides/stringordoublechartvalue/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
```
public class StringOrDoubleChartValue extends BaseChartValue implements IStringOrDoubleChartValue
```

Stellt einen Zeichenketten- oder Double-Wert dar, der in einer pptx-Präsentationsdatei auf zwei Arten gespeichert werden kann: 1) in Zelle/Zellen einer dem Diagramm zugeordneten Arbeitsmappe; 2) als Literalwert.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAsCell()](#getAsCell--) | Gibt die Diagrammdatenzelle zurück oder legt sie fest. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Gibt die Diagrammdatenzelle zurück oder legt sie fest. |
| [getAsLiteralString()](#getAsLiteralString--) | Gibt den Wert als Literalzeichenfolge zurück oder legt ihn fest. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Gibt den Wert als Literalzeichenfolge zurück oder legt ihn fest. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Gibt den Wert als Literal-Double zurück oder legt ihn fest. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Gibt den Wert als Literal-Double zurück oder legt ihn fest. |
| [getData()](#getData--) | Gibt das Data-Objekt zurück oder legt es fest. |
| [setData(Object value)](#setData-java.lang.Object-) | Gibt das Data-Objekt zurück oder legt es fest. |
| [toDouble()](#toDouble--) | Konvertiert zu double. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Gibt die Diagrammdatenzelle zurück oder legt sie fest. Lesen/Schreiben [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Rückgabe:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Gibt die Diagrammdatenzelle zurück oder legt sie fest. Lesen/Schreiben [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

Gibt den Wert als Literalzeichenfolge zurück oder legt ihn fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

Gibt den Wert als Literalzeichenfolge zurück oder legt ihn fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

Gibt den Wert als Literal-Double zurück oder legt ihn fest. Lesen/Schreiben double.

**Rückgabe:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

Gibt den Wert als Literal-Double zurück oder legt ihn fest. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getData() {#getData--}
```
public Object getData()
```

Gibt das Data-Objekt zurück oder legt es fest. Lesen/Schreiben Object.

**Rückgabe:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Gibt das Data-Objekt zurück oder legt es fest. Lesen/Schreiben Object.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.Object |  |
### toDouble() {#toDouble--}
```
public final double toDouble()
```

Konvertiert zu double.

**Rückgabe:**
double - Double value.