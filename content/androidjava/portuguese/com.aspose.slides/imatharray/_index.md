---
title: IMathArray
second_title: Aspose.Slides para Android via Referência de API Java
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
| [getArguments()](#getArguments--) | O conjunto de itens do array |
| [getBaseJustification()](#getBaseJustification--) | Especifica o alinhamento do array em relação ao texto ao redor. Texto fora do array pode ser alinhado ao fundo, ao topo ou ao centro de um objeto array. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Especifica o alinhamento do array em relação ao texto ao redor. Texto fora do array pode ser alinhado ao fundo, ao topo ou ao centro de um objeto array. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Distribuição Máxima Quando verdadeiro, o array é espaçado até a largura máxima do elemento contêiner (página, coluna, célula, etc.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Distribuição Máxima Quando verdadeiro, o array é espaçado até a largura máxima do elemento contêiner (página, coluna, célula, etc.). |
| [getObjectDistribution()](#getObjectDistribution--) | Distribuição de Objeto Quando verdadeiro, o conteúdo do array é espaçado até a largura máxima do objeto array. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Distribuição de Objeto Quando verdadeiro, o conteúdo do array é espaçado até a largura máxima do objeto array. |
| [getRowSpacingRule()](#getRowSpacingRule--) | O tipo de espaçamento vertical entre os elementos do array |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | O tipo de espaçamento vertical entre os elementos do array |
| [getRowSpacing()](#getRowSpacing--) | Espaçamento entre linhas de um array. É usado apenas quando RowSpacingRule está definido como 3 Exactly, caso em que a unidade de medida é pontos ou Multiple, caso em que a unidade de medida é meia-linhas. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Espaçamento entre linhas de um array. É usado apenas quando RowSpacingRule está definido como 3 Exactly, caso em que a unidade de medida é pontos ou Multiple, caso em que a unidade de medida é meia-linhas. |
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

Especifica o alinhamento do array em relação ao texto ao redor. Texto fora do array pode ser alinhado ao fundo, ao topo ou ao centro de um objeto array. Valor padrão: Center

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

Especifica o alinhamento do array em relação ao texto ao redor. Texto fora do array pode ser alinhado ao fundo, ao topo ou ao centro de um objeto array. Valor padrão: Center

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

Espaçamento entre linhas de um array. É usado apenas quando RowSpacingRule está definido como 3 Exactly, caso em que a unidade de medida é pontos ou Multiple, caso em que a unidade de medida é meia-linhas. Padrão: 0

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

Espaçamento entre linhas de um array. É usado apenas quando RowSpacingRule está definido como 3 Exactly, caso em que a unidade de medida é pontos ou Multiple, caso em que a unidade de medida é meia-linhas. Padrão: 0

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