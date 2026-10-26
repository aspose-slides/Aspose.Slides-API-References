---
title: IMathMatrix
second_title: Aspose.Slides para Android via Referência da API Java
description: Especifica o objeto Matrix composto por elementos filhos dispostos em uma ou mais linhas e colunas.
type: docs
url: /pt/com.aspose.slides/imathmatrix/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

Especifica o objeto Matrix, composto por elementos filhos dispostos em uma ou mais linhas e colunas. É importante observar que as matrizes não possuem delimitadores incorporados. Para colocar a matriz nos colchetes, você deve usar o objeto delimitador (IMathDelimiter). Argumentos nulos podem ser usados para criar lacunas nas matrizes.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int row, int column)](#get-Item-int-int-) | Elementos da matriz |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Elementos da matriz |
| [getRowCount()](#getRowCount--) | Número de linhas na matriz |
| [getColumnCount()](#getColumnCount--) | Número de colunas na matriz |
| [getHidePlaceholders()](#getHidePlaceholders--) | Ocultar os marcadores de posição para elementos de matriz vazios Padrão: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Ocultar os marcadores de posição para elementos de matriz vazios Padrão: false |
| [getBaseJustification()](#getBaseJustification--) | Especifica a justificação vertical em relação ao texto ao redor. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Especifica a justificação vertical em relação ao texto ao redor. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Largura mínima da coluna em twips (1/20 de ponto) O espaçamento de lacuna (também chamado de \\u201cColumn Gap\\u201d ou \\u201cGap Width\\u201d) é adicionado ao MinColumnWidth para determinar o espaçamento total da coluna da matriz (distância entre as mesmas bordas de colunas diferentes). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Largura mínima da coluna em twips (1/20 de ponto) O espaçamento de lacuna (também chamado de \\u201cColumn Gap\\u201d ou \\u201cGap Width\\u201d) é adicionado ao MinColumnWidth para determinar o espaçamento total da coluna da matriz (distância entre as mesmas bordas de colunas diferentes). |
| [getColumnGapRule()](#getColumnGapRule--) | O tipo de espaçamento horizontal entre colunas de uma matriz; as unidades de espaçamento horizontal podem ser ems ou pontos (armazenados como twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | O tipo de espaçamento horizontal entre colunas de uma matriz; as unidades de espaçamento horizontal podem ser ems ou pontos (armazenados como twips). |
| [getColumnGap()](#getColumnGap--) | O valor do espaçamento horizontal entre colunas de uma matriz; Se o ColumnGapRule for definido como 3 ("Exactly"), a unidade é interpretada como twips (1/20 de ponto) Se o ColumnGapRule for definido como 4 ("Multiple"), a unidade é interpretada como número de incrementos de 0.5 em. |
| [setColumnGap(long value)](#setColumnGap-long-) | O valor do espaçamento horizontal entre colunas de uma matriz; Se o ColumnGapRule for definido como 3 ("Exactly"), a unidade é interpretada como twips (1/20 de ponto) Se o ColumnGapRule for definido como 4 ("Multiple"), a unidade é interpretada como número de incrementos de 0.5 em. |
| [getRowGapRule()](#getRowGapRule--) | O tipo de espaçamento vertical entre linhas de uma matriz; as unidades de espaçamento vertical podem ser linhas ou pontos (armazenados como twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | O tipo de espaçamento vertical entre linhas de uma matriz; as unidades de espaçamento vertical podem ser linhas ou pontos (armazenados como twips). |
| [getRowGap()](#getRowGap--) | O valor do espaçamento vertical entre linhas de uma matriz; Se o RowGapRule for definido como 3 ("Exactly"), a unidade é interpretada como twips (1/20 de ponto) Se o RowGapRule for definido como 4 ("Multiple"), a unidade é interpretada como meia linha. |
| [setRowGap(long value)](#setRowGap-long-) | O valor do espaçamento vertical entre linhas de uma matriz; Se o RowGapRule for definido como 3 ("Exactly"), a unidade é interpretada como twips (1/20 de ponto) Se o RowGapRule for definido como 4 ("Multiple"), a unidade é interpretada como meia linha. |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Obter o alinhamento horizontal da coluna especificada |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Definir o alinhamento horizontal da coluna especificada |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Definir o alinhamento horizontal das colunas especificadas |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Inserir uma nova linha antes da especificada. Inicialmente todos os elementos na nova linha são nulos. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Inserir uma nova linha após a especificada. Inicialmente todos os elementos na nova linha são nulos. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Exclui a linha especificada |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Inserir uma nova coluna antes da especificada. Inicialmente todos os elementos na nova coluna são nulos. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Inserir uma nova coluna após a especificada. Inicialmente todos os elementos na nova coluna são nulos. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Exclui a coluna especificada |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public abstract IMathElement get_Item(int row, int column)
```

Elementos da matriz

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
public abstract void set_Item(int row, int column, IMathElement value)
```

Elementos da matriz

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

### getRowCount() {#getRowCount--}
```
public abstract int getRowCount()
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
public abstract int getColumnCount()
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
public abstract boolean getHidePlaceholders()
```

Ocultar os marcadores de posição para elementos de matriz vazios Padrão: false

--------------------

> ```
> Exemplo:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Retorna:**
boolean

### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public abstract void setHidePlaceholders(boolean value)
```

Ocultar os marcadores de posição para elementos de matriz vazios Padrão: false

--------------------

> ```
> Exemplo:
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
public abstract int getBaseJustification()
```

Especifica a justificação vertical em relação ao texto ao redor. Valores possíveis são top, bottom e center. Padrão: Center

--------------------

> ```
> Exemplo:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Retorna:**
int

### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

Especifica a justificação vertical em relação ao texto ao redor. Valores possíveis são top, bottom e center. Padrão: Center

--------------------

> ```
> Exemplo:
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
public abstract long getMinColumnWidth()
```

Largura mínima da coluna em twips (1/20 de ponto) O espaçamento de lacuna (também chamado de \\u201cColumn Gap\\u201d ou \\u201cGap Width\\u201d) é adicionado ao MinColumnWidth para determinar o espaçamento total da coluna da matriz (distância entre as mesmas bordas de colunas diferentes). Padrão: 0.

--------------------

> ```
> Exemplo:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Retorna:**
long

### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public abstract void setMinColumnWidth(long value)
```

Largura mínima da coluna em twips (1/20 de ponto) O espaçamento de lacuna (também chamado de \\u201cColumn Gap\\u201d ou \\u201cGap Width\\u201d) é adicionado ao MinColumnWidth para determinar o espaçamento total da coluna da matriz (distância entre as mesmas bordas de colunas diferentes). Padrão: 0.

--------------------

> ```
> Exemplo:
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
public abstract int getColumnGapRule()
```

O tipo de espaçamento horizontal entre colunas de uma matriz; as unidades de espaçamento horizontal podem ser ems ou pontos (armazenados como twips). Padrão: SingleSpacingGap (0)

--------------------

> ```
> Exemplo:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Retorna:**
int

### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public abstract void setColumnGapRule(int value)
```

O tipo de espaçamento horizontal entre colunas de uma matriz; as unidades de espaçamento horizontal podem ser ems ou pontos (armazenados como twips). Padrão: SingleSpacingGap (0)

--------------------

> ```
> Exemplo:
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
public abstract long getColumnGap()
```

O valor do espaçamento horizontal entre colunas de uma matriz; Se o ColumnGapRule for definido como 3 ("Exactly"), a unidade é interpretada como twips (1/20 de ponto) Se o ColumnGapRule for definido como 4 ("Multiple"), a unidade é interpretada como número de incrementos de 0.5 em. Em outros casos, ignorado. Padrão: 0

--------------------

> ```
> Exemplo:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Retorna:**
long

### setColumnGap(long value) {#setColumnGap-long-}
```
public abstract void setColumnGap(long value)
```

O valor do espaçamento horizontal entre colunas de uma matriz; Se o ColumnGapRule for definido como 3 ("Exactly"), a unidade é interpretada como twips (1/20 de ponto) Se o ColumnGapRule for definido como 4 ("Multiple"), a unidade é interpretada como número de incrementos de 0.5 em. Em outros casos, ignorado. Padrão: 0

--------------------

> ```
> Exemplo:
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
public abstract int getRowGapRule()
```

O tipo de espaçamento vertical entre linhas de uma matriz; as unidades de espaçamento vertical podem ser linhas ou pontos (armazenados como twips). Padrão: SingleSpacingGap (0)

--------------------

> ```
> Exemplo:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Retorna:**
int

### setRowGapRule(int value) {#setRowGapRule-int-}
```
public abstract void setRowGapRule(int value)
```

O tipo de espaçamento vertical entre linhas de uma matriz; as unidades de espaçamento vertical podem ser linhas ou pontos (armazenados como twips). Padrão: SingleSpacingGap (0)

--------------------

> ```
> Exemplo:
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
public abstract long getRowGap()
```

O valor do espaçamento vertical entre linhas de uma matriz; Se o RowGapRule for definido como 3 ("Exactly"), a unidade é interpretada como twips (1/20 de ponto) Se o RowGapRule for definido como 4 ("Multiple"), a unidade é interpretada como meia linha. Padrão: 0

--------------------

> ```
> Exemplo:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Retorna:**
long

### setRowGap(long value) {#setRowGap-long-}
```
public abstract void setRowGap(long value)
```

O valor do espaçamento vertical entre linhas de uma matriz; Se o RowGapRule for definido como 3 ("Exactly"), a unidade é interpretada como twips (1/20 de ponto) Se o RowGapRule for definido como 4 ("Multiple"), a unidade é interpretada como meia linha. Padrão: 0

--------------------

> ```
> Exemplo:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |

### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public abstract int getColumnAlignment(int columnIndex)
```

Obter o alinhamento horizontal da coluna especificada

--------------------

> ```
> Exemplo:
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
public abstract void setColumnAlignment(int columnIndex, int val)
```

Definir o alinhamento horizontal da coluna especificada

--------------------

> ```
> Exemplo:
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
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Definir o alinhamento horizontal das colunas especificadas

--------------------

> ```
> Exemplo:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| columnIndex | int | Índice baseado em zero da primeira coluna a definir o alinhamento |
| columnsCount | long | O número de colunas para as quais definir o alinhamento |
| val | int | Novo valor do alinhamento horizontal da coluna especificada |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

Inserir uma nova linha antes da especificada. Inicialmente todos os elementos na nova linha são nulos.

--------------------

> ```
> Exemplo:
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
public abstract void insertRowAfter(int rowIndex)
```

Inserir uma nova linha após a especificada. Inicialmente todos os elementos na nova linha são nulos.

--------------------

> ```
> Exemplo:
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
public abstract void deleteRow(int rowIndex)
```

Exclui a linha especificada

--------------------

> ```
> Exemplo:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rowIndex | int | O índice baseado em zero da linha a excluir. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```

Inserir uma nova coluna antes da especificada. Inicialmente todos os elementos na nova coluna são nulos.

--------------------

> ```
> Exemplo:
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
public abstract void insertColumnAfter(int columnIndex)
```

Inserir uma nova coluna após a especificada. Inicialmente todos os elementos na nova coluna são nulos.

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
public abstract void deleteColumn(int columnIndex)
```

Exclui a coluna especificada

--------------------

> ```
> Exemplo:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| columnIndex | int | O índice baseado em zero da coluna a excluir. |