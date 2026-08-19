---
title: Row
second_title: Aspose.Slides för Java API-referens
description: Representerar en rad i en tabell.
type: docs
url: /sv/com.aspose.slides/row/
---
**Arv:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IRow](../../com.aspose.slides/irow)
```
public final class Row extends CellCollection implements IRow
```

Representerar en rad i en tabell.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getHeight()](#getHeight--) | Returnerar höjden på en rad. |
| [getMinimalHeight()](#getMinimalHeight--) | Returnerar eller anger den minsta möjliga höjden på en rad. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Returnerar eller anger den minsta möjliga höjden på en rad. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Ställer in definierade portionsformat egenskaper för alla radcellers portioner. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Ställer in definierade styckeformat egenskaper för alla radcellers stycken. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Ställer in definierade textramformat egenskaper för alla radcellers textramar. |
| [getRowFormat()](#getRowFormat--) | Returnerar RowFormat-objektet som innehåller formateringsegenskaper för denna rad. |
### getHeight() {#getHeight--}
```
public final double getHeight()
```


Returnerar höjden på en rad. Skrivskyddad double.

**Returnerar:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```


Returnerar eller anger den minsta möjliga höjden på en rad. Läs/skriv double.

**Returnerar:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```


Returnerar eller anger den minsta möjliga höjden på en rad. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


Ställer in definierade portionsformat egenskaper för alla radcellers portioner.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat-objekt med nödvändiga egenskaper inställda. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


Ställer in definierade styckeformat egenskaper för alla radcellers stycken.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat-objekt med nödvändiga egenskaper inställda. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```


Ställer in definierade textramformat egenskaper för alla radcellers textramar.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat-objekt med nödvändiga egenskaper inställda. |

### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```


Returnerar RowFormat-objektet som innehåller formateringsegenskaper för denna rad. Skrivskyddad [IRowFormat](../../com.aspose.slides/irowformat).

**Returnerar:**
[IRowFormat](../../com.aspose.slides/irowformat)