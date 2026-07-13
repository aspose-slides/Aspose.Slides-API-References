---
title: IRow
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en rad i en tabell.
type: docs
url: /sv/com.aspose.slides/irow/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

Representerar en rad i en tabell.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getHeight()](#getHeight--) | Returnerar höjden på en rad. |
| [getMinimalHeight()](#getMinimalHeight--) | Returnerar eller anger den minsta möjliga höjden på en rad. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Returnerar eller anger den minsta möjliga höjden på en rad. |
| [getRowFormat()](#getRowFormat--) | Returnerar RowFormat-objektet som innehåller formateringsegenskaper för den här raden. |
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

Returnerar höjden på en rad. Skrivskyddad double.

**Returnerar:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

Returnerar eller anger den minsta möjliga höjden på en rad. Läs/skriv double.

**Returnerar:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```

Returnerar eller anger den minsta möjliga höjden på en rad. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```

Returnerar RowFormat-objektet som innehåller formateringsegenskaper för den här raden. Skrivskyddad [IRowFormat](../../com.aspose.slides/irowformat).

**Returnerar:**
[IRowFormat](../../com.aspose.slides/irowformat)