---
title: IDoubleChartValue
second_title: Aspose.Slides Androidhoz Java API referenciája
description: Kettő módon tárolható double érték a pptx prezentációs dokumentumban: 1) a diagramhoz kapcsolódó munkafüzet celláiban/celláiban; 2) literális értékként.
type: docs
url: /hu/com.aspose.slides/idoublechartvalue/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

Kettő módon tárolható dupla érték a pptx prezentációs dokumentumban: 1) a diagramhoz kapcsolódó munkafüzet celláiban/celláiban; 2) literális értékként.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Visszaadja vagy beállítja a literális double értéket, ha a DataSourceType = Charts.DataSourceType.DoubleLiterals. Olvasás/írás double. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Visszaadja vagy beállítja a literális double értéket, ha a DataSourceType = Charts.DataSourceType.DoubleLiterals. Olvasás/írás double. |
| [toDouble()](#toDouble--) | Átalakít double típusra. |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

Visszaadja vagy beállítja a literális double értéket, ha a DataSourceType = Charts.DataSourceType.DoubleLiterals. Olvasás/írás double.

**Visszatérési érték:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

Visszaadja vagy beállítja a literális double értéket, ha a DataSourceType = Charts.DataSourceType.DoubleLiterals. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

Átalakít double típusra.

**Visszatérési érték:**
double - Double érték.