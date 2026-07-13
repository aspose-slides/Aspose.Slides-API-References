---
title: TableFormat
second_title: Aspose.Slides pro Android pomocí reference Java API
description: Reprezentuje formát tabulky.
type: docs
url: /cs/com.aspose.slides/tableformat/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

Reprezentuje formát tabulky.
## Metody

| Metoda | Popis |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Vrátí objekt vlastností výplně tabulky. |
| [getTransparency()](#getTransparency--) | Získává nebo nastavuje průhlednost barvy výplně. |
| [setTransparency(float value)](#setTransparency-float-) | Získává nebo nastavuje průhlednost barvy výplně. |
| [getEffective()](#getEffective--) | Získává efektivní vlastnosti formátování tabulky s dědičností a aplikovanými styly tabulky. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Vrátí objekt vlastností výplně tabulky. Pouze pro čtení [IFillFormat](../../com.aspose.slides/ifillformat).

**Vrací:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```


Získává nebo nastavuje průhlednost barvy výplně. Čtení/zápis  float .

**Vrací:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```


Získává nebo nastavuje průhlednost barvy výplně. Čtení/zápis  float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final ITableFormatEffectiveData getEffective()
```


Získává efektivní vlastnosti formátování tabulky s dědičností a aplikovanými styly tabulky.

--------------------

> ```
> Tento příklad ukazuje získání efektivního formátu výplně pro různé logické části tabulky.
>  Upozorňujeme, že formátování buňky má vždy vyšší prioritu než formátování řádku, řádek - vyšší než sloupec, sloupec - vyšší než celá tabulka.
>  Nakonec se vždy používají vlastnosti CellFormatEffectiveData k vykreslení tabulky. Následující kód je pouze příkladem API.
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


**Vrací:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - a [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Verze. Pouze pro čtení long.

**Vrací:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Vrací nadřazený IPresentationComponent. Pouze pro čtení [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Vrací:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)