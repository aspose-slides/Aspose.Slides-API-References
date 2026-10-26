---
title: RowFormat
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje formát řádku tabulky.
type: docs
url: /cs/com.aspose.slides/rowformat/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IRowFormat](../../com.aspose.slides/irowformat), com.aspose.slides.IPVIObject
```
public final class RowFormat extends DomObject<Row> implements IRowFormat, IPVIObject
```

Představuje formát řádku tabulky.
## Metody

| Metoda | Popis |
| --- | --- |
| [getEffective()](#getEffective--) | Získá účinné vlastnosti formátování řádku tabulky s aplikovaným děděním a styly tabulky. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IRowFormatEffectiveData getEffective()
```


Získá účinné vlastnosti formátování řádku tabulky s aplikovaným děděním a styly tabulky.

--------------------

> ```
> Tento příklad ukazuje získání efektivního formátu výplně pro různé části logiky tabulky.
>  Všimněte si, že formátování buňky má vždy vyšší prioritu než formátování řádku, řádek – vyšší než sloupec, sloupec – vyšší než celá tabulka.
>  Takže nakonec jsou vlastnosti CellFormatEffectiveData vždy použity k vykreslení tabulky. Následující kód je pouze příkladem API.
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
> ```


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


Vrací nadřazené IPresentationComponent. Pouze pro čtení [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Vrací:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)