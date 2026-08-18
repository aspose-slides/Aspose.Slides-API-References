---
title: IStringChartValue
second_title: Aspose.Slides Java API referencia
description: Képviseli a karakterlánc értéket, amely a pptx prezentációs dokumentumban két módon tárolható: 1) a diagramhoz kapcsolódó munkafüzet celláiban; 2) szó szerinti értékként.
type: docs
url: /hu/com.aspose.slides/istringchartvalue/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

Képviseli a karakterlánc értéket, amely a pptx prezentációs dokumentumban két módon tárolható: 1) a diagramhoz kapcsolódó munkafüzet celláiban; 2) szó szerinti értékként.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Visszaadja vagy beállítja a szó szerinti karakterláncot, ha a DataSourceType tulajdonság értéke DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Visszaadja vagy beállítja a szó szerinti karakterláncot, ha a DataSourceType tulajdonság értéke DataSourceType.StringLiterals. |
| [toString()](#toString--) | Visszaadja a karakterlánc ábrázolását. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Beállítja az értéket a megadott cellából. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Ha a DataSourceType tulajdonság értéke DataSourceType.Worksheet, akkor ez a metódus visszaadja a munkafüzetben lévő cellák címét, amelyek a karakterlánc adatot képviselik. |

### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

Visszaadja vagy beállítja a szó szerinti karakterláncot, ha a DataSourceType tulajdonság értéke DataSourceType.StringLiterals. Olvasás/írás String.

**Visszatér:**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

Visszaadja vagy beállítja a szó szerinti karakterláncot, ha a DataSourceType tulajdonság értéke DataSourceType.StringLiterals. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public abstract String toString()
```

Visszaadja a karakterlánc ábrázolását.

**Visszatér:**
java.lang.String - Egy érték String karakterlánc ábrázolása

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```

Beállítja az értéket a megadott cellából.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```

Ha a DataSourceType tulajdonság értéke DataSourceType.Worksheet, akkor ez a metódus visszaadja a munkafüzetben lévő cellák címét, amelyek a karakterlánc adatot képviselik. Ellenkező esetben üres karakterláncot ad vissza.

**Visszatér:**
java.lang.String - String érték String