---
title: Column
second_title: Aspose.Slides för Java API-referens
description: Representerar en kolumn i en tabell.
type: docs
url: /sv/com.aspose.slides/column/
---
**Arv:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)
```
public final class Column extends CellCollection implements IColumn
```

Representerar en kolumn i en tabell.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getWidth()](#getWidth--) | Returnerar eller anger bredden på en kolumn. |
| [setWidth(double value)](#setWidth-double-) | Returnerar eller anger bredden på en kolumn. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Ställer in definierade formategenskaper för delarna på alla kolumnceller. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Ställer in definierade formategenskaper för stycken på alla kolumnceller. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Ställer in definierade formategenskaper för textramar på alla kolumnceller. |
| [getColumnFormat()](#getColumnFormat--) | Returnerar ColumnFormat-objektet som innehåller formateringsegenskaper för denna kolumn. |
### getWidth() {#getWidth--}
```
public final double getWidth()
```


Returnerar eller anger bredden på en kolumn. Läs/skriv double.

**Returnerar:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Returnerar eller anger bredden på en kolumn. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


Ställer in definierade formategenskaper för delarna på alla kolumnceller.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat-objekt med nödvändiga egenskaper inställda. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


Ställer in definierade formategenskaper för stycken på alla kolumnceller.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat-objekt med nödvändiga egenskaper inställda. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```


Ställer in definierade formategenskaper för textramar på alla kolumnceller.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat-objekt med nödvändiga egenskaper inställda. |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```


Returnerar ColumnFormat-objektet som innehåller formateringsegenskaper för denna kolumn. Endast läs [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Returnerar:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)