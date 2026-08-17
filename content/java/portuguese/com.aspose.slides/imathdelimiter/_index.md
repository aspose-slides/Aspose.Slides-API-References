---
title: IMathDelimiter
second_title: Referência da API Aspose.Slides para Java
description: Especifica o objeto delimitador composto por caracteres de abertura e fechamento, como parênteses, chaves, colchetes e barras verticais, e um ou mais elementos matemáticos dentro, separados por um caractere especificado.
type: docs
url: /pt/com.aspose.slides/imathdelimiter/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

Especifica o objeto delimitador, consistindo de caracteres de abertura e fechamento (como parênteses, chaves, colchetes e barras verticais), e um ou mais elementos matemáticos dentro, separados por um caractere especificado. Exemplos: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
>  ```

## Métodos

| Método | Descrição |
| --- | --- |
| [getArguments()](#getArguments--) | Um ou mais elementos matemáticos separados por caracteres delimitadores |
| [getBeginningCharacter()](#getBeginningCharacter--) | O Delimiter Beginning Character especifica o caractere delimitador de início, ou abertura. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | O Delimiter Beginning Character especifica o caractere delimitador de início, ou abertura. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | O Delimiter Separator Character especifica o caractere que separa os argumentos no objeto delimitador. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | O Delimiter Separator Character especifica o caractere que separa os argumentos no objeto delimitador. |
| [getEndingCharacter()](#getEndingCharacter--) | O Delimiter Ending Character especifica o caractere delimitador de final, ou fechamento. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | O Delimiter Ending Character especifica o caractere delimitador de final, ou fechamento. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Especifica o crescimento de BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando verdadeiro, os delimitadores crescem verticalmente para corresponder à altura do operando. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Especifica o crescimento de BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando verdadeiro, os delimitadores crescem verticalmente para corresponder à altura do operando. |
| [getDelimiterShape()](#getDelimiterShape--) | Especifica a forma dos delimitadores no objeto delimitador. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Especifica a forma dos delimitadores no objeto delimitador. |
| [delimit(char separatorCharacter)](#delimit-char-) | Delimita argumentos usando o caractere delimitador especificado |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

Um ou mais elementos matemáticos separados por caracteres delimitadores

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
>  ```


**Retorna:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public abstract char getBeginningCharacter()
```

O Delimiter Beginning Character especifica o caractere delimitador de início, ou abertura. Delimitadores matemáticos são caracteres de fechamento como parênteses, colchetes e chaves. O valor padrão: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
>  ```

**Retorna:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public abstract void setBeginningCharacter(char value)
```

O Delimiter Beginning Character especifica o caractere delimitador de início, ou abertura. Delimitadores matemáticos são caracteres de fechamento como parênteses, colchetes e chaves. O valor padrão: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
>  ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public abstract char getSeparatorCharacter()
```

O Delimiter Separator Character especifica o caractere que separa os argumentos no objeto delimitador. O padrão: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
>  ```

**Retorna:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public abstract void setSeparatorCharacter(char value)
```

O Delimiter Separator Character especifica o caractere que separa os argumentos no objeto delimitador. O padrão: '|'.

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
public abstract char getEndingCharacter()
```

O Delimiter Ending Character especifica o caractere delimitador de final, ou fechamento. Delimitadores matemáticos são caracteres de fechamento como parênteses, colchetes e chaves. O valor padrão: ')'.

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
public abstract void setEndingCharacter(char value)
```

O Delimiter Ending Character especifica o caractere delimitador de final, ou fechamento. Delimitadores matemáticos são caracteres de fechamento como parênteses, colchetes e chaves. O valor padrão: ')'.

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
public abstract boolean getGrowToMatchOperandHeight()
```

Especifica o crescimento de BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando verdadeiro, os delimitadores crescem verticalmente para corresponder à altura do operando. O valor padrão é true

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
public abstract void setGrowToMatchOperandHeight(boolean value)
```

Especifica o crescimento de BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando verdadeiro, os delimitadores crescem verticalmente para corresponder à altura do operando. O valor padrão é true

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
public abstract int getDelimiterShape()
```

Especifica a forma dos delimitadores no objeto delimitador. Quando o MathDelimiterShape é Centered, os delimitadores são centralizados ao redor do eixo matemático do texto e ainda podem ser ajustados para caber em toda a altura de seu conteúdo. Quando o MathDelimiterShape é Match, sua altura e forma são alteradas para corresponder exatamente ao conteúdo.

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
public abstract void setDelimiterShape(int value)
```

Especifica a forma dos delimitadores no objeto delimitador. Quando o MathDelimiterShape é Centered, os delimitadores são centralizados ao redor do eixo matemático do texto e ainda podem ser ajustados para caber em toda a altura de seu conteúdo. Quando o MathDelimiterShape é Match, sua altura e forma são alteradas para corresponder exatamente ao conteúdo.

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
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Delimita argumentos usando o caractere delimitador especificado

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| separatorCharacter | char | caractere delimitador |

**Retorna:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Este objeto após a aplicação do caractere delimitador