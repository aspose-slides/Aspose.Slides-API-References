---
title: IColumn
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt eine Spalte in einer Tabelle dar.
type: docs
url: /de/com.aspose.slides/icolumn/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

Stellt eine Spalte in einer Tabelle dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getWidth()](#getWidth--) | Liefert oder legt die Breite einer Spalte fest. |
| [setWidth(double value)](#setWidth-double-) | Liefert oder legt die Breite einer Spalte fest. |
| [getColumnFormat()](#getColumnFormat--) | Liefert das ColumnFormat-Objekt, das die Formatierungseigenschaften für diese Spalte enthält. |
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Liefert oder legt die Breite einer Spalte fest. Lese-/Schreib double.

**Rückgabe:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

Liefert oder legt die Breite einer Spalte fest. Lese-/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```

Liefert das ColumnFormat-Objekt, das die Formatierungseigenschaften für diese Spalte enthält. Nur lesbar [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Rückgabe:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)