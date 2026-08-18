---
title: IColumn
second_title: Aspose.Slides for Java API referencia
description: Egy oszlopot ábrázol egy táblázatban.
type: docs
url: /hu/com.aspose.slides/icolumn/
---
**Az összes implementált interfész:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

Egy oszlopot ábrázol egy táblázatban.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getWidth()](#getWidth--) | Visszaadja vagy beállítja egy oszlop szélességét. |
| [setWidth(double value)](#setWidth-double-) | Visszaadja vagy beállítja egy oszlop szélességét. |
| [getColumnFormat()](#getColumnFormat--) | Visszaadja a ColumnFormat objektumot, amely a jelen oszlop formázási tulajdonságait tartalmazza. |

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Visszaadja vagy beállítja egy oszlop szélességét. Olvasás/írás double.

**Visszatér:**
double

### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

Visszaadja vagy beállítja egy oszlop szélességét. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```

Visszaadja a ColumnFormat objektumot, amely a jelen oszlop formázási tulajdonságait tartalmazza. Csak olvasható [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Visszatér:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)