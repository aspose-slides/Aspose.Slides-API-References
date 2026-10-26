---
title: MathArray
second_title: Aspose.Slides para Android via Referência da API Java
description: Especifica um vetor vertical de equações ou quaisquer objetos matemáticos
type: docs
url: /pt/com.aspose.slides/matharray/
---
**Herança:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathArray](../../com.aspose.slides/imatharray)
```
public final class MathArray extends MathElementBase implements IMathArray
```

Especifica um vetor vertical de equações ou quaisquer objetos matemáticos

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Construtores

| Construtor | Descrição |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | Cria um array matemático e coloca o elemento especificado nele |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Cria um array matemático e coloca os elementos especificados nele |
## Métodos

| Método | Descrição |
| --- | --- |
| [getArguments()](#getArguments--) | O conjunto de itens do array |
| [getBaseJustification()](#getBaseJustification--) | Especifica o alinhamento do array em relação ao texto ao redor. Texto fora do array pode ser alinhado com a parte inferior, superior ou o centro de um objeto array. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Especifica o alinhamento do array em relação ao texto ao redor. Texto fora do array pode ser alinhado com a parte inferior, superior ou o centro de um objeto array. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Distribuição Máxima Quando true, o array é espaçado até a largura máxima do elemento contido (página, coluna, célula, etc.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Distribuição Máxima Quando true, o array é espaçado até a largura máxima do elemento contido (página, coluna, célula, etc.). |
| [getObjectDistribution()](#getObjectDistribution--) | Distribuição de Objeto Quando true, o conteúdo do array é espaçado até a largura máxima do objeto array. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Distribuição de Objeto Quando true, o conteúdo do array é espaçado até a largura máxima do objeto array. |
| [getRowSpacingRule()](#getRowSpacingRule--) | O tipo de espaçamento vertical entre os elementos do array. Padrão: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | O tipo de espaçamento vertical entre os elementos do array. Padrão: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | Espaçamento entre linhas de um array. É usado somente quando RowSpacingRule está definido como 3; exatamente nesse caso a unidade de medida é pontos, ou Multiple, quando a unidade de medida é meia linha. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Espaçamento entre linhas de um array. É usado somente quando RowSpacingRule está definido como 3; exatamente nesse caso a unidade de medida é pontos, ou Multiple, quando a unidade de medida é meia linha. |
| [getChildren()](#getChildren--) | Obter elementos filhos |
### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```

Cria um array matemático e coloca o elemento especificado nele

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | O elemento a ser colocado no array |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```

Cria um array matemático e coloca os elementos especificados nele

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Elementos a serem colocados no array |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
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
public final int getBaseJustification()
```

Especifica o alinhamento do array em relação ao texto ao redor. Texto fora do array pode ser alinhado com a parte inferior, superior ou o centro de um objeto array. Valor padrão: Center

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
public final void setBaseJustification(int value)
```

Especifica o alinhamento do array em relação ao texto ao redor. Texto fora do array pode ser alinhado com a parte inferior, superior ou o centro de um objeto array. Valor padrão: Center

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
public final boolean getMaximumDistribution()
```

Distribuição Máxima Quando true, o array é espaçado até a largura máxima do elemento contido (página, coluna, célula, etc.).

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
public final void setMaximumDistribution(boolean value)
```

Distribuição Máxima Quando true, o array é espaçado até a largura máxima do elemento contido (página, coluna, célula, etc.).

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
public final boolean getObjectDistribution()
```

Distribuição de Objeto Quando true, o conteúdo do array é espaçado até a largura máxima do objeto array.

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
public final void setObjectDistribution(boolean value)
```

Distribuição de Objeto Quando true, o conteúdo do array é espaçado até a largura máxima do objeto array.

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
public final int getRowSpacingRule()
```

O tipo de espaçamento vertical entre os elementos do array. Padrão: SingleLineGap

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
public final void setRowSpacingRule(int value)
```

O tipo de espaçamento vertical entre os elementos do array. Padrão: SingleLineGap

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
public final long getRowSpacing()
```

Espaçamento entre linhas de um array. É usado somente quando RowSpacingRule está definido como 3; exatamente nesse caso a unidade de medida é pontos, ou Multiple, quando a unidade de medida é meia linha. Padrão: 0

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
public final void setRowSpacing(long value)
```

Espaçamento entre linhas de um array. É usado somente quando RowSpacingRule está definido como 3; exatamente nesse caso a unidade de medida é pontos, ou Multiple, quando a unidade de medida é meia linha. Padrão: 0

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
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Obter elementos filhos

**Retorna:**
com.aspose.slides.IMathElement[]