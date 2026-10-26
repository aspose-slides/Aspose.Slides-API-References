---
title: ITable
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma tabela em um slide.
type: docs
url: /pt/com.aspose.slides/itable/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

Representa uma tabela em um slide.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Retorna a célula nos índices de coluna e linha especificados. |
| [getRows()](#getRows--) | Retorna a coleção de linhas. |
| [getColumns()](#getColumns--) | Retorna a coleção de colunas. |
| [getTableFormat()](#getTableFormat--) | Retorna o objeto TableFormat que contém as propriedades de formatação desta tabela. |
| [getStylePreset()](#getStylePreset--) | Obtém ou define o estilo interno da tabela. |
| [setStylePreset(int value)](#setStylePreset-int-) | Obtém ou define o estilo interno da tabela. |
| [getRightToLeft()](#getRightToLeft--) | Determina se a tabela tem ordem de leitura da direita para a esquerda. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Determina se a tabela tem ordem de leitura da direita para a esquerda. |
| [getFirstRow()](#getFirstRow--) | Determina se a primeira linha da tabela deve ser desenhada com formatação especial. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Determina se a primeira linha da tabela deve ser desenhada com formatação especial. |
| [getFirstCol()](#getFirstCol--) | Determina se a primeira coluna da tabela deve ser desenhada com formatação especial. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Determina se a primeira coluna da tabela deve ser desenhada com formatação especial. |
| [getLastRow()](#getLastRow--) | Determina se a última linha da tabela deve ser desenhada com formatação especial. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Determina se a última linha da tabela deve ser desenhada com formatação especial. |
| [getLastCol()](#getLastCol--) | Determina se a última coluna da tabela deve ser desenhada com formatação especial. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Determina se a última coluna da tabela deve ser desenhada com formatação especial. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Determina se as linhas pares devem ser desenhadas com formatação diferente. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Determina se as linhas pares devem ser desenhadas com formatação diferente. |
| [getVerticalBanding()](#getVerticalBanding--) | Determina se as colunas pares devem ser desenhadas com formatação diferente. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Determina se as colunas pares devem ser desenhadas com formatação diferente. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Mescla células vizinhas. |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```

Retorna a célula nos índices de coluna e linha especificados. Somente leitura [ICell](../../com.aspose.slides/icell).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Retorna:**
[ICell](../../com.aspose.slides/icell)
### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```

Retorna a coleção de linhas. Somente leitura [IRowCollection](../../com.aspose.slides/irowcollection).

**Retorna:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```

Retorna a coleção de colunas. Somente leitura [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Retorna:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```

Retorna o objeto TableFormat que contém as propriedades de formatação desta tabela. Somente leitura [ITableFormat](../../com.aspose.slides/itableformat).

**Retorna:**
[ITableFormat](../../com.aspose.slides/itableformat)
### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```

Obtém ou define o estilo interno da tabela. Leitura/escrita [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Retorna:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```

Obtém ou define o estilo interno da tabela. Leitura/escrita [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

Determina se a tabela tem ordem de leitura da direita para a esquerda. Boolean leitura/escrita.

**Retorna:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```

Determina se a tabela tem ordem de leitura da direita para a esquerda. Boolean leitura/escrita.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```

Determina se a primeira linha da tabela deve ser desenhada com formatação especial. Leitura/escrita boolean.

**Retorna:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```

Determina se a primeira linha da tabela deve ser desenhada com formatação especial. Leitura/escrita boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```

Determina se a primeira coluna da tabela deve ser desenhada com formatação especial. Leitura/escrita boolean.

**Retorna:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```

Determina se a primeira coluna da tabela deve ser desenhada com formatação especial. Leitura/escrita boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```

Determina se a última linha da tabela deve ser desenhada com formatação especial. Leitura/escrita boolean.

**Retorna:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```

Determina se a última linha da tabela deve ser desenhada com formatação especial. Leitura/escrita boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```

Determina se a última coluna da tabela deve ser desenhada com formatação especial. Leitura/escrita boolean.

**Retorna:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```

Determina se a última coluna da tabela deve ser desenhada com formatação especial. Leitura/escrita boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```

Determina se as linhas pares devem ser desenhadas com formatação diferente. Leitura/escrita boolean.

**Retorna:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```

Determina se as linhas pares devem ser desenhadas com formatação diferente. Leitura/escrita boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```

Determina se as colunas pares devem ser desenhadas com formatação diferente. Leitura/escrita boolean.

**Retorna:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```

Determina se as colunas pares devem ser desenhadas com formatação diferente. Leitura/escrita boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

Mescla células vizinhas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Célula a mesclar. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Célula a mesclar. |
| allowSplitting | boolean | Verdadeiro para permitir divisão das células. |

**Retorna:**
[ICell](../../com.aspose.slides/icell) - Célula mesclada.