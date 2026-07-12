---
title: RowFormat
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt das Format einer Tabellenzeile dar.
type: docs
url: /de/com.aspose.slides/rowformat/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IRowFormat](../../com.aspose.slides/irowformat), com.aspose.slides.IPVIObject
```
public final class RowFormat extends DomObject<Row> implements IRowFormat, IPVIObject
```

Stellt das Format einer Tabellenzeile dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEffective()](#getEffective--) | Ruft die effektiven Tabellenzeilenformatierungs-Eigenschaften mit Vererbung und angewendeten Tabellenstilen ab. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IRowFormatEffectiveData getEffective()
```


Ruft die effektiven Tabellenzeilenformatierungs-Eigenschaften mit Vererbung und angewendeten Tabellenstilen ab.

--------------------

> ```
> This example demonstrates getting effective fill format for different table logic parts.
>  Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
>  So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
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


**Rückgabewert:**
[IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata) - Ein [IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Version. Nur-Lese long.

**Rückgabewert:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Rückgibt übergeordnetes IPresentationComponent. Nur-Lese [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Rückgabewert:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)