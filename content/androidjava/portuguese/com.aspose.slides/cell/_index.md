---
title: Cell
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma célula de uma tabela.
type: docs
url: /pt/com.aspose.slides/cell/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
com.aspose.slides.IDOMObject, [com.aspose.slides.ICell](../../com.aspose.slides/icell)
```
public class Cell implements IDOMObject, ICell
```

Representa uma célula de uma tabela.
## Métodos

| Method | Description |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | Retorna uma distância do lado esquerdo de uma tabela ao lado esquerdo de uma célula. |
| [getOffsetY()](#getOffsetY--) | Retorna uma distância do lado superior de uma tabela ao lado superior de uma célula. |
| [getFirstRowIndex()](#getFirstRowIndex--) | Retorna o índice da primeira linha coberta pela célula. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | Retorna o índice da primeira coluna coberta pela célula. |
| [getWidth()](#getWidth--) | Retorna a largura da célula. |
| [getHeight()](#getHeight--) | Retorna a altura da célula. |
| [getMinimalHeight()](#getMinimalHeight--) | Retorna a altura mínima de uma célula. |
| [getMarginLeft()](#getMarginLeft--) | Retorna ou define a margem esquerda em um TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Retorna ou define a margem esquerda em um TextFrame. |
| [getMarginRight()](#getMarginRight--) | Retorna ou define a margem direita em um TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Retorna ou define a margem direita em um TextFrame. |
| [getMarginTop()](#getMarginTop--) | Retorna ou define a margem superior em um TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Retorna ou define a margem superior em um TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Retorna ou define a margem inferior em um TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Retorna ou define a margem inferior em um TextFrame. |
| [getTextVerticalType()](#getTextVerticalType--) | Retorna ou define o tipo de texto vertical. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Retorna ou define o tipo de texto vertical. |
| [getTextAnchorType()](#getTextAnchorType--) | Retorna ou define o tipo de âncora de texto. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | Retorna ou define o tipo de âncora de texto. |
| [getAnchorCenter()](#getAnchorCenter--) | Determina se a caixa de texto está centrada dentro de uma célula. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Determina se a caixa de texto está centrada dentro de uma célula. |
| [getFirstRow()](#getFirstRow--) | Obtém a primeira linha da célula. |
| [getFirstColumn()](#getFirstColumn--) | Obtém a primeira coluna da célula. |
| [getColSpan()](#getColSpan--) | Retorna o número de colunas da grade na grade da tabela pai que devem ser abrangidas pela célula atual. |
| [getRowSpan()](#getRowSpan--) | Retorna o número de linhas que uma célula mesclada abrange. |
| [getTextFrame()](#getTextFrame--) | Retorna o quadro de texto de uma célula. |
| [getTable()](#getTable--) | Retorna o objeto Table pai de uma célula. |
| [isMergedCell()](#isMergedCell--) | Retorna verdadeiro se a célula está mesclada com qualquer célula ajustada, falso caso contrário. |
| [getCellFormat()](#getCellFormat--) | Retorna o objeto CellFormat que contém propriedades de formatação para esta célula. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Divide a célula em duas células pelo índice da coluna. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Divide a célula em duas células pelo índice da linha. |
| [splitByHeight(double height)](#splitByHeight-double-) | Divide a célula por altura. |
| [splitByWidth(double width)](#splitByWidth-double-) | Divide a célula por largura. |
| [getSlide()](#getSlide--) | Retorna o slide pai de uma célula. |
| [getPresentation()](#getPresentation--) | Retorna a apresentação pai de uma célula. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getOffsetX() {#getOffsetX--}
```
public final double getOffsetX()
```

Retorna uma distância do lado esquerdo de uma tabela ao lado esquerdo de uma célula. Somente leitura double.

**Retorna:**
double
### getOffsetY() {#getOffsetY--}
```
public final double getOffsetY()
```

Retorna uma distância do lado superior de uma tabela ao lado superior de uma célula. Somente leitura double.

**Retorna:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public final int getFirstRowIndex()
```

Retorna o índice da primeira linha coberta pela célula. Somente leitura int.

**Retorna:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public final int getFirstColumnIndex()
```

Retorna o índice da primeira coluna coberta pela célula. Somente leitura int.

**Retorna:**
int
### getWidth() {#getWidth--}
```
public final double getWidth()
```

Retorna a largura da célula. Somente leitura double.

**Retorna:**
double
### getHeight() {#getHeight--}
```
public final double getHeight()
```

Retorna a altura da célula. Somente leitura double.

**Retorna:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

Retorna a altura mínima de uma célula. Esta é a soma das alturas mínimas de todas as linhas cobertas pela célula. Somente leitura double.

**Retorna:**
double
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

Retorna ou define a margem esquerda em um TextFrame. Leitura/gravação double.

**Retorna:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

Retorna ou define a margem esquerda em um TextFrame. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

Retorna ou define a margem direita em um TextFrame. Leitura/gravação double.

**Retorna:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

Retorna ou define a margem direita em um TextFrame. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

Retorna ou define a margem superior em um TextFrame. Leitura/gravação double.

**Retorna:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

Retorna ou define a margem superior em um TextFrame. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

Retorna ou define a margem inferior em um TextFrame. Leitura/gravação double.

**Retorna:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

Retorna ou define a margem inferior em um TextFrame. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

Retorna ou define o tipo de texto vertical. Leitura/gravação [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Retorna:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

Retorna ou define o tipo de texto vertical. Leitura/gravação [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public final byte getTextAnchorType()
```

Retorna ou define o tipo de âncora de texto. Leitura/gravação [TextAnchorType](../../com.aspose.slides/textanchortype).

**Retorna:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public final void setTextAnchorType(byte value)
```

Retorna ou define o tipo de âncora de texto. Leitura/gravação [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public final boolean getAnchorCenter()
```

Determina se a caixa de texto está centrada dentro de uma célula. Leitura/gravação boolean.

**Retorna:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public final void setAnchorCenter(boolean value)
```

Determina se a caixa de texto está centrada dentro de uma célula. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getFirstRow() {#getFirstRow--}
```
public final IRow getFirstRow()
```

Obtém a primeira linha da célula. Somente leitura [IRow](../../com.aspose.slides/irow).

**Retorna:**
[IRow](../../com.aspose.slides/irow)
### getFirstColumn() {#getFirstColumn--}
```
public final IColumn getFirstColumn()
```

Obtém a primeira coluna da célula. Somente leitura [IColumn](../../com.aspose.slides/icolumn).

**Retorna:**
[IColumn](../../com.aspose.slides/icolumn)
### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```

Retorna o número de colunas da grade na grade da tabela pai que devem ser abrangidas pela célula atual. Esta propriedade permite que as células pareçam mescladas, pois abrangem limites verticais de outras células na tabela. Somente leitura int.

**Retorna:**
int
### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```

Retorna o número de linhas que uma célula mesclada abrange. Isto é usado em combinação com o atributo vMerge em outras células para especificar a célula inicial de uma mesclagem horizontal. Somente leitura int.

**Retorna:**
int
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Retorna o quadro de texto de uma célula. Somente leitura [ITextFrame](../../com.aspose.slides/itextframe).

**Retorna:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public final ITable getTable()
```

Retorna o objeto Table pai de uma célula. Somente leitura [ITable](../../com.aspose.slides/itable).

**Retorna:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public final boolean isMergedCell()
```

Retorna verdadeiro se a célula está mesclada com qualquer célula ajustada, falso caso contrário. Somente leitura boolean.

**Retorna:**
boolean
### getCellFormat() {#getCellFormat--}
```
public final ICellFormat getCellFormat()
```

Retorna o objeto CellFormat que contém propriedades de formatação para esta célula. Somente leitura [ICellFormat](../../com.aspose.slides/icellformat).

**Retorna:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public final void splitByColSpan(int index)
```

Divide a célula em duas células pelo índice da coluna.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice da coluna. |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public final void splitByRowSpan(int index)
```

Divide a célula em duas células pelo índice da linha.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice da linha. |
### splitByHeight(double height) {#splitByHeight-double-}
```
public final void splitByHeight(double height)
```

Divide a célula por altura.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| height | double | Altura de uma linha. |
### splitByWidth(double width) {#splitByWidth-double-}
```
public final void splitByWidth(double width)
```

Divide a célula por largura.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| width | double | Largura de uma coluna. |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retorna o slide pai de uma célula. Somente leitura [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Retorna:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retorna a apresentação pai de uma célula. Somente leitura [IPresentation](../../com.aspose.slides/ipresentation).

**Retorna:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retorna o objeto Parent_Immediate. Somente leitura IDOMObject.

**Retorna:**
com.aspose.slides.IDOMObject