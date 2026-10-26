---
title: IColumn
second_title: Aspose.Slides pro Java API – reference
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

| Metoda | Popis |
| --- | --- |
| [getWidth()](#getWidth--) | Vrací nebo nastavuje šířku sloupce. |
| [setWidth(double value)](#setWidth-double-) | Vrací nebo nastavuje šířku sloupce. |
| [getColumnFormat()](#getColumnFormat--) | Vrací objekt ColumnFormat, který obsahuje vlastnosti formátování pro tento sloupec. |
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Vrací nebo nastavuje šířku sloupce. Čtení/zápis double.

**Vrací:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```


Vrací nebo nastavuje šířku sloupce. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```


Vrací objekt ColumnFormat, který obsahuje vlastnosti formátování pro tento sloupec. Pouze ke čtení [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Vrací:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)