---
title: IColumn
second_title: Aspose.Slides för Java API-referens
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
| [getWidth()](#getWidth--) | Returnerar eller sätter bredden på en kolumn. |
| [setWidth(double value)](#setWidth-double-) | Returnerar eller sätter bredden på en kolumn. |
| [getColumnFormat()](#getColumnFormat--) | Returnerar ColumnFormat-objektet som innehåller formateringsinställningar för den här kolumnen. |
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Returnerar eller sätter bredden på en kolumn. Läs/skriv double.

**Returnerar:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```


Returnerar eller sätter bredden på en kolumn. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```


Returnerar ColumnFormat-objektet som innehåller formateringsinställningar för den här kolumnen. Läs endast [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Returnerar:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)