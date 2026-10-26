---
title: CellFormat
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar formatet för en tabellcell.
type: docs
url: /sv/com.aspose.slides/cellformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.ICellFormat](../../com.aspose.slides/icellformat)
```
public final class CellFormat extends PVIObject implements ICellFormat
```

Representerar formatet för en tabellcell.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillFormat()](#getFillFormat--) | Returnerar ett objekt som representerar cellens fyllningsegenskaper. |
| [getBorderLeft()](#getBorderLeft--) | Returnerar ett objekt för vänster kantlinjeegenskaper. |
| [getBorderTop()](#getBorderTop--) | Returnerar ett objekt för övre kantlinjeegenskaper. |
| [getBorderRight()](#getBorderRight--) | Returnerar ett objekt för höger kantlinjeegenskaper. |
| [getBorderBottom()](#getBorderBottom--) | Returnerar ett objekt för nedre kantlinjeegenskaper. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Returnerar ett objekt för diagonal linje från övre vänster till nedre höger. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Returnerar ett objekt för diagonal linje från nedre vänster till övre högra. |
| [getEffective()](#getEffective--) | Hämtar effektiva formateringsegenskaper för tabellcellen med arv och tabellstilar tillämpade. |
| [getTransparency()](#getTransparency--) | Hämtar eller anger genomskinligheten för fyllningsfärgen. |
| [setTransparency(float value)](#setTransparency-float-) | Hämtar eller anger genomskinligheten för fyllningsfärgen. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Endast läsning long.

**Returnerar:**
long
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Returnerar ett objekt som representerar cellens fyllningsegenskaper. Endast läsning [IFillFormat](../../com.aspose.slides/ifillformat).

**Returnerar:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```

Returnerar ett objekt för vänster kantlinjeegenskaper. Endast läsning [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```

Returnerar ett objekt för övre kantlinjeegenskaper. Endast läsning [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```

Returnerar ett objekt för höger kantlinjeegenskaper. Endast läsning [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```

Returnerar ett objekt för nedre kantlinjeegenskaper. Endast läsning [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```

Returnerar ett objekt för diagonal linje från övre vänster till nedre höger. Endast läsning [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```

Returnerar ett objekt för diagonal linje från nedre vänster till övre högra. Endast läsning [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```

Hämtar effektiva formateringsegenskaper för tabellcellen med arv och tabellstilar tillämpade.

--------------------

> ```
> This example demonstrates getting effective fill format for different table logic parts.
>  Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
>  So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
>  
>  Presentation pres = new Presentation(@"MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (ITable) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).RowFormat.GetEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returnerar:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - En [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

Hämtar eller anger genomskinligheten för fyllningsfärgen. Läs/skriv  float .

**Returnerar:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

Hämtar eller anger genomskinligheten för fyllningsfärgen. Läs/skriv  float .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |