---
title: CellFormat
second_title: Aspose.Slides pro Java API Reference
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
| [getBorderLeft()](#getBorderLeft--) | Vrací objekt vlastností levého okraje čáry. |
| [getBorderTop()](#getBorderTop--) | Vrací objekt vlastností horního okraje čáry. |
| [getBorderRight()](#getBorderRight--) | Vrací objekt vlastností pravého okraje čáry. |
| [getBorderBottom()](#getBorderBottom--) | Vrací objekt vlastností spodního okraje čáry. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Vrací objekt vlastností úhlopříčky zleva nahoře do pravého dole. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Vrací objekt vlastností úhlopříčky zleva dole do pravého nahoře. |
| [getEffective()](#getEffective--) | Získává účinné vlastnosti formátování buňky tabulky s dědičností a aplikovanými styly tabulky. |
| [getTransparency()](#getTransparency--) | Získává nebo nastavuje průhlednost barvy výplně. |
| [setTransparency(float value)](#setTransparency-float-) | Získává nebo nastavuje průhlednost barvy výplně. |
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

Vrací objekt vlastností levého okraje čáry. Pouze pro čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```

Vrací objekt vlastností horního okraje čáry. Pouze pro čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```

Vrací objekt vlastností pravého okraje čáry. Pouze pro čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```

Vrací objekt vlastností spodního okraje čáry. Pouze pro čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```

Vrací objekt vlastností úhlopříčky zleva nahoře do pravého dole. Pouze pro čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```

Vrací objekt vlastností úhlopříčky zleva dole do pravého nahoře. Pouze pro čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```

Získává účinné vlastnosti formátování buňky tabulky s dědičností a aplikovanými styly tabulky.

--------------------

> ```
> Tento příklad ukazuje, jak získat účinný formát výplně pro různé logické části tabulky.
>  Všimněte si, že formátování buňky má vždy vyšší prioritu než formátování řádku, řádek - vyšší než sloupec, sloupec - vyšší než celá tabulka.
>  Takže nakonec jsou vlastnosti CellFormatEffectiveData vždy použity k vykreslení tabulky. Následující kód je jen příklad API.
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
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) – A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

Získává nebo nastavuje průhlednost barvy výplně. Čtení a zápis float .

**Vrací:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

Získává nebo nastavuje průhlednost barvy výplně. Čtení a zápis float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |