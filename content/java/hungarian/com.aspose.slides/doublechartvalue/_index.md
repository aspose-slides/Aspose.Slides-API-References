---
title: DoubleChartValue
second_title: Aspose.Slides Java API hivatkozás
description: Képviseli a dupla értéket, amely pptx prezentációs dokumentumban két módon tárolható: 1) a diagramhoz kapcsolódó munkafüzet celláiban; 2) literális értékként.
type: docs
url: /hu/com.aspose.slides/doublechartvalue/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Minden Implementált Interfész:**
[com.aspose.slides.IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
```
public class DoubleChartValue extends BaseChartValue implements IDoubleChartValue
```

Képviseli a dupla értéket, amely pptx prezentációs dokumentumban két módon tárolható: 1) a diagramhoz kapcsolódó munkafüzet celláiban; 2) literális értékként.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getAsCell()](#getAsCell--) | Visszaadja vagy beállítja a diagram adatcelláját. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Visszaadja vagy beállítja a diagram adatcelláját. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Visszaadja vagy beállítja az értéket literális doubleként. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Visszaadja vagy beállítja az értéket literális doubleként. |
| [getData()](#getData--) | Visszaadja vagy beállítja a Data objektumot. |
| [setData(Object value)](#setData-java.lang.Object-) | Visszaadja vagy beállítja a Data objektumot. |
| [toDouble()](#toDouble--) | Átalakítja double típusra. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Visszaadja vagy beállítja a diagram adatcelláját. Olvasás/írás [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Visszatérési érték:**
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

Visszaadja vagy beállítja az értéket literális doubleként. Olvasás/írás double.

**Visszatérési érték:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

Visszaadja vagy beállítja az értéket literális doubleként. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### getData() {#getData--}
```
public Object getData()
```

Visszaadja vagy beállítja a Data objektumot. Olvasás/írás Object.

**Visszatérési érték:**
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

Átalakítja double típusra.

**Visszatérési érték:**
double - Visszaad egy LiteralDouble értéket, ha a DataSourceType megegyezik a DoubleLiterals értékkel. Ha a DataSourceType Worksheet, akkor sikeresen double típusra konvertált cellaértéket ad vissza, egyébként NaN-t ad vissza.