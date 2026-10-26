---
title: IRow
second_title: Aspose.Slides dla Androida za pośrednictwem dokumentacji interfejsu Java API
description: Reprezentuje wiersz w tabeli.
type: docs
url: /pl/com.aspose.slides/irow/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

Reprezentuje wiersz w tabeli.
## Metody

| Method | Description |
| --- | --- |
| [getHeight()](#getHeight--) | Zwraca wysokość wiersza. |
| [getMinimalHeight()](#getMinimalHeight--) | Zwraca lub ustawia minimalną możliwą wysokość wiersza. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Zwraca lub ustawia minimalną możliwą wysokość wiersza. |
| [getRowFormat()](#getRowFormat--) | Zwraca obiekt RowFormat, który zawiera właściwości formatowania tego wiersza. |

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

Zwraca wysokość wiersza. Tylko do odczytu double.

**Zwraca:**
double

### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

Zwraca lub ustawia minimalną możliwą wysokość wiersza. Do odczytu i zapisu double.

**Zwraca:**
double

### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```

Zwraca lub ustawia minimalną możliwą wysokość wiersza. Do odczytu i zapisu double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```

Zwraca obiekt RowFormat, który zawiera właściwości formatowania tego wiersza. Tylko do odczytu [IRowFormat](../../com.aspose.slides/irowformat).

**Zwraca:**
[IRowFormat](../../com.aspose.slides/irowformat)