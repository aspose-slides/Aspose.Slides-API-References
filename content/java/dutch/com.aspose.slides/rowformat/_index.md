---
title: RowFormat
second_title: Aspose.Slides voor Java API-referentie
description: Stelt het formaat van een tabelrij voor.
type: docs
url: /nl/com.aspose.slides/rowformat/
---
**Overerving:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IRowFormat](../../com.aspose.slides/irowformat), com.aspose.slides.IPVIObject
```
public final class RowFormat extends DomObject<Row> implements IRowFormat, IPVIObject
```

Stelt het opmaak van een tabelrij voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getEffective()](#getEffective--) | Haalt effectieve tabelrij opmaak eigenschappen op met overerving en toepaste tabelstijlen. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IRowFormatEffectiveData getEffective()
```


Haalt effectieve tabelrij opmaak eigenschappen op met overerving en toepaste tabelstijlen.

--------------------

> ```
> Dit voorbeeld toont hoe je het effectieve opvulformaat voor verschillende tabellogica-onderdelen verkrijgt.
>  Houd er rekening mee dat celopmaak altijd een hogere prioriteit heeft dan rij-opmaak, rij hoger dan kolom, kolom hoger dan de hele tabel.
>  Uiteindelijk worden de CellFormatEffectiveData-eigenschappen altijd gebruikt om de tabel te tekenen. De volgende code is slechts een voorbeeld van de API.
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


**Retour:**
[IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata) - Een [IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata).
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


Retourneert ouder IPresentationComponent. Alleen-lezen [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Retour:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)