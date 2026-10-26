---
title: IColumn
second_title: Aspose.Slides dla Java - odniesienie API
description: Reprezentuje kolumnę w tabeli.
type: docs
url: /pl/com.aspose.slides/icolumn/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

Represents a column in a table.
## Metody

| Metoda | Opis |
| --- | --- |
| [getWidth()](#getWidth--) | Zwraca lub ustawia szerokość kolumny. |
| [setWidth(double value)](#setWidth-double-) | Zwraca lub ustawia szerokość kolumny. |
| [getColumnFormat()](#getColumnFormat--) | Zwraca obiekt ColumnFormat, który zawiera właściwości formatowania tej kolumny. |
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Zwraca lub ustawia szerokość kolumny. Odczyt/zapis double.

**Zwraca:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

Zwraca lub ustawia szerokość kolumny. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |
### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```

Zwraca obiekt ColumnFormat, który zawiera właściwości formatowania tej kolumny. Tylko do odczytu [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Zwraca:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)