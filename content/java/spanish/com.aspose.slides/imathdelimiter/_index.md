---
title: IMathDelimiter
second_title: Referencia de API de Aspose.Slides para Java
description: Especifica el objeto delimitador que consiste en caracteres de apertura y cierre, como paréntesis, llaves, corchetes y barras verticales, y uno o más elementos matemáticos dentro, separados por un carácter especificado.
type: docs
url: /es/com.aspose.slides/imathdelimiter/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

Especifica el objeto delimitador, que consta de caracteres de apertura y cierre (como paréntesis, llaves, corchetes y barras verticales), y uno o más elementos matemáticos dentro, separados por un carácter especificado. Ejemplos: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```
## Métodos

| Método | Descripción |
| --- | --- |
| [getArguments()](#getArguments--) | Uno o más elementos matemáticos separados por caracteres delimitadores |
| [getBeginningCharacter()](#getBeginningCharacter--) | El carácter de inicio del delimitador especifica el carácter delimitador de comienzo, o de apertura. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | El carácter de inicio del delimitador especifica el carácter delimitador de comienzo, o de apertura. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | El carácter separador del delimitador especifica el carácter que separa los argumentos en el objeto delimitador. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | El carácter separador del delimitador especifica el carácter que separa los argumentos en el objeto delimitador. |
| [getEndingCharacter()](#getEndingCharacter--) | El carácter de fin del delimitador especifica el carácter delimitador de cierre, o final. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | El carácter de fin del delimitador especifica el carácter delimitador de cierre, o final. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Especifica el crecimiento de BeginningCharacter, SeparatorCharacter, EndingCharacter. Cuando es true, los delimitadores crecen verticalmente para coincidir con la altura del operando. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Especifica el crecimiento de BeginningCharacter, SeparatorCharacter, EndingCharacter. Cuando es true, los delimitadores crecen verticalmente para coincidir con la altura del operando. |
| [getDelimiterShape()](#getDelimiterShape--) | Especifica la forma de los delimitadores en el objeto delimitador. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Especifica la forma de los delimitadores en el objeto delimitador. |
| [delimit(char separatorCharacter)](#delimit-char-) | Delimita los argumentos utilizando el carácter delimitador especificado |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

Uno o más elementos matemáticos separados por caracteres delimitadores

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**Devuelve:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public abstract char getBeginningCharacter()
```

El carácter de inicio del delimitador especifica el carácter delimitador de comienzo, o de apertura. Los delimitadores matemáticos son caracteres de cierre como paréntesis, corchetes y llaves. El valor predeterminado: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Devuelve:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public abstract void setBeginningCharacter(char value)
```

El carácter de inicio del delimitador especifica el carácter delimitador de comienzo, o de apertura. Los delimitadores matemáticos son caracteres de cierre como paréntesis, corchetes y llaves. El valor predeterminado: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public abstract char getSeparatorCharacter()
```

El carácter separador del delimitador especifica el carácter que separa los argumentos en el objeto delimitador. El valor predeterminado: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Devuelve:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public abstract void setSeparatorCharacter(char value)
```

El carácter separador del delimitador especifica el carácter que separa los argumentos en el objeto delimitador. El valor predeterminado: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public abstract char getEndingCharacter()
```

El carácter de fin del delimitador especifica el carácter delimitador de cierre, o final. Los delimitadores matemáticos son caracteres de apertura como paréntesis, corchetes y llaves. El valor predeterminado: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Devuelve:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public abstract void setEndingCharacter(char value)
```

El carácter de fin del delimitador especifica el carácter delimitador de cierre, o final. Los delimitadores matemáticos son caracteres de apertura como paréntesis, corchetes y llaves. El valor predeterminado: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```

Especifica el crecimiento de BeginningCharacter, SeparatorCharacter, EndingCharacter. Cuando es true, los delimitadores crecen verticalmente para coincidir con la altura del operando. El valor predeterminado es true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Devuelve:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```

Especifica el crecimiento de BeginningCharacter, SeparatorCharacter, EndingCharacter. Cuando es true, los delimitadores crecen verticalmente para coincidir con la altura del operando. El valor predeterminado es true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public abstract int getDelimiterShape()
```

Especifica la forma de los delimitadores en el objeto delimitador. Cuando es MathDelimiterShape.Centered, los delimitadores se centran alrededor del eje matemático del texto y pueden ajustarse para cubrir toda la altura de su contenido. Cuando es MathDelimiterShape.Match, su altura y forma se modifican para coincidir exactamente con su contenido.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Devuelve:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public abstract void setDelimiterShape(int value)
```

Especifica la forma de los delimitadores en el objeto delimitador. Cuando es MathDelimiterShape.Centered, los delimitadores se centran alrededor del eje matemático del texto y pueden ajustarse para cubrir toda la altura de su contenido. Cuando es MathDelimiterShape.Match, su altura y forma se modifican para coincidir exactamente con su contenido.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Delimita los argumentos utilizando el carácter delimitador especificado

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| separatorCharacter | char | carácter delimitador |

**Devuelve:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Este objeto después de aplicar el carácter delimitador