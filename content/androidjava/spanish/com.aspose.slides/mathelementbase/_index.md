---
title: MathElementBase
second_title: Referencia de API Java de Aspose.Slides para Android
description: Clase base para IMathElement con la implementación de algunos métodos que son comunes a todas las clases heredadas. Solo para uso interno.
type: docs
url: /es/com.aspose.slides/mathelementbase/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

Clase base para IMathElement con la implementación de algunos métodos que son comunes a todas las clases heredadas. Solo para uso interno. La clase heredada debe ser IMathElement.
## Métodos

| Método | Descripción |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | Devuelve el objeto Parent_Immediate. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Une un elemento matemático y forma un bloque matemático |
| [join(String mathText)](#join-java.lang.String-) | Une un texto matemático y forma un bloque matemático |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Crea una fracción con este numerador y el denominador especificado |
| [divide(String denominator)](#divide-java.lang.String-) | Crea una fracción con este numerador y el denominador especificado |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [enclose()](#enclose--) | Encierra un elemento matemático entre paréntesis |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Encierra un elemento matemático en caracteres especificados, como paréntesis u otros caracteres como marco |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Toma una función de un argumento usando esta instancia como nombre de la función |
| [function(String functionArgument)](#function-java.lang.String-) | Toma una función de un argumento usando esta instancia como nombre de la función |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Toma la función especificada usando esta instancia como argumento |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Toma la función especificada usando esta instancia como argumento |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Toma la función especificada usando esta instancia como argumento |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Toma la función especificada usando esta instancia como argumento y un argumento adicional especificado |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Toma la función especificada usando esta instancia como argumento y un argumento adicional especificado |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Crea subíndice |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Crea subíndice |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Crea superíndice |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Crea superíndice |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crea subíndice y superíndice a la derecha |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Crea subíndice y superíndice a la derecha |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crea subíndice y superíndice a la izquierda |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Crea subíndice y superíndice a la izquierda |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Especifica la raíz matemática del grado dado a partir del argumento especificado. |
| [radical(String degree)](#radical-java.lang.String-) | Especifica la raíz matemática del grado dado a partir del argumento especificado. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Toma límite superior |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Toma límite superior |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Toma límite inferior |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Toma límite inferior |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crea un operador N-ario |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | Crea un operador N-ario |
| [toMathArray()](#toMathArray--) | Coloca en una matriz vertical |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Toma la integral |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Toma la integral |
| [integral(int integralType)](#integral-int-) | Toma la integral sin límites |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | Toma la integral |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | Toma la integral |
| [accent(char accentCharacter)](#accent-char-) | Establece una marca de acento (un carácter en la parte superior de este elemento) |
| [overbar()](#overbar--) | Establece una barra en la parte superior de este elemento |
| [underbar()](#underbar--) | Establece una barra en la parte inferior de este elemento |
| [group()](#group--) | Coloca este elemento en un grupo usando una llave inferior |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Coloca este elemento en un grupo usando un carácter de agrupación como una llave inferior u otro |
| [toBorderBox()](#toBorderBox--) | Coloca este elemento en un cuadro de borde |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Coloca este elemento en un cuadro de borde |
| [toBox()](#toBox--) | Coloca este elemento en una caja no visual (agrupación lógica) que se usa para agrupar componentes de una ecuación u otra instancia de texto matemático. |
| [getChildren()](#getChildren--) | Obtiene elementos hijos |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Devuelve el objeto Parent_Immediate. Solo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Une un elemento matemático y forma un bloque matemático

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | El elemento que se va a unir |

**Devuelve:**
[IMathBlock](../../com.aspose.slides/imathblock) - Un nuevo IMathBlock que contiene esta instancia y el argumento especificado

### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Une un texto matemático y forma un bloque matemático

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathText | java.lang.String | Texto matemático que se va a unir |

**Devuelve:**
[IMathBlock](../../com.aspose.slides/imathblock) - Un nuevo IMathBlock que contiene esta instancia y el argumento especificado

### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public final IMathFraction divide(IMathElement denominator)
```

Crea una fracción con este numerador y el denominador especificado

--------------------

> ```
> Ejemplo:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMMathFraction fraction = numerator.divide(denumerator);
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominador |

**Devuelve:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nueva fracción

### divide(String denominator) {#divide-java.lang.String-}
```
public final IMathFraction divide(String denominator)
```

Crea una fracción con este numerador y el denominador especificado

--------------------

> ```
> Ejemplo:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| denominator | java.lang.String | Denominador |

**Devuelve:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nueva fracción

### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction divide(IMathElement denominator, int fractionType)
```

Crea una fracción del tipo especificado con este numerador y el denominador especificado

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominador |
| fractionType | int | Tipo de fracción: Bar, NoBar, Skewed, Linear |

**Devuelve:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nueva fracción

### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public final IMathFraction divide(String denominator, int fractionType)
```

Crea una fracción del tipo especificado con este numerador y el denominador especificado

--------------------

> ```
> Ejemplo:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| denominator | java.lang.String | Denominador |
| fractionType | int | Tipo de fracción: Bar, NoBar, Skewed, Linear |

**Devuelve:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nueva fracción

### enclose() {#enclose--}
```
public final IMathDelimiter enclose()
```

Encierra un elemento matemático entre paréntesis

--------------------

> ```
> Ejemplo:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```


**Devuelve:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - El elemento matemático de tipo [IMathDelimiter](../../com.aspose.slides/imathdelimiter) que incluye los paréntesis

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Encierra un elemento matemático en caracteres especificados, como paréntesis u otros caracteres como marco

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| beginningCharacter | char | Carácter inicial (usualmente corchete izquierdo) |
| endingCharacter | char | Carácter final (usualmente corchete derecho) |

**Devuelve:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - El elemento matemático de tipo [IMathDelimiter](../../com.aspose.slides/imathdelimiter) que incluye los caracteres especificados como marco

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```

Toma una función de un argumento usando esta instancia como nombre de la función

--------------------

> ```
> Ejemplo:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | Un argumento de la función |

**Devuelve:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nuevo elemento matemático de tipo [IMathFunction](../../com.aspose.slides/imathfunction)

### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```

Toma una función de un argumento usando esta instancia como nombre de la función

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionArgument | java.lang.String | Un argumento de la función |

**Devuelve:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nuevo elemento matemático de tipo [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```

Toma la función especificada usando esta instancia como argumento

--------------------

> ```
> Ejemplo:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | Nombre de la función |

**Devuelve:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nuevo elemento matemático de tipo [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(String functionName)
```

Toma la función especificada usando esta instancia como argumento

--------------------

> ```
> Ejemplo:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionName | java.lang.String | Nombre de la función |

**Devuelve:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nuevo elemento matemático de tipo [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public final IMathFunction asArgumentOfFunction(int functionType)
```

Toma la función especificada usando esta instancia como argumento

--------------------

> ```
> Ejemplo:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionType | int | Uno de los tipos comunes de función de un argumento |

**Devuelve:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nuevo elemento matemático de tipo [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

Toma la función especificada usando esta instancia como argumento y un argumento adicional especificado

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Devuelve el logaritmo de 'x' a la base '5'
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionType | int | Uno de los tipos comunes de función de dos argumentos: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argumento adicional según el tipo de función |

**Devuelve:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nuevo elemento matemático de tipo [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

Toma la función especificada usando esta instancia como argumento y un argumento adicional especificado

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Devuelve el logaritmo de 'x' a la base '5'
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionType | int | Uno de los tipos comunes de función de dos argumentos: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | Argumento adicional según el tipo de función |

**Devuelve:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nuevo elemento matemático de tipo [IMathFunction](../../com.aspose.slides/imathfunction)

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```

Crea subíndice

--------------------

> ```
> Ejemplo:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subíndice (índice inferior a la derecha) |

**Devuelve:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Nuevo elemento matemático de tipo [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```

Crea subíndice

--------------------

> ```
> Ejemplo:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| subscript | java.lang.String | Subíndice (índice inferior a la derecha) |

**Devuelve:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Nuevo elemento matemático de tipo [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

Crea superíndice

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Superíndice (índice superior a la derecha) |

**Devuelve:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Nuevo elemento matemático de tipo [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```

Crea superíndice

--------------------

> ```
> Ejemplo:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| superscript | java.lang.String | Superíndice (índice superior a la derecha) |

**Devuelve:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Nuevo elemento matemático de tipo [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

Crea subíndice y superíndice a la derecha

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subíndice (índice inferior a la derecha) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Superíndice (índice superior a la derecha) |

**Devuelve:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Nuevo elemento matemático de tipo [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

Crea subíndice y superíndice a la derecha

--------------------

> ```
> Ejemplo:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| subscript | java.lang.String | Subíndice (índice inferior a la derecha) |
| superscript | java.lang.String | Superíndice (índice superior a la derecha) |

**Devuelve:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Nuevo elemento matemático de tipo [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Crea subíndice y superíndice a la izquierda

--------------------

> ```
> Ejemplo:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subíndice (índice inferior a la izquierda) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Superíndice (índice superior a la izquierda) |

**Devuelve:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Nuevo elemento matemático de tipo [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)

### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Crea subíndice y superíndice a la izquierda

--------------------

> ```
> Ejemplo:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| subscript | java.lang.String | Subíndice (índice inferior a la izquierda) |
| superscript | java.lang.String | Superíndice (índice superior a la izquierda) |

**Devuelve:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Nuevo elemento matemático de tipo [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)

### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

Especifica la raíz matemática del grado dado a partir del argumento especificado.

--------------------

> ```
> Ejemplo:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMMathRadical radical = baseElement.radical(degree);
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Argumento del radical |

**Devuelve:**
[IMathRadical](../../com.aspose.slides/imathradical) - Nueva instancia de tipo [IMathRadical](../../com.aspose.slides/imathradical)

### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```

Especifica la raíz matemática del grado dado a partir del argumento especificado.

--------------------

> ```
> Ejemplo:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| degree | java.lang.String | Argumento del radical |

**Devuelve:**
[IMathRadical](../../com.aspose.slides/imathradical) - Nueva instancia de tipo [IMathRadical](../../com.aspose.slides/imathradical)

### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```

Toma límite superior

--------------------

> ```
> Ejemplo:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | límite |

**Devuelve:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nueva instancia de tipo [IMathLimit](../../com.aspose.slides/imathlimit)

### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```

Toma límite superior

--------------------

> ```
> Ejemplo:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| limit | java.lang.String | límite |

**Devuelve:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nueva instancia de tipo [IMathLimit](../../com.aspose.slides/imathlimit)

### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

Toma límite inferior

--------------------

> ```
> Ejemplo:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | límite |

**Devuelve:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nueva instancia de tipo [IMathLimit](../../com.aspose.slides/imathlimit)

### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

Toma límite inferior

--------------------

> ```
> Ejemplo:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| limit | java.lang.String | límite |

**Devuelve:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nueva instancia de tipo [IMathLimit](../../com.aspose.slides/imathlimit)

### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

Crea un operador N-ario

--------------------

> ```
> Ejemplo:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | Tipo del operador N-ario |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Límite inferior |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Límite superior |

**Devuelve:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nueva instancia de tipo [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

Crea un operador N-ario

--------------------

> ```
> Ejemplo:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | Tipo del operador N-ario |
| lowerLimit | java.lang.String | Límite inferior |
| upperLimit | java.lang.String | Límite superior |

**Devuelve:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nueva instancia de tipo [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Coloca en una matriz vertical

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Devuelve:**
[IMathArray](../../com.aspose.slides/imatharray) - Nueva instancia de tipo [IMathArray](../../com.aspose.slides/imatharray)

### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

Toma la integral

--------------------

> ```
> Ejemplo:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| integralType | int | Tipo de integral |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Límite inferior de la integral |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Límite superior de la integral |
| limitLocations | int | ubicación de los límites |

**Devuelve:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nueva instancia de tipo [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

Toma la integral

--------------------

> ```
> Ejemplo:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| integralType | int | Tipo de integral |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Límite inferior de la integral |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Límite superior de la integral |

**Devuelve:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nueva instancia de tipo [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

Toma la integral sin límites

--------------------

> ```
> Ejemplo:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| integralType | int | Tipo de integral |

**Devuelve:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nueva instancia de tipo [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

Toma la integral

--------------------

> ```
> Ejemplo:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| integralType | int | Tipo de integral |
| lowerLimit | java.lang.String | Límite inferior de la integral |
| upperLimit | java.lang.String | Límite superior de la integral |
| limitLocations | int | ubicación de los límites |

**Devuelve:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nueva instancia de tipo [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

Toma la integral

--------------------

> ```
> Ejemplo:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| integralType | int | Tipo de integral |
| lowerLimit | java.lang.String | Límite inferior de la integral |
| upperLimit | java.lang.String | Límite superior de la integral |

**Devuelve:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nueva instancia de tipo [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

Establece una marca de acento (un carácter en la parte superior de este elemento)

--------------------

> ```
> Ejemplo:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| accentCharacter | char | Carácter de acento. El valor debe estar dentro del rango (U+0300-U+036F) o (U+20D0-U+20EF) |

**Devuelve:**
[IMathAccent](../../com.aspose.slides/imathaccent) - Nueva instancia de tipo [IMathAccent](../../com.aspose.slides/imathaccent)

### overbar() {#overbar--}
```
public final IMathBar overbar()
```

Establece una barra en la parte superior de este elemento

--------------------

> ```
public final IMathBar overbar()
```

**Devuelve:**
[IMathBar](../../com.aspose.slides/imathbar) - Nueva instancia de tipo [IMathBar](../../com.aspose.slides/imathbar)

### underbar() {#underbar--}
```
public final IMathBar underbar()
```

Establece una barra en la parte inferior de este elemento

--------------------

> ```
> Ejemplo:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Devuelve:**
[IMathBar](../../com.aspose.slides/imathbar) - Nueva instancia de tipo [IMathBar](../../com.aspose.slides/imathbar)

### group() {#group--}
```
public final IMathGroupingCharacter group()
```

Coloca este elemento en un grupo usando una llave inferior

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**Devuelve:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Nueva instancia de tipo [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)

### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Coloca este elemento en un grupo usando un carácter de agrupación como una llave inferior u otro

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| character | char | Carácter de agrupación como LLAVE INFERIOR (U+23DF) u otro |
| position | int | Posición del carácter de agrupación |
| verticalJustification | int | Justificación vertical del carácter de grupo. Especifica la alineación del objeto respecto a la línea base. Por ejemplo, cuando el carácter de grupo está sobre el objeto, VerticalJustification de Top indica que la parte superior del objeto cae en la línea base; cuando VerticalJustification es Bottom, la parte inferior del objeto está en la línea base |

**Devuelve:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Nueva instancia de tipo [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)

### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

Coloca este elemento en un cuadro de borde

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Devuelve:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Cuadro de borde con este elemento colocado dentro

### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Coloca este elemento en un cuadro de borde

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hideTop | boolean | Ocultar borde superior |
| hideBottom | boolean | Ocultar borde inferior |
| hideLeft | boolean | Ocultar borde izquierdo |
| hideRight | boolean | Ocultar borde derecho |
| strikethroughHorizontal | boolean | Tachar horizontalmente el cuadro de borde |
| strikethroughVertical | boolean | Tachar verticalmente el cuadro de borde |
| strikethroughBottomLeftToTopRight | boolean | Tachar diagonal de abajo-izquierda a arriba-derecha |
| strikethroughTopLeftToBottomRight | boolean | Tachar diagonal de arriba-izquierda a abajo-derecha |

**Devuelve:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Cuadro de borde con este elemento colocado dentro

### toBox() {#toBox--}
```
public final IMathBox toBox()
```

Coloca este elemento en una caja no visual (agrupación lógica) que se usa para agrupar componentes de una ecuación u otra instancia de texto matemático. Un objeto encerrado puede (por ejemplo) servir como emulador de operador con o sin punto de alineación, servir como punto de salto de línea, o agruparse de modo que no se permitan saltos de línea dentro.

--------------------

> ```
> Ejemplo:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**Devuelve:**
[IMathBox](../../com.aspose.slides/imathbox) - Caja lógica con este elemento colocado dentro

### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

Obtiene elementos hijos

**Devuelve:**
com.aspose.slides.IMathElement[] - Matriz de [IMathElement](../../com.aspose.slides/imathelement)