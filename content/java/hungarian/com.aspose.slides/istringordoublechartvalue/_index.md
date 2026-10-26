---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides Java API Referencia
description: Karakterlánc vagy double érték ábrázolása, amely pptx prezentációs dokumentumban két módon tárolható: 1) a diagramhoz kapcsolódó munkafüzet celláiban; 2) literális értékként.
type: docs
url: /hu/com.aspose.slides/istringordoublechartvalue/
---
**Összes megvalósított interfész:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

Karakterlánc vagy double érték ábrázolása, amely pptx prezentációs dokumentumban két módon tárolható: 1) a diagramhoz kapcsolódó munkafüzet celláiban; 2) literális értékként.
## Methods

| Method | Description |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Visszaadja vagy beállítja a literális karakterláncot, ha a DataSourceType tulajdonság értéke DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Visszaadja vagy beállítja a literális karakterláncot, ha a DataSourceType tulajdonság értéke DataSourceType.StringLiterals. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Visszaadja vagy beállítja a literális double értéket, ha a DataSourceType tulajdonság értéke DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Visszaadja vagy beállítja a literális double értéket, ha a DataSourceType tulajdonság értéke DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Átalakítja az értéket double típusra. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```


Visszaadja vagy beállítja a literális karakterláncot, ha a DataSourceType tulajdonság értéke DataSourceType.StringLiterals. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```


Visszaadja vagy beállítja a literális karakterláncot, ha a DataSourceType tulajdonság értéke DataSourceType.StringLiterals. Olvasás/írás String.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```


Visszaadja vagy beállítja a literális double értéket, ha a DataSourceType tulajdonság értéke DataSourceType.DoubleLiterals. Olvasás/írás double.

**Visszatér:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```


Visszaadja vagy beállítja a literális double értéket, ha a DataSourceType tulajdonság értéke DataSourceType.DoubleLiterals. Olvasás/írás double.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Átalakítja az értéket double típusra.

**Visszatér:**
double - Double érték double