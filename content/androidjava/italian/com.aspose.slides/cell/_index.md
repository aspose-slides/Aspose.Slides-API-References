---
title: Cell
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta una cella di una tabella.
type: docs
url: /it/com.aspose.slides/cell/
---
**Eredita:**
java.lang.Object

**Tutte le interfacce implementate:**
com.aspose.slides.IDOMObject, [com.aspose.slides.ICell](../../com.aspose.slides/icell)
```
public class Cell implements IDOMObject, ICell
```

Rappresenta una cella di una tabella.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | Restituisce una distanza dal lato sinistro di una tabella al lato sinistro di una cella. |
| [getOffsetY()](#getOffsetY--) | Restituisce una distanza dal lato superiore di una tabella al lato superiore di una cella. |
| [getFirstRowIndex()](#getFirstRowIndex--) | Restituisce l'indice della prima riga coperta dalla cella. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | Restituisce l'indice della prima colonna coperta dalla cella. |
| [getWidth()](#getWidth--) | Restituisce la larghezza della cella. |
| [getHeight()](#getHeight--) | Restituisce l'altezza della cella. |
| [getMinimalHeight()](#getMinimalHeight--) | Restituisce l'altezza minima di una cella. |
| [getMarginLeft()](#getMarginLeft--) | Restituisce o imposta il margine sinistro in un TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Restituisce o imposta il margine sinistro in un TextFrame. |
| [getMarginRight()](#getMarginRight--) | Restituisce o imposta il margine destro in un TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Restituisce o imposta il margine destro in un TextFrame. |
| [getMarginTop()](#getMarginTop--) | Restituisce o imposta il margine superiore in un TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Restituisce o imposta il margine superiore in un TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Restituisce o imposta il margine inferiore in un TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Restituisce o imposta il margine inferiore in un TextFrame. |
| [getTextVerticalType()](#getTextVerticalType--) | Restituisce o imposta il tipo di testo verticale. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Restituisce o imposta il tipo di testo verticale. |
| [getTextAnchorType()](#getTextAnchorType--) | Restituisce o imposta il tipo di ancoraggio del testo. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | Restituisce o imposta il tipo di ancoraggio del testo. |
| [getAnchorCenter()](#getAnchorCenter--) | Determina se la casella di testo è centrata all'interno di una cella. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Determina se la casella di testo è centrata all'interno di una cella. |
| [getFirstRow()](#getFirstRow--) | Ottiene la prima riga della cella. |
| [getFirstColumn()](#getFirstColumn--) | Ottiene la prima colonna della cella. |
| [getColSpan()](#getColSpan--) | Restituisce il numero di colonne della griglia nella tabella genitore che la cella corrente deve coprire. |
| [getRowSpan()](#getRowSpan--) | Restituisce il numero di righe che una cella unita copre. |
| [getTextFrame()](#getTextFrame--) | Restituisce il TextFrame di una cella. |
| [getTable()](#getTable--) | Restituisce l'oggetto Table genitore per una cella. |
| [isMergedCell()](#isMergedCell--) | Restituisce true se la cella è unita a un'altra cella, false altrimenti. |
| [getCellFormat()](#getCellFormat--) | Restituisce l'oggetto CellFormat che contiene le proprietà di formattazione per questa cella. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Divide la cella in due celle in base all'indice di colonna. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Divide la cella in due celle in base all'indice di riga. |
| [splitByHeight(double height)](#splitByHeight-double-) | Divide la cella per altezza. |
| [splitByWidth(double width)](#splitByWidth-double-) | Divide la cella per larghezza. |
| [getSlide()](#getSlide--) | Restituisce la diapositiva genitore di una cella. |
| [getPresentation()](#getPresentation--) | Restituisce la presentazione genitore di una cella. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getOffsetX() {#getOffsetX--}
```
public final double getOffsetX()
```

Restituisce una distanza dal lato sinistro di una tabella al lato sinistro di una cella. Solo lettura double.

**Restituisce:**
double
### getOffsetY() {#getOffsetY--}
```
public final double getOffsetY()
```

Restituisce una distanza dal lato superiore di una tabella al lato superiore di una cella. Solo lettura double.

**Restituisce:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public final int getFirstRowIndex()
```

Restituisce l'indice della prima riga coperta dalla cella. Solo lettura int.

**Restituisce:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public final int getFirstColumnIndex()
```

Restituisce l'indice della prima colonna coperta dalla cella. Solo lettura int.

**Restituisce:**
int
### getWidth() {#getWidth--}
```
public final double getWidth()
```

Restituisce la larghezza della cella. Solo lettura double.

**Restituisce:**
double
### getHeight() {#getHeight--}
```
public final double getHeight()
```

Restituisce l'altezza della cella. Solo lettura double.

**Restituisce:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

Restituisce l'altezza minima di una cella. Questa è la somma delle altezze minime di tutte le righe coperte dalla cella. Solo lettura double.

**Restituisce:**
double
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

Restituisce o imposta il margine sinistro in un TextFrame. Lettura/scrittura double.

**Restituisce:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

Restituisce o imposta il margine sinistro in un TextFrame. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

Restituisce o imposta il margine destro in un TextFrame. Lettura/scrittura double.

**Restituisce:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

Restituisce o imposta il margine destro in un TextFrame. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

Restituisce o imposta il margine superiore in un TextFrame. Lettura/scrittura double.

**Restituisce:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

Restituisce o imposta il margine superiore in un TextFrame. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

Restituisce o imposta il margine inferiore in un TextFrame. Lettura/scrittura double.

**Restituisce:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

Restituisce o imposta il margine inferiore in un TextFrame. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

Restituisce o imposta il tipo di testo verticale. Lettura/scrittura [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Restituisce:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

Restituisce o imposta il tipo di testo verticale. Lettura/scrittura [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public final byte getTextAnchorType()
```

Restituisce o imposta il tipo di ancoraggio del testo. Lettura/scrittura [TextAnchorType](../../com.aspose.slides/textanchortype).

**Restituisce:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public final void setTextAnchorType(byte value)
```

Restituisce o imposta il tipo di ancoraggio del testo. Lettura/scrittura [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public final boolean getAnchorCenter()
```

Determina se la casella di testo è centrata all'interno di una cella. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public final void setAnchorCenter(boolean value)
```

Determina se la casella di testo è centrata all'interno di una cella. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getFirstRow() {#getFirstRow--}
```
public final IRow getFirstRow()
```

Ottiene la prima riga della cella. Solo lettura [IRow](../../com.aspose.slides/irow).

**Restituisce:**
[IRow](../../com.aspose.slides/irow)
### getFirstColumn() {#getFirstColumn--}
```
public final IColumn getFirstColumn()
```

Ottiene la prima colonna della cella. Solo lettura [IColumn](../../com.aspose.slides/icolumn).

**Restituisce:**
[IColumn](../../com.aspose.slides/icolumn)
### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```

Restituisce il numero di colonne della griglia nella tabella genitore che la cella corrente deve coprire. Questa proprietà consente alle celle di apparire unite, poiché si estendono oltre i limiti verticali di altre celle nella tabella. Solo lettura int.

**Restituisce:**
int
### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```

Restituisce il numero di righe che una cella unita copre. Questo è usato in combinazione con l'attributo vMerge su altre celle per specificare la cella di inizio di una fusione orizzontale. Solo lettura int.

**Restituisce:**
int
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Restituisce il TextFrame di una cella. Solo lettura [ITextFrame](../../com.aspose.slides/itextframe).

**Restituisce:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public final ITable getTable()
```

Restituisce l'oggetto Table genitore per una cella. Solo lettura [ITable](../../com.aspose.slides/itable).

**Restituisce:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public final boolean isMergedCell()
```

Restituisce true se la cella è unita a un'altra cella, false altrimenti. Solo lettura boolean.

**Restituisce:**
boolean
### getCellFormat() {#getCellFormat--}
```
public final ICellFormat getCellFormat()
```

Restituisce l'oggetto CellFormat che contiene le proprietà di formattazione per questa cella. Solo lettura [ICellFormat](../../com.aspose.slides/icellformat).

**Restituisce:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public final void splitByColSpan(int index)
```

Divide la cella in due celle in base all'indice di colonna.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della colonna. |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public final void splitByRowSpan(int index)
```

Divide la cella in due celle in base all'indice di riga.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della riga. |
### splitByHeight(double height) {#splitByHeight-double-}
```
public final void splitByHeight(double height)
```

Divide la cella per altezza.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| height | double | Altezza di una riga. |
### splitByWidth(double width) {#splitByWidth-double-}
```
public final void splitByWidth(double width)
```

Divide la cella per larghezza.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | double | Larghezza di una colonna. |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Restituisce la diapositiva genitore di una cella. Solo lettura [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Restituisce:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Restituisce la presentazione genitore di una cella. Solo lettura [IPresentation](../../com.aspose.slides/ipresentation).

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject