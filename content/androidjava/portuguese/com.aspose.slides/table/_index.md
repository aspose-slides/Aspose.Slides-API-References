---
title: Table
second_title: Aspose.Slides para Android via Referência de API Java
description: Representa uma tabela em um slide.
type: docs
url: /pt/com.aspose.slides/table/
---
**Herança:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ITable](../../com.aspose.slides/itable)
```
public final class Table extends GraphicalObject implements ITable
```

Representa uma tabela em um slide.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Retorna a célula nos índices de coluna e linha especificados. |
| [getRows()](#getRows--) | Retorna a coleção de linhas. |
| [getColumns()](#getColumns--) | Retorna a coleção de colunas. |
| [getTableFormat()](#getTableFormat--) | Retorna o objeto TableFormat que contém as propriedades de formatação para esta tabela. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Mescla células vizinhas. |
| [getStylePreset()](#getStylePreset--) | Obtém ou define o estilo de tabela embutido. |
| [setStylePreset(int value)](#setStylePreset-int-) | Obtém ou define o estilo de tabela embutido. |
| [getRightToLeft()](#getRightToLeft--) | Determina se a tabela tem ordem de leitura da direita para a esquerda. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Determina se a tabela tem ordem de leitura da direita para a esquerda. |
| [getFirstRow()](#getFirstRow--) | Determina se a primeira linha de uma tabela deve ser desenhada com formatação especial. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Determina se a primeira linha de uma tabela deve ser desenhada com formatação especial. |
| [getFirstCol()](#getFirstCol--) | Determina se a primeira coluna de uma tabela deve ser desenhada com formatação especial. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Determina se a primeira coluna de uma tabela deve ser desenhada com formatação especial. |
| [getLastRow()](#getLastRow--) | Determina se a última linha de uma tabela deve ser desenhada com formatação especial. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Determina se a última linha de uma tabela deve ser desenhada com formatação especial. |
| [getLastCol()](#getLastCol--) | Determina se a última coluna de uma tabela deve ser desenhada com formatação especial. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Determina se a última coluna de uma tabela deve ser desenhada com formatação especial. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Determina se as linhas pares devem ser desenhadas com formatação diferente. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Determina se as linhas pares devem ser desenhadas com formatação diferente. |
| [getVerticalBanding()](#getVerticalBanding--) | Determina se as colunas pares devem ser desenhadas com formatação diferente. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Determina se as colunas pares devem ser desenhadas com formatação diferente. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Define propriedades de formato de porção para todas as porções das células da tabela. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Define propriedades de formato de parágrafo para todos os parágrafos das células da tabela. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Define propriedades de formato de quadro de texto para todos os quadros de texto das células da tabela. |
| [getFillFormat()](#getFillFormat--) | Retorna um objeto TableFormat.FillFormat contendo a formatação de preenchimento para a Tabela. |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```


Retorna a célula nos índices de coluna e linha especificados. Somente leitura [Cell](../../com.aspose.slides/cell).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Retorna:**
[ICell](../../com.aspose.slides/icell)
### getRows() {#getRows--}
```
public final IRowCollection getRows()
```


Retorna a coleção de linhas. Somente leitura [IRowCollection](../../com.aspose.slides/irowcollection).

**Retorna:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```


Retorna a coleção de colunas. Somente leitura [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Retorna:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```


Retorna o objeto TableFormat que contém as propriedades de formatação para esta tabela. Somente leitura [ITableFormat](../../com.aspose.slides/itableformat).

**Retorna:**
[ITableFormat](../../com.aspose.slides/itableformat)
### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```


Mescla células vizinhas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Célula a mesclar. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Célula a mesclar. |
| allowSplitting | boolean | Verdadeiro para permitir a divisão das células. |

**Retorna:**
[ICell](../../com.aspose.slides/icell) - Célula mesclada.
### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```


Obtém ou define o estilo de tabela embutido. Leitura/gravação [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Retorna:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```


Obtém ou define o estilo de tabela embutido. Leitura/gravação [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```


Determina se a tabela tem ordem de leitura da direita para a esquerda. Leitura/gravação  boolean .

**Retorna:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```


Determina se a tabela tem ordem de leitura da direita para a esquerda. Leitura/gravação  boolean .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```


Determina se a primeira linha de uma tabela deve ser desenhada com formatação especial. Leitura/gravação  boolean .

**Retorna:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```


Determina se a primeira linha de uma tabela deve ser desenhada com formatação especial. Leitura/gravação  boolean .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```


Determina se a primeira coluna de uma tabela deve ser desenhada com formatação especial. Leitura/gravação  boolean .

**Retorna:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```


Determina se a primeira coluna de uma tabela deve ser desenhada com formatação especial. Leitura/gravação  boolean .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```


Determina se a última linha de uma tabela deve ser desenhada com formatação especial. Leitura/gravação  boolean .

**Retorna:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```


Determina se a última linha de uma tabela deve ser desenhada com formatação especial. Leitura/gravação  boolean .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```


Determina se a última coluna de uma tabela deve ser desenhada com formatação especial. Leitura/gravação  boolean .

**Retorna:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```


Determina se a última coluna de uma tabela deve ser desenhada com formatação especial. Leitura/gravação  boolean .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```


Determina se as linhas pares devem ser desenhadas com formatação diferente. Leitura/gravação  boolean .

**Retorna:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```


Determina se as linhas pares devem ser desenhadas com formatação diferente. Leitura/gravação  boolean .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```


Determina se as colunas pares devem ser desenhadas com formatação diferente. Leitura/gravação  boolean .

**Retorna:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```


Determina se as colunas pares devem ser desenhadas com formatação diferente. Leitura/gravação  boolean .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


Define propriedades de formato de porção para todas as porções das células da tabela.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | Objeto IPortionFormat com as propriedades necessárias definidas. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


Define propriedades de formato de parágrafo para todos os parágrafos das células da tabela.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | Objeto IParagraphFormat com as propriedades necessárias definidas. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```


Define propriedades de formato de quadro de texto para todos os quadros de texto das células da tabela.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | Objeto ITextFrameFormat com as propriedades necessárias definidas. |

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```


Retorna um objeto TableFormat.FillFormat contendo a formatação de preenchimento para a Tabela. Somente leitura [IFillFormat](../../com.aspose.slides/ifillformat).

**Retorna:**
[IFillFormat](../../com.aspose.slides/ifillformat)