---
title: TableFormat
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt het formaat van een tabel voor.
type: docs
url: /nl/com.aspose.slides/tableformat/
---
**Erfenis:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

Stelt het formaat van een tabel voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Retourneert een object met vul-eigenschappen voor een tabel. |
| [getTransparency()](#getTransparency--) | Geeft of stelt de transparantie van de vulkleur in. |
| [setTransparency(float value)](#setTransparency-float-) | Geeft of stelt de transparantie van de vulkleur in. |
| [getEffective()](#getEffective--) | Haalt de effectieve tabelopmaak-eigenschappen op met overerving en toegepaste tabelstijlen. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Retourneert een object met vul-eigenschappen voor een tabel. Alleen-lezen [IFillFormat](../../com.aspose.slides/ifillformat).

**Retourneert:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```


Geeft of stelt de transparantie van de vulkleur in. Lezen/Schrijven  float .

**Retourneert:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```


Geeft of stelt de transparantie van de vulkleur in. Lezen/Schrijven  float .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final ITableFormatEffectiveData getEffective()
```


Haalt de effectieve tabelopmaak-eigenschappen op met overerving en toegepaste tabelstijlen.

--------------------

> ```
> This example demonstrates getting effective fill format for different table logic parts.
>  Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
>  So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
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


**Retourneert:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - Een [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Versie. Alleen-lezen long.

**Retourneert:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Retourneert de bovenliggende IPresentationComponent. Alleen-lezen [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Retourneert:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)