---
title: ICell
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma célula em uma tabela.
type: docs
url: /pt/com.aspose.slides/icell/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ICell extends ISlideComponent
```

Representa uma célula em uma tabela.
## Métodos

| Método | Descrição |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | Retorna a distância do lado esquerdo de uma tabela ao lado esquerdo de uma célula. |
| [getOffsetY()](#getOffsetY--) | Retorna a distância do lado superior de uma tabela ao lado superior de uma célula. |
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
| [getAnchorCenter()](#getAnchorCenter--) | Determina se a caixa de texto está centralizada dentro de uma célula. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Determina se a caixa de texto está centralizada dentro de uma célula. |
| [getFirstColumn()](#getFirstColumn--) | Obtém a primeira coluna da célula. |
| [getFirstRow()](#getFirstRow--) | Obtém a primeira linha da célula. |
| [getColSpan()](#getColSpan--) | Retorna o número de colunas da grade na tabela pai que devem ser abrangidas pela célula atual. |
| [getRowSpan()](#getRowSpan--) | Retorna o número de linhas que uma célula mesclada abrange. |
| [getTextFrame()](#getTextFrame--) | Retorna o quadro de texto de uma célula. |
| [getTable()](#getTable--) | Retorna o objeto Table pai de uma célula. |
| [isMergedCell()](#isMergedCell--) | Retorna verdadeiro se a célula estiver mesclada com alguma célula ajustada, falso caso contrário. |
| [getCellFormat()](#getCellFormat--) | Retorna o objeto CellFormat que contém propriedades de formatação para esta célula. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Divide a célula em duas células pelo índice da coluna. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Divide a célula em duas células pelo índice da linha. |
| [splitByHeight(double height)](#splitByHeight-double-) | Divide a célula pela altura. |
| [splitByWidth(double width)](#splitByWidth-double-) | Divide a célula pela largura. |
### getOffsetX() {#getOffsetX--}
```
public abstract double getOffsetX()
```

Retorna a distância do lado esquerdo de uma tabela ao lado esquerdo de uma célula. Somente leitura double.

**Retorna:**
double
### getOffsetY() {#getOffsetY--}
```
public abstract double getOffsetY()
```

Retorna a distância do lado superior de uma tabela ao lado superior de uma célula. Somente leitura double.

**Retorna:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public abstract int getFirstRowIndex()
```

Retorna o índice da primeira linha coberta pela célula. Somente leitura int.

**Retorna:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public abstract int getFirstColumnIndex()
```

Retorna o índice da primeira coluna coberta pela célula. Somente leitura int.

**Retorna:**
int
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Retorna a largura da célula. Somente leitura double.

**Retorna:**
double
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

Retorna a altura da célula. Somente leitura double.

**Retorna:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

Retorna a altura mínima de uma célula. Esta é a soma das alturas mínimas de todas as linhas cobertas pela célula. Somente leitura double.

**Retorna:**
double
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Retorna ou define a margem esquerda em um TextFrame. Leitura/gravação double.

**Retorna:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Retorna ou define a margem esquerda em um TextFrame. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Retorna ou define a margem direita em um TextFrame. Leitura/gravação double.

**Retorna:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Retorna ou define a margem direita em um TextFrame. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Retorna ou define a margem superior em um TextFrame. Leitura/gravação double.

**Retorna:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Retorna ou define a margem superior em um TextFrame. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Retorna ou define a margem inferior em um TextFrame. Leitura/gravação double.

**Retorna:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Retorna ou define a margem inferior em um TextFrame. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Retorna ou define o tipo de texto vertical. Leitura/gravação [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Retorna:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Retorna ou define o tipo de texto vertical. Leitura/gravação [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public abstract byte getTextAnchorType()
```

Retorna ou define o tipo de âncora de texto. Leitura/gravação [TextAnchorType](../../com.aspose.slides/textanchortype).

**Retorna:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public abstract void setTextAnchorType(byte value)
```

Retorna ou define o tipo de âncora de texto. Leitura/gravação [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public abstract boolean getAnchorCenter()
```

Determina se a caixa de texto está centralizada dentro de uma célula. Leitura/gravação boolean.

**Retorna:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public abstract void setAnchorCenter(boolean value)
```

Determina se a caixa de texto está centralizada dentro de uma célula. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getFirstColumn() {#getFirstColumn--}
```
public abstract IColumn getFirstColumn()
```

Obtém a primeira coluna da célula. Somente leitura [IColumn](../../com.aspose.slides/icolumn).

**Retorna:**
[IColumn](../../com.aspose.slides/icolumn)
### getFirstRow() {#getFirstRow--}
```
public abstract IRow getFirstRow()
```

Obtém a primeira linha da célula. Somente leitura [IRow](../../com.aspose.slides/irow).

**Retorna:**
[IRow](../../com.aspose.slides/irow)
### getColSpan() {#getColSpan--}
```
public abstract int getColSpan()
```

Retorna o número de colunas da grade na tabela pai que devem ser abrangidas pela célula atual. Esta propriedade permite que as células pareçam mescladas, pois abrangem limites verticais de outras células na tabela. Somente leitura int.

**Retorna:**
int
### getRowSpan() {#getRowSpan--}
```
public abstract int getRowSpan()
```

Retorna o número de linhas que uma célula mesclada abrange. Isso é usado em combinação com o atributo vMerge em outras células para especificar a célula inicial de uma mesclagem horizontal. Somente leitura int.

**Retorna:**
int
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Retorna o quadro de texto de uma célula. Somente leitura [ITextFrame](../../com.aspose.slides/itextframe).

**Retorna:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public abstract ITable getTable()
```

Retorna o objeto Table pai de uma célula. Somente leitura [ITable](../../com.aspose.slides/itable).

**Retorna:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public abstract boolean isMergedCell()
```

Retorna verdadeiro se a célula estiver mesclada com alguma célula ajustada, falso caso contrário. Somente leitura boolean.

**Retorna:**
boolean
### getCellFormat() {#getCellFormat--}
```
public abstract ICellFormat getCellFormat()
```

Retorna o objeto CellFormat que contém propriedades de formatação para esta célula. Somente leitura [ICellFormat](../../com.aspose.slides/icellformat).

**Retorna:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public abstract void splitByColSpan(int index)
```

Divide a célula em duas células pelo índice da coluna.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice da coluna. |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public abstract void splitByRowSpan(int index)
```

Divide a célula em duas células pelo índice da linha.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice da linha. |
### splitByHeight(double height) {#splitByHeight-double-}
```
public abstract void splitByHeight(double height)
```

Divide a célula pela altura.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| height | double | Altura de uma linha. |
### splitByWidth(double width) {#splitByWidth-double-}
```
public abstract void splitByWidth(double width)
```

Divide a célula pela largura.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| width | double | Largura de uma coluna. |