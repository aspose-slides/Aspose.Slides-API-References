---
title: ColumnFormat
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje formát sloupce tabulky.
type: docs
url: /cs/com.aspose.slides/columnformat/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.IColumnFormat](../../com.aspose.slides/icolumnformat), com.aspose.slides.IPVIObject
```
public final class ColumnFormat extends DomObject<Column> implements IColumnFormat, IPVIObject
```

Reprezentuje formát sloupce tabulky.
## Metody

| Method | Description |
| --- | --- |
| [getEffective()](#getEffective--) | Získá efektivní vlastnosti formátování sloupce tabulky s aplikovaným děděním a styly tabulky. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IColumnFormatEffectiveData getEffective()
```

Získá efektivní vlastnosti formátování sloupce tabulky s aplikovaným děděním a styly tabulky.

--------------------

> ```
> Tento příklad ukazuje získání efektivního formátu výplně pro různé logické části tabulky.
>  Všimněte si, že formátování buněk má vždy vyšší prioritu než formátování řádků, řádek - vyšší než sloupec, sloupec - vyšší než celá tabulka.
>  Takže nakonec jsou vlastnosti CellFormatEffectiveData vždy použity k vykreslení tabulky. Následující kód je jen příklad API.
>  
>  Presentation pres = new Presentation(@"MyPresentation.pptx");
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
[IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata) - a [IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Verze. Pouze ke čtení long.

**Vrací:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Vrací nadřazený IPresentationComponent. Pouze ke čtení [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Vrací:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)