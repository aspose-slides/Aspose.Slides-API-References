---
title: IColumn
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en kolumn i en tabell.
type: docs
url: /sv/com.aspose.slides/icolumn/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

Representerar en kolumn i en tabell.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getWidth()](#getWidth--) | Returnerar eller anger bredden på en kolumn. |
| [setWidth(double value)](#setWidth-double-) | Returnerar eller anger bredden på en kolumn. |
| [getColumnFormat()](#getColumnFormat--) | Returnerar ColumnFormat-objektet som innehåller formateringsegenskaper för denna kolumn. |
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Returnerar eller anger bredden på en kolumn. Läs/skriv double.

**Returnerar:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```


Returnerar eller anger bredden på en kolumn. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```


Returnerar ColumnFormat-objektet som innehåller formateringsegenskaper för denna kolumn. Skrivskyddad [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Returnerar:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)