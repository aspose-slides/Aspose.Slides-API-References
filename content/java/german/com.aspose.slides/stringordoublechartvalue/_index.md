---
title: StringOrDoubleChartValue
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Zeichenketten- oder Doppelwert dar, der in einer pptx-Präsentationsdatei auf zwei Arten gespeichert werden kann: 1 in Zelle/Zellen des Arbeitsblatts, das mit einem Diagramm verbunden ist 2 als wörtlicher Wert.
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

Stellt einen Zeichenketten- oder Doppelwert dar, der in einer pptx-Präsentationsdatei auf zwei Arten gespeichert werden kann: 1) in Zelle/Zellen des Arbeitsblatts, das mit einem Diagramm verbunden ist; 2) als wörtlicher Wert.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAsCell()](#getAsCell--) | Gibt die Chart-Datenzelle zurück oder setzt sie. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Gibt die Chart-Datenzelle zurück oder setzt sie. |
| [getAsLiteralString()](#getAsLiteralString--) | Gibt den Wert als wörtliche Zeichenkette zurück oder setzt ihn. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Gibt den Wert als wörtliche Zeichenkette zurück oder setzt ihn. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Gibt den Wert als wörtliches double zurück oder setzt ihn. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Gibt den Wert als wörtliches double zurück oder setzt ihn. |
| [getData()](#getData--) | Gibt das Data-Objekt zurück oder setzt es. |
| [setData(Object value)](#setData-java.lang.Object-) | Gibt das Data-Objekt zurück oder setzt es. |
| [toDouble()](#toDouble--) | Konvertiert zu double. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Gibt die Chart-Datenzelle zurück oder setzt sie. Lesen/Schreiben [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Rückgabewert:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Gibt die Chart-Datenzelle zurück oder setzt sie. Lesen/Schreiben [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

Gibt den Wert als wörtliche Zeichenkette zurück oder setzt ihn. Lesen/Schreiben String.

**Rückgabewert:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

Gibt den Wert als wörtliche Zeichenkette zurück oder setzt ihn. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

Gibt den Wert als wörtliches double zurück oder setzt ihn. Lesen/Schreiben double.

**Rückgabewert:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

Gibt den Wert als wörtliches double zurück oder setzt ihn. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getData() {#getData--}
```
public Object getData()
```

Gibt das Data-Objekt zurück oder setzt es. Lesen/Schreiben Object.

**Rückgabewert:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Gibt das Data-Objekt zurück oder setzt es. Lesen/Schreiben Object.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.Object |  |
### toDouble() {#toDouble--}
```
public final double toDouble()
```

Konvertiert zu double.

**Rückgabewert:**
double - Doppelwert.