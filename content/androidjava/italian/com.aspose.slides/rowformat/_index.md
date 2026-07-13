---
title: RowFormat
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta il formato di una riga di tabella.
type: docs
url: /it/com.aspose.slides/rowformat/
---
**Eredità:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.IRowFormat](../../com.aspose.slides/irowformat), com.aspose.slides.IPVIObject
```
public final class RowFormat extends DomObject<Row> implements IRowFormat, IPVIObject
```

Rappresenta il formato di una riga di tabella.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEffective()](#getEffective--) | Ottiene le proprietà di formattazione della riga di tabella effettive con eredità e stili di tabella applicati. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IRowFormatEffectiveData getEffective()
```


Ottiene le proprietà di formattazione della riga di tabella effettive con eredità e stili di tabella applicati.

--------------------

> ```
> Questo esempio mostra come ottenere il formato di riempimento efficace per le diverse parti logiche della tabella.
>  Nota che la formattazione delle celle ha sempre priorità più alta rispetto a quella delle righe, le righe - più alta delle colonne, le colonne - più alta dell'intera tabella.
>  Quindi, alla fine, le proprietà di CellFormatEffectiveData vengono sempre usate per disegnare la tabella. Il codice seguente è solo un esempio di utilizzo dell'API.
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


**Restituisce:**
[IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata) - Un [IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Versione. Long a sola lettura.

**Restituisce:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Restituisce il genitore IPresentationComponent. [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent) a sola lettura.

**Restituisce:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)