---
title: StringOrDoubleChartValue
second_title: Aspose.Slides Java API referencia
description: Karakterlánc vagy double értéket reprezentál, amely pptx prezentációs dokumentumban két módon tárolható: 1) a diagramhoz kapcsolódó munkafüzet celláiban/celláiban; 2) szó szerinti értékként.
type: docs
url: /hu/com.aspose.slides/stringordoublechartvalue/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Minden megvalósított interfész:**
[com.aspose.slides.IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
```
public class StringOrDoubleChartValue extends BaseChartValue implements IStringOrDoubleChartValue
```

Két módon tárolható karakterlánc vagy double érték egy pptx prezentációs dokumentumban: 1) a diagramhoz kapcsolódó munkafüzet celláiban/celláiban; 2) szó szerinti értékként.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getAsCell()](#getAsCell--) | Visszaadja vagy beállítja a diagram adatcellát. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Visszaadja vagy beállítja a diagram adatcellát. |
| [getAsLiteralString()](#getAsLiteralString--) | Visszaadja vagy beállítja az értéket szó szerinti karakterláncként. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Visszaadja vagy beállítja az értéket szó szerinti karakterláncként. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Visszaadja vagy beállítja az értéket szó szerinti doubleként. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Visszaadja vagy beállítja az értéket szó szerinti doubleként. |
| [getData()](#getData--) | Visszaadja vagy beállítja a Data objektumot. |
| [setData(Object value)](#setData-java.lang.Object-) | Visszaadja vagy beállítja a Data objektumot. |
| [toDouble()](#toDouble--) | Átalakítja double típusúvá. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Visszaadja vagy beállítja a diagram adatcellát. Olvasás/írás [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Visszatér:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Visszaadja vagy beállítja a diagram adatcellát. Olvasás/írás [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

Visszaadja vagy beállítja az értéket szó szerinti karakterláncként. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

Visszaadja vagy beállítja az értéket szó szerinti karakterláncként. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

Visszaadja vagy beállítja az értéket szó szerinti doubleként. Olvasás/írás double.

**Visszatér:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

Visszaadja vagy beállítja az értéket szó szerinti doubleként. Olvasás/írás double.

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

Átalakítja double típusúvá.

**Visszatér:**
double - Double érték.