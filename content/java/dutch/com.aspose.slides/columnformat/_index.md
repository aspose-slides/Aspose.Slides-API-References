---
title: ColumnFormat
second_title: Aspose.Slides voor Java API-referentie
description: Stelt het formaat van een tabelkolom voor.
type: docs
url: /nl/com.aspose.slides/columnformat/
---
**Erfenis:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IColumnFormat](../../com.aspose.slides/icolumnformat), com.aspose.slides.IPVIObject
```
public final class ColumnFormat extends DomObject<Column> implements IColumnFormat, IPVIObject
```

Stelt het formaat van een tabelkolom voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getEffective()](#getEffective--) | Haalt effectieve tabelkolomopmaak-eigenschappen op met overerving en toegepaste tabelstijlen. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IColumnFormatEffectiveData getEffective()
```


Haalt effectieve tabelkolomopmaak-eigenschappen op met overerving en toegepaste tabelstijlen.

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

**Retour:**
[IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata) - Een [IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Versie. Alleen-lezen long.

**Retour:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Retourneert de bovenliggende IPresentationComponent. Alleen-lezen [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Retour:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)