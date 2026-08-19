---
title: CellFormat
second_title: Aspose.Slides för Java API-referens
description: Representerar formatet för en tabellcell.
type: docs
url: /sv/com.aspose.slides/cellformat/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alla implementerade gränssnitt:**
[com.aspose.slides.ICellFormat](../../com.aspose.slides/icellformat)
```
public final class CellFormat extends PVIObject implements ICellFormat
```

Representerar formatet för en tabellcell.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillFormat()](#getFillFormat--) | Returnerar ett objekt för cellens fyllningsegenskaper. |
| [getBorderLeft()](#getBorderLeft--) | Returnerar ett objekt för vänster kantlinje. |
| [getBorderTop()](#getBorderTop--) | Returnerar ett objekt för övre kantlinje. |
| [getBorderRight()](#getBorderRight--) | Returnerar ett objekt för högre kantlinje. |
| [getBorderBottom()](#getBorderBottom--) | Returnerar ett objekt för nedre kantlinje. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Returnerar ett objekt för diagonal linje från övre vänster till nedre höger. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Returnerar ett objekt för diagonal linje från nedre vänster till övre höger. |
| [getEffective()](#getEffective--) | Hämtar effektiva formateringsegenskaper för en tabellcell med arv och tillämpade tabellstilar. |
| [getTransparency()](#getTransparency--) | Hämtar eller anger transparensen för fyllningsfärgen. |
| [setTransparency(float value)](#setTransparency-float-) | Hämtar eller anger transparensen för fyllningsfärgen. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Skrivskyddad long.

**Returnerar:**
long
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Returnerar ett objekt för cellens fyllningsegenskaper. Skrivskyddad [IFillFormat](../../com.aspose.slides/ifillformat).

**Returnerar:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```


Returnerar ett objekt för vänster kantlinje. Skrivskyddad [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```


Returnerar ett objekt för övre kantlinje. Skrivskyddad [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```


Returnerar ett objekt för högre kantlinje. Skrivskyddad [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```


Returnerar ett objekt för nedre kantlinje. Skrivskyddad [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```


Returnerar ett objekt för diagonal linje från övre vänster till nedre höger. Skrivskyddad [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```


Returnerar ett objekt för diagonal linje från nedre vänster till övre höger. Skrivskyddad [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```


Hämtar effektiva formateringsegenskaper för en tabellcell med arv och tillämpade tabellstilar.

--------------------

> ```
> Detta exempel visar hur man får den effektiva fyllnadsformatet för olika tabelllogikdelar.
>  Observera att cellformatering alltid har högre prioritet än radformatering, rad - högre än kolumn, kolumn - högre än hela tabellen.
>  Så slutligen används alltid CellFormatEffectiveData-egenskaper för att rita tabellen. Följande kod är bara ett exempel på API.
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


Hämtar eller anger transparensen för fyllningsfärgen. Läs/skriv float .

**Returnerar:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```


Hämtar eller anger transparensen för fyllningsfärgen. Läs/skriv float .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |