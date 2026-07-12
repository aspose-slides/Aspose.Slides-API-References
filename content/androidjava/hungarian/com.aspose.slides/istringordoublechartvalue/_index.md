---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides Androidhoz a Java API hivatkozás
description: String vagy double értéket képvisel, amely pptx prezentációs dokumentumban két módon tárolható: 1) a diagramhoz kapcsolódó munkafüzet celláiban/celláiban, 2) literális értékként.
type: docs
url: /hu/com.aspose.slides/istringordoublechartvalue/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

A string vagy double értéket, amely pptx prezentációs dokumentumban két módon tárolható: 1) a diagramhoz kapcsolódó munkafüzet celláiban/celláiban; 2) literális értékként.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Visszatér vagy beállítja a literális stringet, ha a DataSourceType tulajdonság értéke DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Visszatér vagy beállítja a literális stringet, ha a DataSourceType tulajdonság értéke DataSourceType.StringLiterals. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Visszatér vagy beállítja a literális double értéket, ha a DataSourceType tulajdonság értéke DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Visszatér vagy beállítja a literális double értéket, ha a DataSourceType tulajdonság értéke DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Az értéket double típusra konvertálja. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

Visszatér vagy beállítja a literális stringet, ha a DataSourceType tulajdonság értéke DataSourceType.StringLiterals. Olvasás/írás String.

**Visszatérési érték:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

Visszatér vagy beállítja a literális stringet, ha a DataSourceType tulajdonság értéke DataSourceType.StringLiterals. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

Visszatér vagy beállítja a literális double értéket, ha a DataSourceType tulajdonság értéke DataSourceType.DoubleLiterals. Olvasás/írás double.

**Visszatérési érték:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

Visszatér vagy beállítja a literális double értéket, ha a DataSourceType tulajdonság értéke DataSourceType.DoubleLiterals. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

Az értéket double típusra konvertálja.

**Visszatérési érték:**
double - Double érték double