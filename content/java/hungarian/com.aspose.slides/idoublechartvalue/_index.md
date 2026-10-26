---
title: IDoubleChartValue
second_title: Aspose.Slides Java API Referencia
description: Kétféleképpen tárolható double értéket képvisel a pptx prezentációs dokumentumban: 1) a diagramhoz kapcsolódó munkafüzet celláiban/celláiban; 2) literális értékként.
type: docs
url: /hu/com.aspose.slides/idoublechartvalue/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

Képviseli a double értéket, amely két módon tárolható pptx prezentációs dokumentumban: 1) a diagramhoz kapcsolódó munkafüzet celláiban/celláiban; 2) literális értékként.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Visszaad vagy beállítja a literális double értéket, ha a DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Visszaad vagy beállítja a literális double értéket, ha a DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Átalakít double típusra. |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

Visszaad vagy beállítja a literális double értéket, ha a DataSourceType = Charts.DataSourceType.DoubleLiterals. Olvasás/írás double.

**Visszatér:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

Visszaad vagy beállítja a literális double értéket, ha a DataSourceType = Charts.DataSourceType.DoubleLiterals. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

Átalakít double típusra.

**Visszatér:**
double - Double érték.