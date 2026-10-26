---
title: MathDelimiter
second_title: Referencia de API de Aspose.Slides para Java
description: Especifica el objeto delimitador compuesto por caracteres de apertura y cierre, como paréntesis, llaves, corchetes y barras verticales, y uno o más elementos matemáticos dentro separados por un carácter especificado.
type: docs
url: /es/com.aspose.slides/mathdelimiter/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**  
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

Especifica el objeto delimitador, que consiste en caracteres de apertura y cierre (como paréntesis, llaves, corchetes y barras verticales), y uno o más elementos matemáticos dentro, separados por un carácter especificado. Ejemplos: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | Inicializa MathDelimiter con el elemento especificado como argumento base único |
## Métodos

| Método | Descripción |
| --- | --- |
| [getArguments()](#getArguments--) | Uno o más elementos matemáticos separados por caracteres delimitadores |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character especifica el carácter de inicio, o de apertura, del delimitador. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character especifica el carácter de inicio, o de apertura, del delimitador. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character especifica el carácter que separa los argumentos en el objeto delimitador. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character especifica el carácter que separa los argumentos en el objeto delimitador. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character especifica el carácter de fin, o de cierre, del delimitador. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character especifica el carácter de fin, o de cierre, del delimitador. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Especifica el crecimiento de BeginningCharacter, SeparatorCharacter, EndingCharacter. Cuando es true, los delimitadores crecen verticalmente para coincidir con la altura del operando. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Especifica el crecimiento de BeginningCharacter, SeparatorCharacter, EndingCharacter. Cuando es true, los delimitadores crecen verticalmente para coincidir con la altura del operando. |
| [getDelimiterShape()](#getDelimiterShape--) | Especifica la forma de los delimitadores en el objeto delimitador. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Especifica la forma de los delimitadores en el objeto delimitador. |
| [delimit(char separatorCharacter)](#delimit-char-) | Delimita argumentos usando el carácter delimitador especificado |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Encierra un elemento matemático en caracteres especificados, como paréntesis u otros caracteres como marco |
| [getChildren()](#getChildren--) | Obtiene los elementos hijos |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propiedades de carácter de control |
### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```


Inicializa MathDelimiter con el elemento especificado como argumento base único

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```


**Parámetros:**  
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | El elemento base al que se aplica el delimitador. Puede ser null. |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
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
public final char getBeginningCharacter()
```


Delimiter Beginning Character especifica el carácter de inicio, o de apertura, del delimitador. Los delimitadores matemáticos son caracteres de cierre como paréntesis, corchetes y llaves. El valor predeterminado: '('.

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
public final void setBeginningCharacter(char value)
```


Delimiter Beginning Character especifica el carácter de inicio, o de apertura, del delimitador. Los delimitadores matemáticos son caracteres de cierre como paréntesis, corchetes y llaves. El valor predeterminado: '('.

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
public final char getSeparatorCharacter()
```


Delimiter Separator Character especifica el carácter que separa los argumentos en el objeto delimitador. El valor predeterminado: '|'.

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
public final void setSeparatorCharacter(char value)
```


Delimiter Separator Character especifica el carácter que separa los argumentos en el objeto delimitador. El valor predeterminado: '|'.

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
public final char getEndingCharacter()
```


Delimiter Ending Character especifica el carácter de fin, o de cierre, del delimitador. Los delimitadores matemáticos son caracteres de cierre como paréntesis, corchetes y llaves. El valor predeterminado: ')'.

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
public final void setEndingCharacter(char value)
```


Delimiter Ending Character especifica el carácter de fin, o de cierre, del delimitador. Los delimitadores matemáticos son caracteres de cierre como paréntesis, corchetes y llaves. El valor predeterminado: ')'.

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
public final boolean getGrowToMatchOperandHeight()
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
public final void setGrowToMatchOperandHeight(boolean value)
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
public final int getDelimiterShape()
```


Especifica la forma de los delimitadores en el objeto delimitador. Cuando es MathDelimiterShape.Centered, los delimitadores se centran alrededor del eje matemático del texto y aún pueden ajustarse para cubrir toda la altura de su contenido. Cuando es MathDelimiterShape.Match, su altura y forma se modifican para coincidir exactamente con su contenido.

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
public final void setDelimiterShape(int value)
```


Especifica la forma de los delimitadores en el objeto delimitador. Cuando es MathDelimiterShape.Centered, los delimitadores se centran alrededor del eje matemático del texto y aún pueden ajustarse para cubrir toda la altura de su contenido. Cuando es MathDelimiterShape.Match, su altura y forma se modifican para coincidir exactamente con su contenido.

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
public final IMathDelimiter delimit(char separatorCharacter)
```


Delimita argumentos usando el carácter delimitador especificado

**Parámetros:**  
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| separatorCharacter | char | carácter delimitador |

**Devuelve:**  
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Este objeto después de aplicar el carácter delimitador
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```


Encierra un elemento matemático en caracteres especificados, como paréntesis u otros caracteres como marco

--------------------

> ```
> Example:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
> ```

**Parámetros:**  
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| beginningCharacter | char | Carácter inicial (usualmente corchete izquierdo) |
| endingCharacter | char | Carácter final (usualmente corchete derecho) |

**Devuelve:**  
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Si beginningCharacter y endingCharacter son null, solo se asignan los valores a las propiedades correspondientes y no se crea un nuevo objeto (devuelve esta instancia). De lo contrario, devuelve un nuevo elemento matemático de tipo Delimiter que incluye los caracteres especificados como marco y esta instancia de [MathDelimiter](../../com.aspose.slides/mathdelimiter) enmarcada dentro.
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Obtiene los elementos hijos

**Devuelve:**  
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Propiedades de carácter de control

**Devuelve:**  
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps