---
title: IMathDelimiter
second_title: Aspose.Slides para Android via Referência da API Java
description: Especifica o objeto delimitador composto por caracteres de abertura e fechamento, como parênteses, chaves, colchetes e barras verticais, e um ou mais elementos matemáticos internos separados por um caractere especificado.
type: docs
url: /pt/com.aspose.slides/imathdelimiter/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

Specifica o objeto delimitador, consistindo de caracteres de abertura e fechamento (como parênteses, chaves, colchetes e barras verticais) e um ou mais elementos matemáticos dentro, separados por um caractere especificado. Exemplos: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```
## Métodos

| Método | Descrição |
| --- | --- |
| [getArguments()](#getArguments--) | Um ou mais elementos matemáticos separados por caracteres delimitadores |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character especifica o caractere delimitador inicial, ou de abertura. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character especifica o caractere delimitador inicial, ou de abertura. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character especifica o caractere que separa argumentos no objeto delimitador. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character especifica o caractere que separa argumentos no objeto delimitador. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character especifica o caractere delimitador final, ou de fechamento. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character especifica o caractere delimitador final, ou de fechamento. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter Quando true, os delimitadores crescem verticalmente para corresponder à altura do operando. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter Quando true, os delimitadores crescem verticalmente para corresponder à altura do operando. |
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
> ```

**Retorna:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public abstract char getBeginningCharacter()
```

Delimiter Beginning Character especifica o caractere delimitador inicial, ou de abertura. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. The default value: '('.

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
public abstract void setBeginningCharacter(char value)
```

Delimiter Beginning Character especifica o caractere delimitador inicial, ou de abertura. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. The default value: '('.

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
public abstract char getSeparatorCharacter()
```

Delimiter Separator Character especifica o caractere que separa argumentos no objeto delimitador. The default: '|'.

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
public abstract void setSeparatorCharacter(char value)
```

Delimiter Separator Character especifica o caractere que separa argumentos no objeto delimitador. The default: '|'.

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

Delimiter Ending Character especifica o caractere delimitador final, ou de fechamento. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. The default value: ')'.

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

Delimiter Ending Character especifica o caractere delimitador final, ou de fechamento. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. The default value: ')'.

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

Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter Quando true, os delimitadores crescem verticalmente para corresponder à altura do operando. The default value is true

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

Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter Quando true, os delimitadores crescem verticalmente para corresponder à altura do operando. The default value is true

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

Specifies the shape of delimiters in the delimiter object. When is MathDelimiterShape.Centered, delimiters are centered around the math axis of the mathematical text and still be made to fit the entire height of their contents. When is MathDelimiterShape.Match, their height and shape are altered to exactly match their contents.

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

Specifies the shape of delimiters in the delimiter object. When is MathDelimiterShape.Centered, delimiters are centered around the math axis of the mathematical text and still be made to fit the entire height of their contents. When is MathDelimiterShape.Match, their height and shape are altered to exactly match their contents.

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