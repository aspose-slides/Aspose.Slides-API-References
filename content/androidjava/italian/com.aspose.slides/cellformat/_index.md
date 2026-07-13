---
title: CellFormat
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta il formato di una cella di tabella.
type: docs
url: /it/com.aspose.slides/cellformat/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tutte le interfacce implementate:**
[com.aspose.slides.ICellFormat](../../com.aspose.slides/icellformat)
```
public final class CellFormat extends PVIObject implements ICellFormat
```

Rappresenta il formato di una cella di tabella.
## Methods

| Metodo | Descrizione |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillFormat()](#getFillFormat--) | Restituisce un oggetto di proprietà di riempimento della cella. |
| [getBorderLeft()](#getBorderLeft--) | Restituisce un oggetto di proprietà della linea del bordo sinistro. |
| [getBorderTop()](#getBorderTop--) | Restituisce un oggetto di proprietà della linea del bordo superiore. |
| [getBorderRight()](#getBorderRight--) | Restituisce un oggetto di proprietà della linea del bordo destro. |
| [getBorderBottom()](#getBorderBottom--) | Restituisce un oggetto di proprietà della linea del bordo inferiore. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Restituisce un oggetto di proprietà della linea diagonale dall'alto a sinistra al basso a destra. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Restituisce un oggetto di proprietà della linea diagonale dal basso a sinistra al alto a destra. |
| [getEffective()](#getEffective--) | Ottiene le proprietà di formattazione della cella della tabella effettive con ereditarietà e stili della tabella applicati. |
| [getTransparency()](#getTransparency--) | Ottiene o imposta la trasparenza del colore di riempimento. |
| [setTransparency(float value)](#setTransparency-float-) | Ottiene o imposta la trasparenza del colore di riempimento. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versione. Solo lettura long.

**Restituisce:**
long
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Restituisce un oggetto di proprietà di riempimento della cella. Solo lettura [IFillFormat](../../com.aspose.slides/ifillformat).

**Restituisce:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```


Restituisce un oggetto di proprietà della linea del bordo sinistro. Solo lettura [ILineFormat](../../com.aspose.slides/ilineformat).

**Restituisce:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```


Restituisce un oggetto di proprietà della linea del bordo superiore. Solo lettura [ILineFormat](../../com.aspose.slides/ilineformat).

**Restituisce:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```


Restituisce un oggetto di proprietà della linea del bordo destro. Solo lettura [ILineFormat](../../com.aspose.slides/ilineformat).

**Restituisce:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```


Restituisce un oggetto di proprietà della linea del bordo inferiore. Solo lettura [ILineFormat](../../com.aspose.slides/ilineformat).

**Restituisce:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```


Restituisce un oggetto di proprietà della linea diagonale dall'alto a sinistra al basso a destra. Solo lettura [ILineFormat](../../com.aspose.slides/ilineformat).

**Restituisce:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```


Restituisce un oggetto di proprietà della linea diagonale dal basso a sinistra al alto a destra. Solo lettura [ILineFormat](../../com.aspose.slides/ilineformat).

**Restituisce:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```


Ottiene le proprietà di formattazione della cella della tabella effettive con ereditarietà e stili della tabella applicati.

--------------------

> ```
> This example demonstrates getting effective fill format for different table logic parts.
>  Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
>  So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
>  
>  Presentation pres = new Presentation(@"MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (ITable) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).RowFormat.GetEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```


Ottiene o imposta la trasparenza del colore di riempimento. Lettura/scrittura float .

**Restituisce:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```


Ottiene o imposta la trasparenza del colore di riempimento. Lettura/scrittura float .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |