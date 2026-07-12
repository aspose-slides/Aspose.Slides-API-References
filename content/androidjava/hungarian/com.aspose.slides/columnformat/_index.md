---
title: ColumnFormat
second_title: Aspose.Slides Androidra a Java API hivatkozással
description: A táblázat oszlopának formátumát képviseli.
type: docs
url: /hu/com.aspose.slides/columnformat/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Az összes megvalósított interfész:**
[com.aspose.slides.IColumnFormat](../../com.aspose.slides/icolumnformat), com.aspose.slides.IPVIObject
```
public final class ColumnFormat extends DomObject<Column> implements IColumnFormat, IPVIObject
```

A táblázat oszlopának formátumát képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getEffective()](#getEffective--) | Lekéri a hatékony táblázatoszlop formázási tulajdonságait öröklődéssel és a táblázat stílusainak alkalmazásával. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IColumnFormatEffectiveData getEffective()
```


Lekéri a hatékony táblázatoszlop formázási tulajdonságait öröklődéssel és a táblázat stílusainak alkalmazásával.

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


**Visszatér:**
[IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata) - egy [IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Verzió. Csak olvasható long.

**Visszatér:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Visszatér a szülő IPresentationComponent. Csak olvasható [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Visszatér:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)