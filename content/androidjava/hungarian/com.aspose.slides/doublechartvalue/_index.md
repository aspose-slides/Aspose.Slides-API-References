---
title: DoubleChartValue
second_title: Aspose.Slides Androidhoz Java API referencia
description: Kettős értéket képvisel, amely két módon tárolható a pptx prezentációs dokumentumban: 1) a diagramhoz kapcsolódó munkafüzet celláiban/celláiban, 2) literális értékként.
type: docs
url: /hu/com.aspose.slides/doublechartvalue/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Minden megvalósított interfész:**
[com.aspose.slides.IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
```
public class DoubleChartValue extends BaseChartValue implements IDoubleChartValue
```

Kettős értéket képvisel, amely két módon tárolható a pptx bemutató dokumentumban: 1) a diagramhoz kapcsolódó munkafüzet celláiban/celláiban; 2) literális értékként.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getAsCell()](#getAsCell--) | Visszaadja vagy beállítja a diagram adatcelláját. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Visszaadja vagy beállítja a diagram adatcelláját. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Visszaadja vagy beállítja az értéket literális double-ként. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Visszaadja vagy beállítja az értéket literális double-ként. |
| [getData()](#getData--) | Visszaadja vagy beállítja a Data objektumot. |
| [setData(Object value)](#setData-java.lang.Object-) | Visszaadja vagy beállítja a Data objektumot. |
| [toDouble()](#toDouble--) | Átkonvertál double-ra. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```


Visszaadja vagy beállítja a diagram adatcelláját. Olvasás/írás [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Visszatér:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```


Visszaadja vagy beállítja a diagram adatcelláját. Olvasás/írás [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```


Visszaadja vagy beállítja az értéket literális double-ként. Olvasás/írás double.

**Visszatér:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```


Visszaadja vagy beállítja az értéket literális double-ként. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getData() {#getData--}
```
public Object getData()
```


Visszaadja vagy beállítja a Data objektumot. Olvasás/írás Object.

**Visszatér:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```


Visszaadja vagy beállítja a Data objektumot. Olvasás/írás Object.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Object |  |

### toDouble() {#toDouble--}
```
public final double toDouble()
```


Átkonvertál double-ra.

**Visszatér:**
double - Visszaadja a LiteralDouble értéket, ha a DataSourceType egyenlő a DoubleLiterals-szal. Ha a DataSourceType egyenlő a Worksheet-szal, visszaadja a sikeresen double-ra konvertált cellaértéket, egyébként NaN-t ad vissza.