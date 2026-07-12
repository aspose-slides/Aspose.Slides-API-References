---
title: IStringChartValue
second_title: Aspose.Slides Android számára a Java API hivatkozás
description: Sztring értéket képvisel, amely a pptx prezentációs dokumentumban két módon tárolható: 1) a diagramhoz kapcsolódó munkafüzet celláiban/celláiban, 2) literális értékként.
type: docs
url: /hu/com.aspose.slides/istringchartvalue/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

A sztring értéket képviseli, amely a pptx prezentációs dokumentumban két módon tárolható: 1) a diagramhoz tartozó munkafüzet celláiban/celláiban; 2) literális értékként.
## Módszerek

| Method | Description |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Visszaadja vagy beállítja a literális sztringet, ha a DataSourceType property az DataSourceType.StringLiterals. Olvasás/írás String. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Visszaadja vagy beállítja a literális sztringet, ha a DataSourceType property az DataSourceType.StringLiterals. Olvasás/írás String. |
| [toString()](#toString--) | Visszaadja a sztring ábrázolását. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Beállítja az értéket a megadott cellából. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Ha a DataSourceType property az DataSourceType.Worksheet, akkor ez a metódus visszaadja a munkafüzetben lévő cellák címét, amelyek a sztring adatot képviselik. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

Visszaadja vagy beállítja a literális sztringet, ha a DataSourceType property az DataSourceType.StringLiterals. Olvasás/írás String.

**Visszatérési érték:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

Visszaadja vagy beállítja a literális sztringet, ha a DataSourceType property az DataSourceType.StringLiterals. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### toString() {#toString--}
```
public abstract String toString()
```

Visszaadja a sztring ábrázolását.

**Visszatérési érték:**
java.lang.String - Egy érték String ábrázolása
### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```

Beállítja az értéket a megadott cellából.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cella. |
### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```

Ha a DataSourceType property az DataSourceType.Worksheet, akkor ez a metódus visszaadja a munkafüzetben lévő cellák címét, amelyek a sztring adatot képviselik. Ellenkező esetben üres sztringet ad vissza.

**Visszatérési érték:**
java.lang.String - String érték String