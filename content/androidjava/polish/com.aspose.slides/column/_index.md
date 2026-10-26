---
title: Column
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Reprezentuje kolumnę w tabeli.
type: docs
url: /pl/com.aspose.slides/column/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)
```
public final class Column extends CellCollection implements IColumn
```

Reprezentuje kolumnę w tabeli.
## Metody

| Metoda | Opis |
| --- | --- |
| [getWidth()](#getWidth--) | Zwraca lub ustawia szerokość kolumny. |
| [setWidth(double value)](#setWidth-double-) | Zwraca lub ustawia szerokość kolumny. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Ustawia zdefiniowane właściwości formatu części na wszystkich częściach komórek kolumny. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Ustawia zdefiniowane właściwości formatu akapitu na wszystkich akapitach komórek kolumny. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Ustawia zdefiniowane właściwości formatu ramki tekstowej na wszystkich ramkach tekstowych komórek kolumny. |
| [getColumnFormat()](#getColumnFormat--) | Zwraca obiekt ColumnFormat, który zawiera właściwości formatowania dla tej kolumny. |
### getWidth() {#getWidth--}
```
public final double getWidth()
```


Zwraca lub ustawia szerokość kolumny. Odczyt/zapis double.

**Zwraca:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Zwraca lub ustawia szerokość kolumny. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


Ustawia zdefiniowane właściwości formatu części na wszystkich częściach komórek kolumny.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | Obiekt IPortionFormat z ustawionymi niezbędnymi właściwościami. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


Ustawia zdefiniowane właściwości formatu akapitu na wszystkich akapitach komórek kolumny.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | Obiekt IParagraphFormat z ustawionymi niezbędnymi właściwościami. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```


Ustawia zdefiniowane właściwości formatu ramki tekstowej na wszystkich ramkach tekstowych komórek kolumny.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | Obiekt ITextFrameFormat z ustawionymi niezbędnymi właściwościami. |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```


Zwraca obiekt ColumnFormat, który zawiera właściwości formatowania dla tej kolumny. Tylko do odczytu [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Zwraca:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)