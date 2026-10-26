---
title: IRow
second_title: Aspose.Slides för Java API-referens
description: Representerar en rad i en tabell.
type: docs
url: /sv/com.aspose.slides/irow/
---
**All Implemented Interfaces:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

Representerar en rad i en tabell.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getHeight()](#getHeight--) | Returnerar radens höjd. |
| [getMinimalHeight()](#getMinimalHeight--) | Returnerar eller anger den minsta möjliga höjden för en rad. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Returnerar eller anger den minsta möjliga höjden för en rad. |
| [getRowFormat()](#getRowFormat--) | Returnerar RowFormat-objektet som innehåller formateringsegenskaper för denna rad. |
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Returnerar radens höjd. Skrivskyddad double.

**Returnerar:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```


Returnerar eller anger den minsta möjliga höjden för en rad. Läs/skriv double.

**Returnerar:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```


Returnerar eller anger den minsta möjliga höjden för en rad. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```


Returnerar RowFormat-objektet som innehåller formateringsegenskaper för denna rad. Skrivskyddad [IRowFormat](../../com.aspose.slides/irowformat).

**Returnerar:**
[IRowFormat](../../com.aspose.slides/irowformat)