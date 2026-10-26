---
title: CellFormat
second_title: Aspose.Slides pro Android přes referenci Java API
description: Reprezentuje formát buňky tabulky.
type: docs
url: /cs/com.aspose.slides/cellformat/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Všechny implementované rozhraní:**
[com.aspose.slides.ICellFormat](../../com.aspose.slides/icellformat)
```
public final class CellFormat extends PVIObject implements ICellFormat
```

Reprezentuje formát buňky tabulky.
## Metody

| Metoda | Popis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillFormat()](#getFillFormat--) | Vrací objekt vlastností výplně buňky. |
| [getBorderLeft()](#getBorderLeft--) | Vrací objekt vlastností levé čáry okraje. |
| [getBorderTop()](#getBorderTop--) | Vrací objekt vlastností horní čáry okraje. |
| [getBorderRight()](#getBorderRight--) | Vrací objekt vlastností pravé čáry okraje. |
| [getBorderBottom()](#getBorderBottom--) | Vrací objekt vlastností spodní čáry okraje. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Vrací objekt vlastností úhlopříčky zleva nahoře doprava dolů. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Vrací objekt vlastností úhlopříčky ze spodního levého rohu do pravého horního. |
| [getEffective()](#getEffective--) | Získá efektivní vlastnosti formátování buňky tabulky s aplikovanou dědičností a styly tabulky. |
| [getTransparency()](#getTransparency--) | Získá nebo nastaví průhlednost barvy výplně. |
| [setTransparency(float value)](#setTransparency-float-) | Získá nebo nastaví průhlednost barvy výplně. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verze. Pouze pro čtení long.

**Vrací:**
long
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Vrací objekt vlastností výplně buňky. Pouze pro čtení [IFillFormat](../../com.aspose.slides/ifillformat).

**Vrací:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```

Vrací objekt vlastností levé čáry okraje. Pouze pro čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```

Vrací objekt vlastností horní čáry okraje. Pouze pro čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```

Vrací objekt vlastností pravé čáry okraje. Pouze pro čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```

Vrací objekt vlastností spodní čáry okraje. Pouze pro čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```

Vrací objekt vlastností úhlopříčky zleva nahoře doprava dolů. Pouze pro čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```

Vrací objekt vlastností úhlopříčky ze spodního levého rohu do pravého horního. Pouze pro čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```

Získá efektivní vlastnosti formátování buňky tabulky s aplikovanou dědičností a styly tabulky.

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


**Vrací:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

Získá nebo nastaví průhlednost barvy výplně. Čtení/zápis float .

**Vrací:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

Získá nebo nastaví průhlednost barvy výplně. Čtení/zápis float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |