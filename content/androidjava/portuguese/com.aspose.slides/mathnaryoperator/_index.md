---
title: MathNaryOperator
second_title: Aspose.Slides para Android via Referência da API Java
description: Especifica um objeto matemático N-ário, como Somatório e Integral.
type: docs
url: /pt/com.aspose.slides/mathnaryoperator/
---
**Herança:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathNaryOperator](../../com.aspose.slides/imathnaryoperator), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathNaryOperator extends MathElementBase implements IMathNaryOperator, IHasControlCharacterProperties
```

Especifica um objeto matemático N-ário, como Somatório e Integral. Consiste em um operador, uma base (ou operando) e limites superior e inferior opcionais. Exemplos de operadores N-ários são: Somatório, União, Interseção, Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```
## Construtores

| Construtor | Descrição |
| --- | --- |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Inicializa uma nova instância da classe MathNaryOperator. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Inicializa uma nova instância da classe MathNaryOperator. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#MathNaryOperator-char-com.aspose.slides.IMathElement-) | Inicializa uma nova instância da classe MathNaryOperator. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getBase()](#getBase--) | Argumento base |
| [getSubscript()](#getSubscript--) | Especifica um argumento subscrito que, por exemplo, no caso de uma integral, define o limite inferior |
| [getSuperscript()](#getSuperscript--) | Especifica um argumento sobrescrito que, por exemplo, no caso de uma integral, define o limite superior |
| [getOperator()](#getOperator--) | Caractere do Operador N-ário Por exemplo: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Caractere do Operador N-ário Por exemplo: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | A localização dos limites (subscrito e sobrescrito) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | A localização dos limites (subscrito e sobrescrito) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | O Caractere do Operador cresce verticalmente para combinar com a altura do operando |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | O Caractere do Operador cresce verticalmente para combinar com a altura do operando |
| [getHideSubscript()](#getHideSubscript--) | Ocultar Subscrito |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Ocultar Subscrito |
| [getHideSuperscript()](#getHideSuperscript--) | Ocultar Sobrescrito |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Ocultar Sobrescrito |
| [getChildren()](#getChildren--) | Obter elementos filhos |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propriedades de Caracter de Controle |
### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


Inicializa uma nova instância da classe MathNaryOperator.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i=0"), new MathematicalText("\ud835\udc5b"));
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| operatorSymbol | char | Símbolo do operador N-ário |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argumento base |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite inferior |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite superior |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


Inicializa uma nova instância da classe MathNaryOperator.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i"));
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| operatorSymbol | char | Símbolo do operador N-ário |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argumento base |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite inferior |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#MathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


Inicializa uma nova instância da classe MathNaryOperator.

--------------------

> ```
> Exemplo:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"));
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| operatorSymbol | char | Símbolo do operador N-ário |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argumento base |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Argumento base

--------------------

> ```
> Exemplo:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
> ```

**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```


Especifica um argumento subscrito que, por exemplo, no caso de uma integral, define o limite inferior

--------------------

> ```
> Exemplo:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```


Especifica um argumento sobrescrito que, por exemplo, no caso de uma integral, define o limite superior

--------------------

> ```
> Exemplo:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperator() {#getOperator--}
```
public final char getOperator()
```


Caractere do Operador N-ário Por exemplo: '\\u2211', '\\u222b'

--------------------

> ```
> Exemplo:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Retorna:**
char
### setOperator(char value) {#setOperator-char-}
```
public final void setOperator(char value)
```


Caractere do Operador N-ário Por exemplo: '\\u2211', '\\u222b'

--------------------

> ```
> Exemplo:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public final int getLimitLocation()
```


A localização dos limites (subscrito e sobrescrito)

--------------------

> ```
> Exemplo:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Retorna:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public final void setLimitLocation(int value)
```


A localização dos limites (subscrito e sobrescrito)

--------------------

> ```
> Exemplo:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```


O Caractere do Operador cresce verticalmente para combinar com a altura do operando

--------------------

> ```
> Exemplo:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Retorna:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```


O Caractere do Operador cresce verticalmente para combinar com a altura do operando

--------------------

> ```
> Exemplo:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public final boolean getHideSubscript()
```


Ocultar Subscrito

--------------------

> ```
> Exemplo:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Retorna:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public final void setHideSubscript(boolean value)
```


Ocultar Subscrito

--------------------

> ```
> Exemplo:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public final boolean getHideSuperscript()
```


Ocultar Sobrescrito

--------------------

> ```
> Exemplo:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Retorna:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public final void setHideSuperscript(boolean value)
```


Ocultar Sobrescrito

--------------------

> ```
> Exemplo:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Obter elementos filhos

**Retorna:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Propriedades de Caracter de Controle

**Retorna:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps