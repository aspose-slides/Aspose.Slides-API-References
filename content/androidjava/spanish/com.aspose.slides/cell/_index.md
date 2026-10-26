---
title: Cell
second_title: Aspose.Slides para Android a través de la API de referencia Java
description: Representa una celda de una tabla.
type: docs
url: /es/com.aspose.slides/cell/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
com.aspose.slides.IDOMObject, [com.aspose.slides.ICell](../../com.aspose.slides/icell)
```
public class Cell implements IDOMObject, ICell
```

Representa una celda de una tabla.
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
| [getTextAnchorType()](#getTextAnchorType--) | Devuelve o establece el tipo de anclaje de texto. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | Devuelve o establece el tipo de anclaje de texto. |
| [getAnchorCenter()](#getAnchorCenter--) | Determina si el cuadro de texto está centrado dentro de una celda. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Determina si el cuadro de texto está centrado dentro de una celda. |
| [getFirstRow()](#getFirstRow--) | Obtiene la primera fila de la celda. |
| [getFirstColumn()](#getFirstColumn--) | Obtiene la primera columna de la celda. |
| [getColSpan()](#getColSpan--) | Devuelve el número de columnas de la cuadrícula en la cuadrícula de la tabla principal que será abarcado por la celda actual. |
| [getRowSpan()](#getRowSpan--) | Devuelve el número de filas que abarca una celda combinada. |
| [getTextFrame()](#getTextFrame--) | Devuelve el marco de texto de una celda. |
| [getTable()](#getTable--) | Devuelve el objeto Table padre de una celda. |
| [isMergedCell()](#isMergedCell--) | Devuelve verdadero si la celda está combinada con alguna celda ajustada, falso en caso contrario. |
| [getCellFormat()](#getCellFormat--) | Devuelve el objeto CellFormat que contiene las propiedades de formato para esta celda. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Divide la celda en dos celdas por índice de columna. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Divide la celda en dos celdas por índice de fila. |
| [splitByHeight(double height)](#splitByHeight-double-) | Divide la celda por altura. |
| [splitByWidth(double width)](#splitByWidth-double-) | Divide la celda por ancho. |
| [getSlide()](#getSlide--) | Devuelve la diapositiva padre de una celda. |
| [getPresentation()](#getPresentation--) | Devuelve la presentación padre de una celda. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getOffsetX() {#getOffsetX--}
```
public final double getOffsetX()
```

Devuelve una distancia desde el lado izquierdo de una tabla hasta el lado izquierdo de una celda. Solo lectura double.

**Devuelve:**
double
### getOffsetY() {#getOffsetY--}
```
public final double getOffsetY()
```

Devuelve una distancia desde el lado superior de una tabla hasta el lado superior de una celda. Solo lectura double.

**Devuelve:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public final int getFirstRowIndex()
```

Devuelve el índice de la primera fila cubierta por la celda. Solo lectura int.

**Devuelve:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public final int getFirstColumnIndex()
```

Devuelve el índice de la primera columna cubierta por la celda. Solo lectura int.

**Devuelve:**
int
### getWidth() {#getWidth--}
```
public final double getWidth()
```

Devuelve el ancho de la celda. Solo lectura double.

**Devuelve:**
double
### getHeight() {#getHeight--}
```
public final double getHeight()
```

Devuelve la altura de la celda. Solo lectura double.

**Devuelve:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

Devuelve la altura mínima de una celda. Esta es la suma de las alturas mínimas de todas las filas cubiertas por la celda. Solo lectura double.

**Devuelve:**
double
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

Devuelve o establece el margen izquierdo en un TextFrame. Lectura/escritura double.

**Devuelve:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

Devuelve o establece el margen izquierdo en un TextFrame. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

Devuelve o establece el margen derecho en un TextFrame. Lectura/escritura double.

**Devuelve:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

Devuelve o establece el margen derecho en un TextFrame. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

Devuelve o establece el margen superior en un TextFrame. Lectura/escritura double.

**Devuelve:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

Devuelve o establece el margen superior en un TextFrame. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

Devuelve o establece el margen inferior en un TextFrame. Lectura/escritura double.

**Devuelve:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

Devuelve o establece el margen inferior en un TextFrame. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

Devuelve o establece el tipo de texto vertical. Lectura/escritura [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Devuelve:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

Devuelve o establece el tipo de texto vertical. Lectura/escritura [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public final byte getTextAnchorType()
```

Devuelve o establece el tipo de anclaje de texto. Lectura/escritura [TextAnchorType](../../com.aspose.slides/textanchortype).

**Devuelve:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public final void setTextAnchorType(byte value)
```

Devuelve o establece el tipo de anclaje de texto. Lectura/escritura [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public final boolean getAnchorCenter()
```

Determina si el cuadro de texto está centrado dentro de una celda. Lectura/escritura boolean.

**Devuelve:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public final void setAnchorCenter(boolean value)
```

Determina si el cuadro de texto está centrado dentro de una celda. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getFirstRow() {#getFirstRow--}
```
public final IRow getFirstRow()
```

Obtiene la primera fila de la celda. Solo lectura [IRow](../../com.aspose.slides/irow).

**Devuelve:**
[IRow](../../com.aspose.slides/irow)
### getFirstColumn() {#getFirstColumn--}
```
public final IColumn getFirstColumn()
```

Obtiene la primera columna de la celda. Solo lectura [IColumn](../../com.aspose.slides/icolumn).

**Devuelve:**
[IColumn](../../com.aspose.slides/icolumn)
### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```

Devuelve el número de columnas de la cuadrícula en la cuadrícula de la tabla principal que será abarcado por la celda actual. Esta propiedad permite que las celdas parezcan combinadas, ya que abarcan los límites verticales de otras celdas en la tabla. Solo lectura int.

**Devuelve:**
int
### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```

Devuelve el número de filas que abarca una celda combinada. Se usa en combinación con el atributo vMerge en otras celdas para especificar la celda inicial de una combinación horizontal. Solo lectura int.

**Devuelve:**
int
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Devuelve el marco de texto de una celda. Solo lectura [ITextFrame](../../com.aspose.slides/itextframe).

**Devuelve:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public final ITable getTable()
```

Devuelve el objeto Table padre de una celda. Solo lectura [ITable](../../com.aspose.slides/itable).

**Devuelve:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public final boolean isMergedCell()
```

Devuelve verdadero si la celda está combinada con alguna celda ajustada, falso en caso contrario. Solo lectura boolean.

**Devuelve:**
boolean
### getCellFormat() {#getCellFormat--}
```
public final ICellFormat getCellFormat()
```

Devuelve el objeto CellFormat que contiene las propiedades de formato para esta celda. Solo lectura [ICellFormat](../../com.aspose.slides/icellformat).

**Devuelve:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public final void splitByColSpan(int index)
```

Divide la celda en dos celdas por índice de columna.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de columna. |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public final void splitByRowSpan(int index)
```

Divide la celda en dos celdas por índice de fila.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de fila. |
### splitByHeight(double height) {#splitByHeight-double-}
```
public final void splitByHeight(double height)
```

Divide la celda por altura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| height | double | Altura de una fila. |
### splitByWidth(double width) {#splitByWidth-double-}
```
public final void splitByWidth(double width)
```

Divide la celda por ancho.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | double | Ancho de una columna. |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Devuelve la diapositiva padre de una celda. Solo lectura [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Devuelve:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Devuelve la presentación padre de una celda. Solo lectura [IPresentation](../../com.aspose.slides/ipresentation).

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Devuelve el objeto Parent_Immediate. Solo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject