---
title: RowFormat
second_title: Aspose.Slides pro Android pomocí Java API
description: Představuje formát řádku tabulky.
type: docs
url: /cs/com.aspose.slides/rowformat/
---
**Dědičnost:**  
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**  
[com.aspose.slides.IRowFormat](../../com.aspose.slides/irowformat), com.aspose.slides.IPVIObject  
```
public final class RowFormat extends DomObject<Row> implements IRowFormat, IPVIObject
```

Představuje formát řádku tabulky.

## Metody

| Metoda | Popis |
| --- | --- |
| [getEffective()](#getEffective--) | Získá efektivní vlastnosti formátování řádku tabulky s aplikovaným děděním a styly tabulky. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |

### getEffective() {#getEffective--}
```
public final IRowFormatEffectiveData getEffective()
```

Získá efektivní vlastnosti formátování řádku tabulky s aplikovaným děděním a styly tabulky.

--------------------

> ```
> Tento příklad ukazuje získání efektivního formátu výplně pro různé logické části tabulky.
>  Upozorňujeme, že formátování buněk má vždy vyšší prioritu než formátování řádků, řádky mají vyšší prioritu než sloupce, sloupce mají vyšší prioritu než celá tabulka.
>  Nakonec jsou vlastnosti CellFormatEffectiveData vždy použity pro vykreslení tabulky. Následující kód je jen příklad API.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (ITable)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).getRowFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
```

**Vrací:**  
[IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata) - A [IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata).

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