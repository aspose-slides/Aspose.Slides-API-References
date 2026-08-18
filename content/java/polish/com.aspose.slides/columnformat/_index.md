---
title: ColumnFormat
second_title: Aspose.Slides dla Java API Reference
description: Reprezentuje format kolumny tabeli.
type: docs
url: /pl/com.aspose.slides/columnformat/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IColumnFormat](../../com.aspose.slides/icolumnformat), com.aspose.slides.IPVIObject
```
public final class ColumnFormat extends DomObject<Column> implements IColumnFormat, IPVIObject
```

Reprezentuje format kolumny tabeli.
## Metody

| Metoda | Opis |
| --- | --- |
| [getEffective()](#getEffective--) | Pobiera efektywne właściwości formatowania kolumny tabeli z uwzględnieniem dziedziczenia i zastosowanych stylów tabeli. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IColumnFormatEffectiveData getEffective()
```

Pobiera efektywne właściwości formatowania kolumny tabeli z uwzględnieniem dziedziczenia i zastosowanych stylów tabeli.

--------------------

> ```
> This example demonstrates getting effective fill format for different table logic parts.
>  Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
>  So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
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


**Zwraca:**
[IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata) - A [IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Wersja. Tylko do odczytu long.

**Zwraca:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Zwraca rodzica IPresentationComponent. Tylko do odczytu [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Zwraca:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)