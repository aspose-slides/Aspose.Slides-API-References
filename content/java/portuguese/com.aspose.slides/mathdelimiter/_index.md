---
title: MathDelimiter
second_title: Referência da API Aspose.Slides para Java
description: Especifica o objeto delimitador composto por caracteres de abertura e fechamento, como parênteses, chaves, colchetes e barras verticais, e um ou mais elementos matemáticos dentro, separados por um caractere especificado.
type: docs
url: /pt/com.aspose.slides/mathdelimiter/
---
**Herança:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

Especifica o objeto delimitador, consistindo de caracteres de abertura e fechamento (como parênteses, chaves, colchetes e barras verticais), e um ou mais elementos matemáticos dentro, separados por um caractere especificado. Exemplos: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```
## Construtores

| Construtor | Descrição |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | Inicializa MathDelimiter com o elemento especificado como argumento base único |
## Métodos

| Método | Descrição |
| --- | --- |
| [getArguments()](#getArguments--) | Um ou mais elementos matemáticos separados por caracteres delimitadores |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character especifica o caractere inicial, ou de abertura, do delimitador. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character especifica o caractere inicial, ou de abertura, do delimitador. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character especifica o caractere que separa argumentos no objeto delimitador. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character especifica o caractere que separa argumentos no objeto delimitador. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character especifica o caractere final, ou de fechamento, do delimitador. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character especifica o caractere final, ou de fechamento, do delimitador. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Especifica o crescimento de BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando true, os delimitadores crescem verticalmente para combinar com a altura do operando. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Especifica o crescimento de BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando true, os delimitadores crescem verticalmente para combinar com a altura do operando. |
| [getDelimiterShape()](#getDelimiterShape--) | Especifica a forma dos delimitadores no objeto delimitador. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Especifica a forma dos delimitadores no objeto delimitador. |
| [delimit(char separatorCharacter)](#delimit-char-) | Delimita argumentos usando o caractere delimitador especificado |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Envolve um elemento matemático em caracteres especificados, como parênteses ou outros caracteres como moldura |
| [getChildren()](#getChildren--) | Obtém elementos filhos |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propriedades de Caractere de Controle |
### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```


Inicializa MathDelimiter com o elemento especificado como argumento base único

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | O elemento base ao qual o delimitador é aplicado. Pode ser nulo. |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```


Um ou mais elementos matemáticos separados por caracteres delimitadores

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**Retorna:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public final char getBeginningCharacter()
```


Delimiter Beginning Character especifica o caractere inicial, ou de abertura, do delimitador. Delimitadores matemáticos são caracteres de fechamento, como parênteses, colchetes e chaves. O padrão: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Retorna:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public final void setBeginningCharacter(char value)
```


Delimiter Beginning Character especifica o caractere inicial, ou de abertura, do delimitador. Delimitadores matemáticos são caracteres de fechamento, como parênteses, colchetes e chaves. O padrão: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public final char getSeparatorCharacter()
```


Delimiter Separator Character especifica o caractere que separa argumentos no objeto delimitador. O padrão: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Retorna:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public final void setSeparatorCharacter(char value)
```


Delimiter Separator Character especifica o caractere que separa argumentos no objeto delimitador. O padrão: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public final char getEndingCharacter()
```


Delimiter Ending Character especifica o caractere final, ou de fechamento, do delimitador. Delimitadores matemáticos são caracteres de fechamento, como parênteses, colchetes e chaves. O padrão: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Retorna:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public final void setEndingCharacter(char value)
```


Delimiter Ending Character especifica o caractere final, ou de fechamento, do delimitador. Delimitadores matemáticos são caracteres de fechamento, como parênteses, colchetes e chaves. O padrão: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```


Especifica o crescimento de BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando true, os delimitadores crescem verticalmente para combinar com a altura do operando. O valor padrão é true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Retorna:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```


Especifica o crescimento de BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando true, os delimitadores crescem verticalmente para combinar com a altura do operando. O valor padrão é true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public final int getDelimiterShape()
```


Especifica a forma dos delimitadores no objeto delimitador. Quando é MathDelimiterShape.Centered, os delimitadores são centralizados ao redor do eixo matemático do texto e ainda podem ser ajustados para caber toda a altura de seu conteúdo. Quando é MathDelimiterShape.Match, sua altura e forma são alteradas para corresponder exatamente ao conteúdo.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Retorna:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public final void setDelimiterShape(int value)
```


Especifica a forma dos delimitadores no objeto delimitador. Quando é MathDelimiterShape.Centered, os delimitadores são centralizados ao redor do eixo matemático do texto e ainda podem ser ajustados para caber toda a altura de seu conteúdo. Quando é MathDelimiterShape.Match, sua altura e forma são alteradas para corresponder exatamente ao conteúdo.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```


Delimita argumentos usando o caractere delimitador especificado

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| separatorCharacter | char | caractere delimitador |

**Retorna:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Este objeto após aplicar o caractere delimitador
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```


Envolve um elemento matemático em caracteres especificados, como parênteses ou outros caracteres como moldura

--------------------

> ```
> Example:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| beginningCharacter | char | Caractere inicial (geralmente colchete esquerdo) |
| endingCharacter | char | Caractere final (geralmente colchete direito) |

**Retorna:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Se beginningCharacter e endingCharacter forem nulos, as propriedades correspondentes recebem valores apenas e nenhum novo objeto é criado (retorna esta instância). Caso contrário, retorna um novo elemento matemático do tipo Delimiter que inclui os caracteres especificados como moldura e esta instância de [MathDelimiter](../../com.aspose.slides/mathdelimiter) enquadrada dentro.
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Obtém elementos filhos

**Retorna:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Propriedades de Caractere de Controle

**Retorna:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps