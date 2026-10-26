---
title: CellFormat
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt het formaat van een tabelcel voor.
type: docs
url: /nl/com.aspose.slides/cellformat/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ICellFormat](../../com.aspose.slides/icellformat)
```
public final class CellFormat extends PVIObject implements ICellFormat
```

Stelt het formaat van een tabelcel voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillFormat()](#getFillFormat--) | Retourneert een object met celvullings eigenschappen. |
| [getBorderLeft()](#getBorderLeft--) | Retourneert een object met eigenschappen van een linker randlijn. |
| [getBorderTop()](#getBorderTop--) | Retourneert een object met eigenschappen van een bovenrandlijn. |
| [getBorderRight()](#getBorderRight--) | Retourneert een object met eigenschappen van een rechter randlijn. |
| [getBorderBottom()](#getBorderBottom--) | Retourneert een object met eigenschappen van een onderste randlijn. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Retourneert een object met eigenschappen van een diagonale lijn van linksboven naar rechtsonder. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Retourneert een object met eigenschappen van een diagonale lijn van linksonder naar rechtsboven. |
| [getEffective()](#getEffective--) | Haalt effectieve opmaak-eigenschappen van een tabelcel op met overerving en toegepaste tabelstijlen. |
| [getTransparency()](#getTransparency--) | Haalt de transparantie van de vulkleur op of stelt deze in. |
| [setTransparency(float value)](#setTransparency-float-) | Haalt de transparantie van de vulkleur op of stelt deze in. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versie. Alleen-lezen long.

**Returns:**
long
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Retourneert een object met celvullings eigenschappen. Alleen-lezen [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```


Retourneert een object met eigenschappen van een linker randlijn. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```


Retourneert een object met eigenschappen van een bovenrandlijn. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```


Retourneert een object met eigenschappen van een rechter randlijn. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```


Retourneert een object met eigenschappen van een onderste randlijn. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```


Retourneert een object met eigenschappen van een diagonale lijn van linksboven naar rechtsonder. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```


Retourneert een object met eigenschappen van een diagonale lijn van linksonder naar rechtsboven. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```


Haalt effectieve opmaak-eigenschappen van een tabelcel op met overerving en toegepaste tabelstijlen.

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


**Returns:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```


Haalt de transparantie van de vulkleur op of stelt deze in. Lezen/schrijven  float .

**Returns:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```


Haalt de transparantie van de vulkleur op of stelt deze in. Lezen/schrijven  float .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |