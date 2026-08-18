---
title: StringChartValue
second_title: Aspose.Slides Java API Referencia
description: Karakterlánc értéket reprezentál, amely két módon tárolható pptx prezentációs dokumentumban: 1) a diagrammal kapcsolódó munkafüzet celláiban/celláiban, 2) literális értékként.
type: docs
url: /hu/com.aspose.slides/stringchartvalue/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Minden megvalósított interfész:**
[com.aspose.slides.IStringChartValue](../../com.aspose.slides/istringchartvalue)
```
public class StringChartValue extends BaseChartValue implements IStringChartValue
```

Kétféleképpen tárolható a pptx prezentációs dokumentumban a karakterlánc értéke: 1) a diagrammal kapcsolódó munkafüzet celláiban; 2) literális értékként.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getAsCells()](#getAsCells--) | Null érték hozzárendelése nem engedélyezett. |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | Null érték hozzárendelése nem engedélyezett. |
| [getAsLiteralString()](#getAsLiteralString--) | Visszaadja vagy beállítja az értéket literális karakterláncként. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Visszaadja vagy beállítja az értéket literális karakterláncként. |
| [getData()](#getData--) | Visszaadja vagy beállítja a Data objektumot. |
| [setData(Object value)](#setData-java.lang.Object-) | Visszaadja vagy beállítja a Data objektumot. |
| [toString()](#toString--) | Visszaadja a karakterlánc értékadatot. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Beállítja az értéket a megadott cellából. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Ha a DataSourceType tulajdonság értéke DataSourceType.Worksheet, akkor ez a metódus visszaadja a munkafüzetben lévő cellák címét, amelyek a karakterlánc adatot képviselik. |

### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```

Null érték hozzárendelése nem engedélyezett. A visszaadott érték mindig nem null. Read/write [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Visszatérési érték:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

Null érték hozzárendelése nem engedélyezett. A visszaadott érték mindig nem null. Read/write [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

Visszaadja vagy beállítja az értéket literális karakterláncként. Read/write String.

**Visszatérési érték:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

Visszaadja vagy beállítja az értéket literális karakterláncként. Read/write String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public Object getData()
```

Visszaadja vagy beállítja a Data objektumot. Read/write Object.

**Visszatérési érték:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Visszaadja vagy beállítja a Data objektumot. Read/write Object.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```

Visszaadja a karakterlánc értékadatot. Null értéket ad vissza, ha a DataSourceType hamis, és nem lett karakterlánc érték hozzárendelve.

**Visszatérési érték:**
java.lang.String
### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```

Beállítja az értéket a megadott cellából.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cella. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```

Ha a DataSourceType tulajdonság értéke DataSourceType.Worksheet, akkor ez a metódus visszaadja a munkafüzetben lévő cellák címét, amelyek a karakterlánc adatot képviselik. Ellenkező esetben üres karakterláncot ad vissza.

**Visszatérési érték:**
java.lang.String