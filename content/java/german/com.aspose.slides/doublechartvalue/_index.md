---
title: DoubleChartValue
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen double-Wert dar, der in einem pptx-Präsentationsdokument auf zwei Arten gespeichert werden kann: 1) in Zelle/Zellen des Arbeitsblatts, das dem Diagramm zugeordnet ist; 2) als Literalwert.
type: docs
url: /de/com.aspose.slides/doublechartvalue/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**All Implemented Interfaces:**
[com.aspose.slides.IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
```
public class DoubleChartValue extends BaseChartValue implements IDoubleChartValue
```

Stellt einen double-Wert dar, der in einem pptx-Präsentationsdokument auf zwei Arten gespeichert werden kann: 1) in Zelle/Zellen des Arbeitsblatts, das dem Diagramm zugeordnet ist; 2) als Literalwert.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAsCell()](#getAsCell--) | Gibt die Diagrammdatenzelle zurück oder setzt sie. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Gibt die Diagrammdatenzelle zurück oder setzt sie. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Gibt den Wert als Literal-double zurück oder setzt ihn. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Gibt den Wert als Literal-double zurück oder setzt ihn. |
| [getData()](#getData--) | Gibt das Data-Objekt zurück oder setzt es. |
| [setData(Object value)](#setData-java.lang.Object-) | Gibt das Data-Objekt zurück oder setzt es. |
| [toDouble()](#toDouble--) | Konvertiert zu double. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```


Gibt die Diagrammdatenzelle zurück oder setzt sie. Lesen/Schreiben [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Rückgabe:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```


Gibt die Diagrammdatenzelle zurück oder setzt sie. Lesen/Schreiben [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```


Gibt den Wert als Literal-double zurück oder setzt ihn. Lesen/Schreiben double.

**Rückgabe:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```


Gibt den Wert als Literal-double zurück oder setzt ihn. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getData() {#getData--}
```
public Object getData()
```


Gibt das Data-Objekt zurück oder setzt es. Lesen/Schreiben Object.

**Rückgabe:**
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

**Rückgabe:**
double - Gibt LiteralDouble zurück, wenn DataSourceType gleich DoubleLiterals ist. Wenn DataSourceType gleich Worksheet ist, wird der erfolgreich zu double konvertierte Zellenwert zurückgegeben, andernfalls NaN.