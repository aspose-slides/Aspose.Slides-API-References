---
title: TableFormat
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar formatet för en tabell.
type: docs
url: /sv/com.aspose.slides/tableformat/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

Representerar formatet för en tabell.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Returnerar ett tabellfyllnadsobjekt. |
| [getTransparency()](#getTransparency--) | Hämtar eller anger genomskinligheten för fyllningsfärgen. |
| [setTransparency(float value)](#setTransparency-float-) | Hämtar eller anger genomskinligheten för fyllningsfärgen. |
| [getEffective()](#getEffective--) | Hämtar effektiva tabellformateringsegenskaper med arv och tabellstilar tillämpade. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Returnerar ett tabellfyllnadsobjekt. Skrivskyddad [IFillFormat](../../com.aspose.slides/ifillformat).

**Returnerar:**
[IFillFormat](../../com.aspose.slides/ifillformat)
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

### getEffective() {#getEffective--}
```
public final ITableFormatEffectiveData getEffective()
```

Hämtar effektiva tabellformateringsegenskaper med arv och tabellstilar tillämpade.

--------------------

> ```
> Detta exempel visar hur man hämtar effektiv fyllnadsformat för olika tabellens logiska delar.
>  Observera att cellformatering alltid har högre prioritet än radformatering, rad - högre än kolumn, kolumn - högre än hela tabellen.
>  Så i slutändan används CellFormatEffectiveData-egenskaperna alltid för att rita tabellen. Följande kod är bara ett exempel på API.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (Table)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).getRowFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returnerar:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - En [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Version. Skrivskyddad long.

**Returnerar:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Returnerar föräldern IPresentationComponent. Skrivskyddad [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Returnerar:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)