---
title: CellFormat
second_title: Aspose.Slides voor Java API-referentie
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
| [getFillFormat()](#getFillFormat--) | Retourneert een celvullings-eigenschappen object. |
| [getBorderLeft()](#getBorderLeft--) | Retourneert een linker randlijn-eigenschappen object. |
| [getBorderTop()](#getBorderTop--) | Retourneert een bovenste randlijn-eigenschappen object. |
| [getBorderRight()](#getBorderRight--) | Retourneert een rechter randlijn-eigenschappen object. |
| [getBorderBottom()](#getBorderBottom--) | Retourneert een onderste randlijn-eigenschappen object. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Retourneert een diagonaal van links-boven naar rechts-onder lijn-eigenschappen object. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Retourneert een diagonaal van links-onder naar rechts-boven lijn-eigenschappen object. |
| [getEffective()](#getEffective--) | Haalt effectieve tabelcel-opmaak-eigenschappen op met overerving en toegepaste tabelstijlen. |
| [getTransparency()](#getTransparency--) | Haalt de transparantie van de vulkleur op of stelt deze in. |
| [setTransparency(float value)](#setTransparency-float-) | Haalt de transparantie van de vulkleur op of stelt deze in. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versie. Alleen-lezen long.

**Retour:**
long
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Retourneert een celvullings-eigenschappen object. Alleen-lezen [IFillFormat](../../com.aspose.slides/ifillformat).

**Retour:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```


Retourneert een linker randlijn-eigenschappen object. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Retour:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```


Retourneert een bovenste randlijn-eigenschappen object. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Retour:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```


Retourneert een rechter randlijn-eigenschappen object. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Retour:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```


Retourneert een onderste randlijn-eigenschappen object. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Retour:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```


Retourneert een diagonaal van links-boven naar rechts-onder lijn-eigenschappen object. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Retour:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```


Retourneert een diagonaal van links-onder naar rechts-boven lijn-eigenschappen object. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Retour:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```


Haalt effectieve tabelcel-opmaak-eigenschappen op met overerving en toegepaste tabelstijlen.

--------------------

> ```
> Dit voorbeeld laat zien hoe je het effectieve invulformaat verkrijgt voor verschillende logische delen van een tabel.
>  Houd er rekening mee dat celopmaak altijd een hogere prioriteit heeft dan rijopmaak, rij - hoger dan kolom, kolom - hoger dan de hele tabel.
>  Dus uiteindelijk worden de eigenschappen van CellFormatEffectiveData altijd gebruikt om de tabel te tekenen. De volgende code is slechts een voorbeeld van de API.
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


**Retour:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - Een [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```


Haalt de transparantie van de vulkleur op of stelt deze in. Lezen/schrijven  float .

**Retour:**
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