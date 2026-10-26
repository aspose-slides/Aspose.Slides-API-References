---
title: ICell
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa una celda en una tabla.
type: docs
url: /es/com.aspose.slides/icell/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ICell extends ISlideComponent
```

Representa una celda en una tabla.
## Métodos

| Método | Descripción |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | Devuelve una distancia desde el lado izquierdo de una tabla hasta el lado izquierdo de una celda. |
| [getOffsetY()](#getOffsetY--) | Devuelve una distancia desde el lado superior de una tabla hasta el lado superior de una celda. |
| [getFirstRowIndex()](#getFirstRowIndex--) | Devuelve el índice de la primera fila cubierta por la celda. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | Devuelve el índice de la primera columna cubierta por la celda. |
| [getWidth()](#getWidth--) | Devuelve el ancho de la celda. |
| [getHeight()](#getHeight--) | Devuelve la altura de la celda. |
| [getMinimalHeight()](#getMinimalHeight--) | Devuelve la altura mínima de una celda. |
| [getMarginLeft()](#getMarginLeft--) | Devuelve o establece el margen izquierdo en un TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Devuelve o establece el margen izquierdo en un TextFrame. |
| [getMarginRight()](#getMarginRight--) | Devuelve o establece el margen derecho en un TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Devuelve o establece el margen derecho en un TextFrame. |
| [getMarginTop()](#getMarginTop--) | Devuelve o establece el margen superior en un TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Devuelve o establece el margen superior en un TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Devuelve o establece el margen inferior en un TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Devuelve o establece el margen inferior en un TextFrame. |
| [getTextVerticalType()](#getTextVerticalType--) | Devuelve o establece el tipo de texto vertical. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Devuelve o establece el tipo de texto vertical. |
| [getTextAnchorType()](#getTextAnchorType--) | Devuelve o establece el tipo de anclaje del texto. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | Devuelve o establece el tipo de anclaje del texto. |
| [getAnchorCenter()](#getAnchorCenter--) | Determina si el cuadro de texto está centrado dentro de una celda. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Determina si el cuadro de texto está centrado dentro de una celda. |
| [getFirstColumn()](#getFirstColumn--) | Obtiene la primera columna de la celda. |
| [getFirstRow()](#getFirstRow--) | Obtiene la primera fila de la celda. |
| [getColSpan()](#getColSpan--) | Devuelve el número de columnas de la cuadrícula en la cuadrícula de la tabla padre que debe abarcar la celda actual. |
| [getRowSpan()](#getRowSpan--) | Devuelve el número de filas que abarca una celda fusionada. |
| [getTextFrame()](#getTextFrame--) | Devuelve el marco de texto de una celda. |
| [getTable()](#getTable--) | Devuelve el objeto Table padre de una celda. |
| [isMergedCell()](#isMergedCell--) | Devuelve true si la celda está fusionada con cualquier celda ajustada, false en caso contrario. |
| [getCellFormat()](#getCellFormat--) | Devuelve el objeto CellFormat que contiene propiedades de formato para esta celda. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Divide la celda en dos celdas por índice de columna. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Divide la celda en dos celdas por índice de fila. |
| [splitByHeight(double height)](#splitByHeight-double-) | Divide la celda por altura. |
| [splitByWidth(double width)](#splitByWidth-double-) | Divide la celda por ancho. |
### getOffsetX() {#getOffsetX--}
```
public abstract double getOffsetX()
```

Devuelve una distancia desde el lado izquierdo de una tabla hasta el lado izquierdo de una celda. Solo lectura double.

**Devuelve:**
double
### getOffsetY() {#getOffsetY--}
```
public abstract double getOffsetY()
```

Devuelve una distancia desde el lado superior de una tabla hasta el lado superior de una celda. Solo lectura double.

**Devuelve:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public abstract int getFirstRowIndex()
```

Devuelve el índice de la primera fila cubierta por la celda. Solo lectura int.

**Devuelve:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public abstract int getFirstColumnIndex()
```

Devuelve el índice de la primera columna cubierta por la celda. Solo lectura int.

**Devuelve:**
int
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Devuelve el ancho de la celda. Solo lectura double.

**Devuelve:**
double
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

Devuelve la altura de la celda. Solo lectura double.

**Devuelve:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

Devuelve la altura mínima de una celda. Esta es la suma de las alturas mínimas de todas las filas cubiertas por la celda. Solo lectura double.

**Devuelve:**
double
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Devuelve o establece el margen izquierdo en un TextFrame. Lectura/escritura double.

**Devuelve:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Devuelve o establece el margen izquierdo en un TextFrame. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Devuelve o establece el margen derecho en un TextFrame. Lectura/escritura double.

**Devuelve:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Devuelve o establece el margen derecho en un TextFrame. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Devuelve o establece el margen superior en un TextFrame. Lectura/escritura double.

**Devuelve:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Devuelve o establece el margen superior en un TextFrame. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Devuelve o establece el margen inferior en un TextFrame. Lectura/escritura double.

**Devuelve:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Devuelve o establece el margen inferior en un TextFrame. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Devuelve o establece el tipo de texto vertical. Lectura/escritura [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Devuelve:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Devuelve o establece el tipo de texto vertical. Lectura/escritura [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public abstract byte getTextAnchorType()
```

Devuelve o establece el tipo de anclaje del texto. Lectura/escritura [TextAnchorType](../../com.aspose.slides/textanchortype).

**Devuelve:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public abstract void setTextAnchorType(byte value)
```

Devuelve o establece el tipo de anclaje del texto. Lectura/escritura [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public abstract boolean getAnchorCenter()
```

Determina si el cuadro de texto está centrado dentro de una celda. Lectura/escritura boolean.

**Devuelve:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public abstract void setAnchorCenter(boolean value)
```

Determina si el cuadro de texto está centrado dentro de una celda. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getFirstColumn() {#getFirstColumn--}
```
public abstract IColumn getFirstColumn()
```

Obtiene la primera columna de la celda. Solo lectura [IColumn](../../com.aspose.slides/icolumn).

**Devuelve:**
[IColumn](../../com.aspose.slides/icolumn)
### getFirstRow() {#getFirstRow--}
```
public abstract IRow getFirstRow()
```

Obtiene la primera fila de la celda. Solo lectura [IRow](../../com.aspose.slides/irow).

**Devuelve:**
[IRow](../../com.aspose.slides/irow)
### getColSpan() {#getColSpan--}
```
public abstract int getColSpan()
```

Devuelve el número de columnas de la cuadrícula en la cuadrícula de la tabla padre que debe abarcar la celda actual. Esta propiedad permite que las celdas parezcan fusionadas, ya que abarcan los límites verticales de otras celdas en la tabla. Solo lectura int.

**Devuelve:**
int
### getRowSpan() {#getRowSpan--}
```
public abstract int getRowSpan()
```

Devuelve el número de filas que una celda fusionada abarca. Se utiliza en combinación con el atributo vMerge en otras celdas para especificar la celda de inicio de una fusión horizontal. Solo lectura int.

**Devuelve:**
int
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Devuelve el marco de texto de una celda. Solo lectura [ITextFrame](../../com.aspose.slides/itextframe).

**Devuelve:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public abstract ITable getTable()
```

Devuelve el objeto Table padre de una celda. Solo lectura [ITable](../../com.aspose.slides/itable).

**Devuelve:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public abstract boolean isMergedCell()
```

Devuelve true si la celda está fusionada con cualquier celda ajustada, false en caso contrario. Solo lectura boolean.

**Devuelve:**
boolean
### getCellFormat() {#getCellFormat--}
```
public abstract ICellFormat getCellFormat()
```

Devuelve el objeto CellFormat que contiene propiedades de formato para esta celda. Solo lectura [ICellFormat](../../com.aspose.slides/icellformat).

**Devuelve:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public abstract void splitByColSpan(int index)
```

Divide la celda en dos celdas por índice de columna.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de la columna. |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public abstract void splitByRowSpan(int index)
```

Divide la celda en dos celdas por índice de fila.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de la fila. |
### splitByHeight(double height) {#splitByHeight-double-}
```
public abstract void splitByHeight(double height)
```

Divide la celda por altura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| height | double | Altura de una fila. |
### splitByWidth(double width) {#splitByWidth-double-}
```
public abstract void splitByWidth(double width)
```

Divide la celda por ancho.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | double | Ancho de una columna. |