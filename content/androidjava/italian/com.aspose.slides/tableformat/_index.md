---
title: TableFormat
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta il formato di una tabella.
type: docs
url: /it/com.aspose.slides/tableformat/
---
**Eredità:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

Rappresenta il formato di una tabella.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Restituisce un oggetto delle proprietà di riempimento della tabella. |
| [getTransparency()](#getTransparency--) | Ottiene o imposta la trasparenza del colore di riempimento. |
| [setTransparency(float value)](#setTransparency-float-) | Ottiene o imposta la trasparenza del colore di riempimento. |
| [getEffective()](#getEffective--) | Ottiene le proprietà di formattazione della tabella effettive con ereditarietà e stili di tabella applicati. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Restituisce un oggetto delle proprietà di riempimento della tabella. Sola lettura [IFillFormat](../../com.aspose.slides/ifillformat).

**Restituisce:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```


Ottiene o imposta la trasparenza del colore di riempimento. Lettura/scrittura  float .

**Restituisce:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```


Ottiene o imposta la trasparenza del colore di riempimento. Lettura/scrittura  float .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final ITableFormatEffectiveData getEffective()
```


Ottiene le proprietà di formattazione della tabella effettive con ereditarietà e stili di tabella applicati.

--------------------

> ```
> Questo esempio dimostra come ottenere il formato di riempimento efficace per diverse parti logiche della tabella.
>  Si prega di notare che la formattazione delle celle ha sempre priorità più alta rispetto alla formattazione delle righe, le righe hanno priorità più alta rispetto alle colonne, le colonne hanno priorità più alta rispetto all'intera tabella.
>  Quindi, alla fine, le proprietà di CellFormatEffectiveData vengono sempre utilizzate per disegnare la tabella. Il codice seguente è solo un esempio di API.
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


**Restituisce:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - Un [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Versione. Sola lettura long.

**Restituisce:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Restituisce il componente IPresentationComponent genitore. Sola lettura [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Restituisce:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)