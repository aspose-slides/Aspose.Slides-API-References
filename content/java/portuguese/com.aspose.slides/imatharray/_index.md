---
title: IMathArray
second_title: Referência da API Aspose.Slides for Java
description: Especifica um array vertical de equações ou quaisquer objetos matemáticos
type: docs
url: /pt/com.aspose.slides/imatharray/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

Especifica um array vertical de equações ou quaisquer objetos matemáticos

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Métodos

| Método | Descrição |
| --- | --- |
| [getArguments()](#getArguments--) | The set of items of the array |
| [getBaseJustification()](#getBaseJustification--) | Specifies alignment of the array relative to surrounding text Text outside of the array can be aligned with the bottom, top, or center of a array object. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Specifies alignment of the array relative to surrounding text Text outside of the array can be aligned with the bottom, top, or center of a array object. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maximum Distribution When true, the array is spaced to the maximum width of the containing element(page, column, cell, etc.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maximum Distribution When true, the array is spaced to the maximum width of the containing element(page, column, cell, etc.). |
| [getObjectDistribution()](#getObjectDistribution--) | Object Distribution When true, the contents of the array are spaced to the maximum width of the array object. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Object Distribution When true, the contents of the array are spaced to the maximum width of the array object. |
| [getRowSpacingRule()](#getRowSpacingRule--) | The type of vertical spacing between array elements |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | The type of vertical spacing between array elements |
| [getRowSpacing()](#getRowSpacing--) | Spacing between rows of an array It is used only when RowSpacingRule is set to 3 Exactly in which case the unit of measure is points or Multiple in which case the unit of measure is half-lines. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Spacing between rows of an array It is used only when RowSpacingRule is set to 3 Exactly in which case the unit of measure is points or Multiple in which case the unit of measure is half-lines. |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

O conjunto de itens do array

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**Retorna:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

Especifica o alinhamento do array em relação ao texto ao redor. Texto fora do array pode ser alinhado com a parte inferior, superior ou central de um objeto array. Valor padrão: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Retorna:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

Especifica o alinhamento do array em relação ao texto ao redor. Texto fora do array pode ser alinhado com a parte inferior, superior ou central de um objeto array. Valor padrão: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public abstract boolean getMaximumDistribution()
```

Distribuição Máxima Quando verdadeiro, o array é espaçado até a largura máxima do elemento contêiner (página, coluna, célula, etc.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Retorna:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public abstract void setMaximumDistribution(boolean value)
```

Distribuição Máxima Quando verdadeiro, o array é espaçado até a largura máxima do elemento contêiner (página, coluna, célula, etc.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public abstract boolean getObjectDistribution()
```

Distribuição de Objeto Quando verdadeiro, o conteúdo do array é espaçado até a largura máxima do objeto array.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Retorna:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public abstract void setObjectDistribution(boolean value)
```

Distribuição de Objeto Quando verdadeiro, o conteúdo do array é espaçado até a largura máxima do objeto array.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public abstract int getRowSpacingRule()
```

O tipo de espaçamento vertical entre os elementos do array

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Retorna:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public abstract void setRowSpacingRule(int value)
```

O tipo de espaçamento vertical entre os elementos do array

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public abstract long getRowSpacing()
```

Espaçamento entre linhas de um array. É usado somente quando RowSpacingRule está definido como 3. Exatamente nesse caso a unidade de medida é pontos ou Múltiplo, nesse caso a unidade de medida é meia linha. Padrão: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Retorna:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public abstract void setRowSpacing(long value)
```

Espaçamento entre linhas de um array. É usado somente quando RowSpacingRule está definido como 3. Exatamente nesse caso a unidade de medida é pontos ou Múltiplo, nesse caso a unidade de medida é meia linha. Padrão: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |