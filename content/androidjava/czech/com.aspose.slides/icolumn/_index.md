---
title: IColumn
second_title: Aspose.Slides pro Android pomocí Java API
description: Reprezentuje sloupec v tabulce.
type: docs
url: /cs/com.aspose.slides/icolumn/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

Reprezentuje sloupec v tabulce.
## Metody

| Method | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Vrací nebo nastavuje šířku sloupce. |
| [setWidth(double value)](#setWidth-double-) | Vrací nebo nastavuje šířku sloupce. |
| [getColumnFormat()](#getColumnFormat--) | Vrací objekt ColumnFormat, který obsahuje vlastnosti formátování pro tento sloupec. |
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Vrací nebo nastavuje šířku sloupce. Read/write double.

**Vrací:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

Vrací nebo nastavuje šířku sloupce. Read/write double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```

Vrací objekt ColumnFormat, který obsahuje vlastnosti formátování pro tento sloupec. Read-only [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Vrací:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)