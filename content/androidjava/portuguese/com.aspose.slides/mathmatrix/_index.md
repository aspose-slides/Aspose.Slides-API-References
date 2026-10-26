---
title: MathMatrix
second_title: Aspose.Slides para Android via Referência da API Java
description: Especifica o objeto Matrix composto por elementos filhos dispostos em uma ou mais linhas e colunas.
type: docs
url: /pt/com.aspose.slides/mathmatrix/
---
**Herança:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

Specifica o objeto Matrix, composto por elementos filhos dispostos em uma ou mais linhas e colunas. É importante notar que matrizes não têm delimitadores embutidos. Para colocar a matriz entre colchetes, você deve usar o objeto delimitador (IMathDelimiter). Argumentos nulos podem ser usados para criar lacunas em matrizes.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Construtores

| Construtor | Descrição |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | Inicializa uma nova instância da classe MathMatrix. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getRowCount()](#getRowCount--) | Número de linhas na matriz |
| [getColumnCount()](#getColumnCount--) | Número de colunas na matriz |
| [getHidePlaceholders()](#getHidePlaceholders--) | Oculta os marcadores de posição para elementos vazios da matriz Padrão: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Oculta os marcadores de posição para elementos vazios da matriz Padrão: false |
| [getBaseJustification()](#getBaseJustification--) | Especifica a justificação vertical em relação ao texto ao redor. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Especifica a justificação vertical em relação ao texto ao redor. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Largura mínima da coluna em twips (1/20th of a point) The gap spacing (also referred to as \\u201cColumn Gap\\u201d or \\u201cGap Width\\u201d) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Largura mínima da coluna em twips (1/20th of a point) The gap spacing (also referred to to as \\u201cColumn Gap\\u201d or \\u201cGap Width\\u201d) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). |
| [getColumnGapRule()](#getColumnGapRule--) | O tipo de espaçamento horizontal entre colunas de uma matriz; as unidades de espaçamento horizontal podem ser ems ou pontos (armazenados como twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | O tipo de espaçamento horizontal entre colunas de uma matriz; as unidades de espaçamento horizontal podem ser ems ou pontos (armazenados como twips). |
| [getColumnGap()](#getColumnGap--) | O valor do espaçamento horizontal entre colunas de uma matriz; se ColumnGapRule for definido como 3 (“Exactly”), a unidade é interpretada como twips (1/20 de ponto). Se ColumnGapRule for definido como 4 (“Multiple”), a unidade é interpretada como número de incrementos de 0,5 em. |
| [setColumnGap(long value)](#setColumnGap-long-) | O valor do espaçamento horizontal entre colunas de uma matriz; se ColumnGapRule for definido como 3 (“Exactly”), a unidade é interpretada como twips (1/20 de ponto). Se ColumnGapRule for definido como 4 (“Multiple”), a unidade é interpretada como número de incrementos de 0,5 em. |
| [getRowGapRule()](#getRowGapRule--) | O tipo de espaçamento vertical entre linhas de uma matriz; as unidades de espaçamento vertical podem ser linhas ou pontos (armazenados como twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | O tipo de espaçamento vertical entre linhas de uma matriz; as unidades de espaçamento vertical podem ser linhas ou pontos (armazenados como twips). |
| [getRowGap()](#getRowGap--) | O valor do espaçamento vertical entre linhas de uma matriz; se RowGapRule for definido como 3 (“Exactly”), a unidade é interpretada como twips (1/20 de ponto). Se RowGapRule for definido como 4 (“Multiple”), a unidade é interpretada como meia linha. |
| [setRowGap(long value)](#setRowGap-long-) | O valor do espaçamento vertical entre linhas de uma matriz; se RowGapRule for definido como 3 (“Exactly”), a unidade é interpretada como twips (1/20 de ponto). Se RowGapRule for definido como 4 (“Multiple”), a unidade é interpretada como meia linha. |
| [get_Item(int row, int column)](#get-Item-int-int-) | Elemento da matriz |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Elemento da matriz |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propriedades de Caracteres de Controle |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Obtém o alinhamento horizontal da coluna especificada |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Define o alinhamento horizontal da coluna especificada |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Define o alinhamento horizontal das colunas especificadas |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Insere uma nova linha antes da especificada. Inicialmente todos os elementos da nova linha são nulos. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Insere uma nova linha após a especificada. Inicialmente todos os elementos da nova linha são nulos. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Exclui a linha especificada |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Insere uma nova coluna antes da especificada. Inicialmente todos os elementos da nova coluna são nulos. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Insere uma nova coluna após a especificada. Inicialmente todos os elementos da nova coluna são nulos. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Exclui a coluna especificada |
| [getChildren()](#getChildren--) | Obtém elementos filhos |
### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
```
public MathMatrix(int rowCount, int columnCount)
```

Inicializa uma nova instância da classe MathMatrix.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rowCount | int | contagem de linhas |
| columnCount | int | contagem de colunas |

### getRowCount() {#getRowCount--}
```
public final int getRowCount()
```

Número de linhas na matriz

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**Retorna:**
int
### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

Número de colunas na matriz

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**Retorna:**
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public final boolean getHidePlaceholders()
```

Oculta os marcadores de posição para elementos vazios da matriz Padrão: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Retorna:**
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public final void setHidePlaceholders(boolean value)
```

Oculta os marcadores de posição para elementos vazios da matriz Padrão: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

Especifica a justificação vertical em relação ao texto ao redor. Os valores possíveis são top, bottom e center. Padrão: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Retorna:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

Especifica a justificação vertical em relação ao texto ao redor. Os valores possíveis são top, bottom e center. Padrão: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public final long getMinColumnWidth()
```

Largura mínima da coluna em twips (1/20th of a point) The gap spacing (also referred to as \\u201cColumn Gap\\u201d or \\u201cGap Width\\u201d) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). Default: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Retorna:**
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public final void setMinColumnWidth(long value)
```

Largura mínima da coluna em twips (1/20th of a point) The gap spacing (also referred to as \\u201cColumn Gap\\u201d or \\u201cGap Width\\u201d) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). Default: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public final int getColumnGapRule()
```

O tipo de espaçamento horizontal entre colunas de uma matriz; as unidades de espaçamento horizontal podem ser ems ou pontos (armazenados como twips). Default: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Retorna:**
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public final void setColumnGapRule(int value)
```

O tipo de espaçamento horizontal entre colunas de uma matriz; as unidades de espaçamento horizontal podem ser ems ou pontos (armazenados como twips). Default: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public final long getColumnGap()
```

O valor do espaçamento horizontal entre colunas de uma matriz; se ColumnGapRule for definido como 3 (“Exactly”), a unidade é interpretada como twips (1/20 de ponto). Se ColumnGapRule for definido como 4 (“Multiple”), a unidade é interpretada como número de incrementos de 0,5 em. In other cases ignored. Default: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Retorna:**
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public final void setColumnGap(long value)
```

O valor do espaçamento horizontal entre colunas de uma matriz; se ColumnGapRule for definido como 3 (“Exactly”), a unidade é interpretada como twips (1/20 de ponto). Se ColumnGapRule for definido como 4 (“Multiple”), a unidade é interpretada como número de incrementos de 0,5 em. In other cases ignored. Default: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public final int getRowGapRule()
```

O tipo de espaçamento vertical entre linhas de uma matriz; as unidades de espaçamento vertical podem ser linhas ou pontos (armazenados como twips). Default: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Retorna:**
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public final void setRowGapRule(int value)
```

O tipo de espaçamento vertical entre linhas de uma matriz; as unidades de espaçamento vertical podem ser linhas ou pontos (armazenados como twips). Default: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public final long getRowGap()
```

O valor do espaçamento vertical entre linhas de uma matriz; se RowGapRule for definido como 3 (“Exactly”), a unidade é interpretada como twips (1/20 de ponto). Se RowGapRule for definido como 4 (“Multiple”), a unidade é interpretada como meia linha. Default: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Retorna:**
long
### setRowGap(long value) {#setRowGap-long-}
```
public final void setRowGap(long value)
```

O valor do espaçamento vertical entre linhas de uma matriz; se RowGapRule for definido como 3 (“Exactly”), a unidade é interpretada como twips (1/20 de ponto). Se RowGapRule for definido como 4 (“Multiple”), a unidade é interpretada como meia linha. Default: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public final IMathElement get_Item(int row, int column)
```

Elemento da matriz

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| row | int | O índice baseado em zero da linha para obter o item |
| column | int | O índice baseado em zero da coluna para obter o item |

**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int row, int column, IMathElement value)
```

Elemento da matriz

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| row | int | O índice baseado em zero da linha para obter o item |
| column | int | O índice baseado em zero da coluna para obter o item |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Propriedades de Caracteres de Controle

**Retorna:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public final int getColumnAlignment(int columnIndex)
```

Obtém o alinhamento horizontal da coluna especificada

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| columnIndex | int | Índice da coluna baseado em zero |

**Retorna:**
int - Alinhamento Horizontal da coluna especificada
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
```

Define o alinhamento horizontal da coluna especificada

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| columnIndex | int | Índice da coluna baseado em zero |
| val | int | Novo valor do alinhamento horizontal da coluna especificada |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Define o alinhamento horizontal das colunas especificadas

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| columnIndex | int | Índice baseado em zero da primeira coluna para definir o alinhamento |
| columnsCount | long | O número de colunas para especificar o alinhamento |
| val | int | Novo valor do alinhamento horizontal da coluna especificada |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```

Insere uma nova linha antes da especificada. Inicialmente todos os elementos da nova linha são nulos.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rowIndex | int | Índice da linha antes da qual inserir uma nova |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```

Insere uma nova linha após a especificada. Inicialmente todos os elementos da nova linha são nulos.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rowIndex | int | Índice da linha após a qual inserir uma nova |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public final void deleteRow(int rowIndex)
```

Exclui a linha especificada

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rowIndex | int | O índice baseado em zero da linha a ser excluída. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
```

Insere uma nova coluna antes da especificada. Inicialmente todos os elementos da nova coluna são nulos.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| columnIndex | int | Índice da coluna antes da qual inserir uma nova |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public final void insertColumnAfter(int columnIndex)
```

Insere uma nova coluna após a especificada. Inicialmente todos os elementos da nova coluna são nulos.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| columnIndex | int | Índice da coluna após a qual inserir uma nova |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public final void deleteColumn(int columnIndex)
```

Exclui a coluna especificada

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| columnIndex | int | Índice baseado em zero da coluna a ser excluída. |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Obtém elementos filhos

**Retorna:**
com.aspose.slides.IMathElement[]