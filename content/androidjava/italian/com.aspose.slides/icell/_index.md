---
title: ICell
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta una cella in una tabella.
type: docs
url: /it/com.aspose.slides/icell/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ICell extends ISlideComponent
```

Rappresenta una cella in una tabella.
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
| [getAnchorCenter()](#getAnchorCenter--) | Determina se il riquadro di testo è centrato all'interno di una cella. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Determina se il riquadro di testo è centrato all'interno di una cella. |
| [getFirstColumn()](#getFirstColumn--) | Ottiene la prima colonna della cella. |
| [getFirstRow()](#getFirstRow--) | Ottiene la prima riga della cella. |
| [getColSpan()](#getColSpan--) | Restituisce il numero di colonne della griglia della tabella padre che la cella corrente deve coprire. |
| [getRowSpan()](#getRowSpan--) | Restituisce il numero di righe che una cella unita occupa. |
| [getTextFrame()](#getTextFrame--) | Restituisce il frame di testo di una cella. |
| [getTable()](#getTable--) | Restituisce l'oggetto Table padre per una cella. |
| [isMergedCell()](#isMergedCell--) | Restituisce true se la cella è unita con un'altra cella adeguata, false altrimenti. |
| [getCellFormat()](#getCellFormat--) | Restituisce l'oggetto CellFormat che contiene le proprietà di formattazione per questa cella. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Divide la cella in due celle in base all'indice di colonna. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Divide la cella in due celle in base all'indice di riga. |
| [splitByHeight(double height)](#splitByHeight-double-) | Divide la cella per altezza. |
| [splitByWidth(double width)](#splitByWidth-double-) | Divide la cella per larghezza. |
### getOffsetX() {#getOffsetX--}
```
public abstract double getOffsetX()
```

Restituisce una distanza dal lato sinistro di una tabella al lato sinistro di una cella. Solo lettura double.

**Restituisce:**
double
### getOffsetY() {#getOffsetY--}
```
public abstract double getOffsetY()
```

Restituisce una distanza dal lato superiore di una tabella al lato superiore di una cella. Solo lettura double.

**Restituisce:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public abstract int getFirstRowIndex()
```

Restituisce l'indice della prima riga coperta dalla cella. Solo lettura int.

**Restituisce:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public abstract int getFirstColumnIndex()
```

Restituisce l'indice della prima colonna coperta dalla cella. Solo lettura int.

**Restituisce:**
int
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Restituisce la larghezza della cella. Solo lettura double.

**Restituisce:**
double
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

Restituisce l'altezza della cella. Solo lettura double.

**Restituisce:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

Restituisce l'altezza minima di una cella. Questa è la somma delle altezze minime di tutte le righe coperte dalla cella. Solo lettura double.

**Restituisce:**
double
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Restituisce o imposta il margine sinistro in un TextFrame. Lettura/Scrittura double.

**Restituisce:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Restituisce o imposta il margine sinistro in un TextFrame. Lettura/Scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Restituisce o imposta il margine destro in un TextFrame. Lettura/Scrittura double.

**Restituisce:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Restituisce o imposta il margine destro in un TextFrame. Lettura/Scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Restituisce o imposta il margine superiore in un TextFrame. Lettura/Scrittura double.

**Restituisce:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Restituisce o imposta il margine superiore in un TextFrame. Lettura/Scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Restituisce o imposta il margine inferiore in un TextFrame. Lettura/Scrittura double.

**Restituisce:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Restituisce o imposta il margine inferiore in un TextFrame. Lettura/Scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Restituisce o imposta il tipo di testo verticale. Lettura/Scrittura [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Restituisce:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Restituisce o imposta il tipo di testo verticale. Lettura/Scrittura [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public abstract byte getTextAnchorType()
```

Restituisce o imposta il tipo di ancoraggio del testo. Lettura/Scrittura [TextAnchorType](../../com.aspose.slides/textanchortype).

**Restituisce:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public abstract void setTextAnchorType(byte value)
```

Restituisce o imposta il tipo di ancoraggio del testo. Lettura/Scrittura [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public abstract boolean getAnchorCenter()
```

Determina se il riquadro di testo è centrato all'interno di una cella. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public abstract void setAnchorCenter(boolean value)
```

Determina se il riquadro di testo è centrato all'interno di una cella. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getFirstColumn() {#getFirstColumn--}
```
public abstract IColumn getFirstColumn()
```

Ottiene la prima colonna della cella. Solo lettura [IColumn](../../com.aspose.slides/icolumn).

**Restituisce:**
[IColumn](../../com.aspose.slides/icolumn)
### getFirstRow() {#getFirstRow--}
```
public abstract IRow getFirstRow()
```

Ottiene la prima riga della cella. Solo lettura [IRow](../../com.aspose.slides/irow).

**Restituisce:**
[IRow](../../com.aspose.slides/irow)
### getColSpan() {#getColSpan--}
```
public abstract int getColSpan()
```

Restituisce il numero di colonne della griglia della tabella padre che la cella corrente deve coprire. Questa proprietà consente alle celle di apparire unite, poiché si estendono sui confini verticali di altre celle nella tabella. Solo lettura int.

**Restituisce:**
int
### getRowSpan() {#getRowSpan--}
```
public abstract int getRowSpan()
```

Restituisce il numero di righe che una cella unita occupa. Questo è usato in combinazione con l'attributo vMerge su altre celle per specificare la cella iniziale di una fusione orizzontale. Solo lettura int.

**Restituisce:**
int
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Restituisce il frame di testo di una cella. Solo lettura [ITextFrame](../../com.aspose.slides/itextframe).

**Restituisce:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public abstract ITable getTable()
```

Restituisce l'oggetto Table padre per una cella. Solo lettura [ITable](../../com.aspose.slides/itable).

**Restituisce:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public abstract boolean isMergedCell()
```

Restituisce true se la cella è unita con un'altra cella adeguata, false altrimenti. Solo lettura boolean.

**Restituisce:**
boolean
### getCellFormat() {#getCellFormat--}
```
public abstract ICellFormat getCellFormat()
```

Restituisce l'oggetto CellFormat che contiene le proprietà di formattazione per questa cella. Solo lettura [ICellFormat](../../com.aspose.slides/icellformat).

**Restituisce:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public abstract void splitByColSpan(int index)
```

Divide la cella in due celle in base all'indice di colonna.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di colonna. |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public abstract void splitByRowSpan(int index)
```

Divide la cella in due celle in base all'indice di riga.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di riga. |
### splitByHeight(double height) {#splitByHeight-double-}
```
public abstract void splitByHeight(double height)
```

Divide la cella per altezza.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| height | double | Altezza di una riga. |
### splitByWidth(double width) {#splitByWidth-double-}
```
public abstract void splitByWidth(double width)
```

Divide la cella per larghezza.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | double | Larghezza di una colonna. |