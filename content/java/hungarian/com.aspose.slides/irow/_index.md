---
title: IRow
second_title: Aspose.Slides Java API referenciája
description: Egy sort reprezentál egy táblázatban.
type: docs
url: /hu/com.aspose.slides/irow/
---
**All Implemented Interfaces:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

Egy sort reprezentál egy táblázatban.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getHeight()](#getHeight--) | Visszaadja a sor magasságát. |
| [getMinimalHeight()](#getMinimalHeight--) | Visszaadja vagy beállítja a sor minimálisan lehetséges magasságát. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Visszaadja vagy beállítja a sor minimálisan lehetséges magasságát. |
| [getRowFormat()](#getRowFormat--) | Visszaadja a RowFormat objektumot, amely a sor formázási tulajdonságait tartalmazza. |
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

Visszaadja a sor magasságát. Csak olvasható double.

**Visszatér:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

Visszaadja vagy beállítja a sor minimálisan lehetséges magasságát. Olvasás/írás double.

**Visszatér:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```

Visszaadja vagy beállítja a sor minimálisan lehetséges magasságát. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```

Visszaadja a RowFormat objektumot, amely a sor formázási tulajdonságait tartalmazza. Csak olvasható [IRowFormat](../../com.aspose.slides/irowformat).

**Visszatér:**
[IRowFormat](../../com.aspose.slides/irowformat)