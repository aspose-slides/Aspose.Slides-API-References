---
title: IMathElement
second_title: Aspose.Slides for Android via Java API Reference
description: Interface de base de tout élément mathématique : fraction, texte mathématique, fonction, expression avec plusieurs éléments, etc.
type: docs
url: /fr/com.aspose.slides/imathelement/
---```
public interface IMathElement
```

Interface de base de tout élément mathématique : fraction, texte mathématique, fonction, expression avec plusieurs éléments, etc

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
> ```
## Methods

| Method | Description |
| --- | --- |
| [getChildren()](#getChildren--) | Get children elements |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Joins a mathematical element and forms a mathematical block |
| [join(String mathText)](#join-java.lang.String-) | Joins a mathematical text and forms a mathematical block |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Creates a fraction with this numerator and specified denominator |
| [divide(String denominator)](#divide-java.lang.String-) | Creates a fraction with this numerator and specified denominator |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Creates a fraction of the specified type with this numerator and specified denominator |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Creates a fraction of the specified type with this numerator and specified denominator |
| [enclose()](#enclose--) | Enclose a math element in parenthesis |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Encloses this element in specified characters such as parenthesis or another characters as framing |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Takes a function of an argument using this instance as the function name |
| [function(String functionArgument)](#function-java.lang.String-) | Takes a function of an argument using this instance as the function name |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Takes specified function using this instance as the argument |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Takes specified function using this instance as the argument |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Takes specified function using this instance as the argument |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Takes specified function using this instance as the argument and specified additional argument |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Takes specified function using this instance as the argument and specified additional argument |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Creates subscript |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Creates subscript |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Creates superscript |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Creates superscript |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates subscript and superscript on the right |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Creates subscript and superscript on the right |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates subscript and superscript on the left |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Creates subscript and superscript on the left |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Specifies the mathematical root of the given degree from the specified argument. |
| [radical(String degree)](#radical-java.lang.String-) | Specifies the mathematical root of the given degree from the specified argument. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Takes upper limit |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Takes upper limit |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Takes lower limit |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Takes lower limit |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates a N-ary operator |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | Creates a N-ary operator |
| [toMathArray()](#toMathArray--) | Puts in a vertical array |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Takes the integral |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Takes the integral |
| [integral(int integralType)](#integral-int-) | Takes the integral without limits |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | Takes the integral |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | Takes the integral |
| [accent(char accentCharacter)](#accent-char-) | Sets an accent mark (a character on the top of this element) |
| [overbar()](#overbar--) | Sets a bar on the top of this element |
| [underbar()](#underbar--) | Sets a bar on the bottom of this element |
| [group()](#group--) | Places this element in a group using a bottom curly bracket |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Places this element in a group using a grouping character such as bottom curly bracket or another |
| [toBorderBox()](#toBorderBox--) | Places this element in a border-box |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Places this element in a border-box |
| [toBox()](#toBox--) | Places this element in a non-visual box (logical grouping) which is used to group components of an equation or other instance of mathematical text. |
### getChildren() {#getChildren--}
```
public abstract IMathElement[] getChildren()
```

Get children elements

**Returns:**
com.aspose.slides.IMathElement[]
### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock join(IMathElement mathElement)
```

Joins a mathematical element and forms a mathematical block

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | The element to be joined |

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - A new IMathBlock containing this instance and specified argument
### join(String mathText) {#join-java.lang.String-}
```
public abstract IMathBlock join(String mathText)
```

Joint un texte mathématique et forme un bloc mathématique

--------------------

> ```
> Exemple:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | Texte mathématique à joindre |

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - Un nouveau IMathBlock contenant cette instance et l'argument spécifié
### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction divide(IMathElement denominator)
```

Crée une fraction avec ce numérateur et le dénominateur spécifié

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Dénominateur |

**Returns:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nouvelle fraction
### divide(String denominator) {#divide-java.lang.String-}
```
public abstract IMathFraction divide(String denominator)
```

Creates a fraction with this numerator and specified denominator

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| denominator | java.lang.String | Denominator |

**Returns:**
[IMathFraction](../../com.aspose.slides/imathfraction) - new fraction
### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction divide(IMathElement denominator, int fractionType)
```

Crée une fraction du type spécifié avec ce numérateur et le dénominateur indiqué

--------------------

> ```
> Exemple:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Dénominateur |
| fractionType | int | Type de fraction : Bar, NoBar, Skewed, Linear |

**Retourne:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nouvelle fraction
### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public abstract IMathFraction divide(String denominator, int fractionType)
```

Crée une fraction du type spécifié avec ce numérateur et le dénominateur indiqué

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| denominator | java.lang.String | Dénominateur |
| fractionType | int | Type de fraction : Bar, NoBar, Skewed, Linear |

**Retourne:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nouvelle fraction
### enclose() {#enclose--}
```
public abstract IMathDelimiter enclose()
```

Encapsule un élément mathématique entre parenthèses

--------------------

> ```
> Exemple :
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**Retourne :**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - L'élément mathématique de type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) qui inclut les parenthèses
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Encadre cet élément avec des caractères spécifiés comme des parenthèses ou d’autres caractères comme encadrement

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| beginningCharacter | char | Caractère de début (généralement crochet ouvrant) |
| endingCharacter | char | Caractère de fin (généralement crochet fermant) |

**Retourne :**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - L'élément mathématique de type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) qui inclut les caractères spécifiés comme encadrement
### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction function(IMathElement functionArgument)
```

Prend une fonction d’un argument en utilisant cette instance comme nom de fonction

--------------------

> ```
> Exemple :
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | Un argument de la fonction |

**Retourne:** [IMathFunction](../../com.aspose.slides/imathfunction) - Nouvel élément mathématique de type [IMathFunction](../../com.aspose.slides/imathfunction)
### function(String functionArgument) {#function-java.lang.String-}
```
public abstract IMathFunction function(String functionArgument)
```

Prend une fonction d’un argument en utilisant cette instance comme nom de fonction

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| functionArgument | java.lang.String | Un argument de la fonction |

**Returns:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nouvel élément mathématique de type [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(IMathElement functionName)
```

Prend la fonction spécifiée en utilisant cette instance comme argument

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | Nom de la fonction |

**Retourne :**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nouvel élément mathématique de type [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(String functionName)
```

Prend la fonction spécifiée en utilisant cette instance comme argument

--------------------

> ```
> Exemple :
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| functionName | java.lang.String | Nom de la fonction |

**Retourne :**
[IMathFunction](../../com.aspose.slides/imathfunction) - New math element of type [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType)
```

Prend la fonction spécifiée en utilisant cette instance comme argument

--------------------

> ```
> Exemple :
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
> ```

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| functionType | int | Un des types de fonction courants à un argument |

**Retourne :**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nouvel élément mathématique de type [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

Prend la fonction spécifiée en utilisant cette instance comme argument et l'argument supplémentaire spécifié

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Renvoie le logarithme de 'x' à la base '5'
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| functionType | int | One of the common function type of two arguments: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Additional argument depending on the type of function |

**Returns:**
[IMathFunction](../../com.aspose.slides/imathfunction) - New math element of type [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

Prend la fonction spécifiée en utilisant cette instance comme argument et l'argument supplémentaire spécifié

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Renvoie le logarithme de 'x' à la base '5'
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| functionType | int | One of the common function type of two arguments: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | Additional argument depending on the type of function |

**Returns:**
[IMathFunction](../../com.aspose.slides/imathfunction) - New math element of type [IMathFunction](../../com.aspose.slides/imathfunction)
### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSubscriptElement setSubscript(IMathElement subscript)
```

Crée un indice

--------------------

> ```
> Exemple :
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Indice (indice inférieur à droite) |

**Returns:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Nouvel élément mathématique de type [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public abstract IMathSubscriptElement setSubscript(String subscript)
```
Crée un indice

--------------------

> ```
> Exemple :
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | Indice (indice inférieur à droite) |

**Retourne :**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Nouvel élément mathématique de type [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSuperscriptElement setSuperscript(IMathElement superscript)
```
 
Crée un exposant

--------------------

> ```
> Exemple :
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
>  ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Exposant (indice supérieur à droite) |

**Retourne :**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Nouvel élément mathématique de type [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public abstract IMathSuperscriptElement setSuperscript(String superscript)
```

Crée un exposant

--------------------

> ```
> Exemple :
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
>  ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| superscript | java.lang.String | Superscript (upper index on the right) |

**Retourne :**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - New math element of type [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```
Crée un indice et un exposant à droite

--------------------

> ```
> Exemple :
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
>  ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Indice (indice inférieur à droite) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Exposant (indice supérieur à droite) |

**Retourne :**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Nouvel élément mathématique de type [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

Crée un indice et un exposant à droite

--------------------

> ```
> Exemple :
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | Indice (indice inférieur à droite) |
| superscript | java.lang.String | Exposant (indice supérieur à droite) |

**Returns:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Nouvel élément mathématique de type [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Creates subscript and superscript on the left

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subscript (lower index on the left) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Superscript (upper index on the left) |

**Returns:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - New math element of type [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Crée un indice et un exposant à gauche

--------------------

> ```
> Exemple :
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | Indice (indice inférieur à gauche) |
| superscript | java.lang.String | Exposant (indice supérieur à gauche) |

**Retourne :**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Nouvel élément mathématique de type [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public abstract IMathRadical radical(IMathElement degree)
```

Spécifie la racine mathématique du degré donné à partir de l'argument spécifié.

--------------------

> ```
> Exemple :
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
>  ```

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Argument du radical |

**Retourne:**
[IMathRadical](../../com.aspose.slides/imathradical) - Nouvelle instance du type [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public abstract IMathRadical radical(String degree)
```

Spécifie la racine mathématique du degré donné à partir de l'argument spécifié.

--------------------

> ```
> Exemple :
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| degree | java.lang.String | Argument of Radical |

**Retourne :**
[IMathRadical](../../com.aspose.slides/imathradical) - Nouvelle instance du type [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setUpperLimit(IMathElement limit)
```
Prend la limite supérieure

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Retourne :**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nouvelle instance du type [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public abstract IMathLimit setUpperLimit(String limit)
```

Prend la limite supérieure

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
>  ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Retourne :**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nouvelle instance du type [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setLowerLimit(IMathElement limit)
```

Prend la limite inférieure

--------------------

> ```
> Exemple :
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Retourne :**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nouvelle instance du type [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public abstract IMathLimit setLowerLimit(String limit)
```

Prend la limite inférieure

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
>  ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Retourne :**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nouvelle instance du type [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```
Crée un opérateur N-aire

--------------------

> ```
> Exemple :
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Le type d’opérateur N-aire |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | La limite inférieure |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | La limite supérieure |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nouvelle instance du type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```
Crée un opérateur N-aire

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | The N-ary operator type |
| lowerLimit | java.lang.String | The lower limit |
| upperLimit | java.lang.String | The upper limit |

**Retourne:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nouvelle instance du type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public abstract IMathArray toMathArray()
```

Place dans un tableau vertical

--------------------

> ```
> Exemple :
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
>  ```

**Retourne :**
[IMathArray](../../com.aspose.slides/imatharray) - Nouvelle instance du type [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

Prend l'intégrale

--------------------

> ```
> Exemple :
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| integralType | int | Type d'intégrale |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite inférieure de l'intégrale |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite supérieure de l'intégrale |
| limitLocations | int | emplacement des limites |

**Retourne :**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nouvelle instance du type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

Prend l'intégrale

--------------------

> ```
> Exemple :
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Type d'intégrale |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite inférieure de l'intégrale |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite supérieure de l'intégrale |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nouvelle instance du type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public abstract IMathNaryOperator integral(int integralType)
```


Prend l'intégrale sans limites

--------------------

> ```
> Exemple :
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
>  ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Type d'intégrale |

**Retourne :**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nouvelle instance du type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

Prend l'intégrale

--------------------

> ```
> Exemple :
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| integralType | int | Type d'intégrale |
| lowerLimit | java.lang.String | Limite inférieure de l'intégrale |
| upperLimit | java.lang.String | Limite supérieure de l'intégrale |
| limitLocations | int | emplacement des limites |

**Retourne :**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nouvelle instance du type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```


Takes the integral

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Integral type |
| lowerLimit | java.lang.String | Lower limit of integral |
| upperLimit | java.lang.String | Upper limit of integral |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public abstract IMathAccent accent(char accentCharacter)
```
Définit un accent (un caractère au-dessus de cet élément)

--------------------

> ```
> Exemple :
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| accentCharacter | char | Caractère d'accent. La valeur doit être dans la plage (U+0300\\u2013U+036F) ou (U+20D0\\u2013U+20EF) |

**Retourne :**
[IMathAccent](../../com.aspose.slides/imathaccent) - Nouvelle instance du type [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public abstract IMathBar overbar()
```

Définit une barre au sommet de cet élément

--------------------

> ```
> Exemple :
>  
>  IMathBar bar = new MathematicalText("x").overbar();
>  ```

**Retourne :**
[IMathBar](../../com.aspose.slides/imathbar) - Nouvelle instance du type [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public abstract IMathBar underbar()
```

Définit une barre en bas de cet élément

--------------------

> ```
> Exemple :
>  
>  IMathBar bar = new MathematicalText("x").underbar();
>  ```

**Retourne :**
[IMathBar](../../com.aspose.slides/imathbar) - Nouvelle instance du type [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public abstract IMathGroupingCharacter group()
```

Place cet élément dans un groupe en utilisant une accolade inférieure

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**Retourne :**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Nouvelle instance du type [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public abstract IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Places this element in a group using a grouping character such as bottom curly bracket or another

--------------------

> ```
> Exemple :
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| character | char | Caractère de groupement tel que ACCOLADE INFÉRIEURE (U+23DF) ou tout autre |
| position | int | Position du caractère de groupement |
| verticalJustification | int | Justification verticale du caractère de groupement. Spécifie l'alignement de l'objet par rapport à la ligne de base. Par exemple, lorsque le caractère de groupement est au-dessus de l'objet, la Justification verticale de Top indique que le haut de l'objet se trouve sur la ligne de base ; lorsque la Justification verticale est définie sur Bottom, le bas de l'objet est sur la ligne de base |

**Returns:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Nouvelle instance du type [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public abstract IMathBorderBox toBorderBox()
```
Place cet élément dans une boîte bordée

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  ```

**Returns:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Boîte bordée contenant cet élément placé à l’intérieur
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```
Place cet élément dans une boîte bordée

--------------------

> ```
> Exemple :
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hideTop | boolean | Masquer le bord supérieur |
| hideBottom | boolean | Masquer le bord inférieur |
| hideLeft | boolean | Masquer le bord gauche |
| hideRight | boolean | Masquer le bord droit |
| strikethroughHorizontal | boolean | Traversée horizontale de la boîte bordée |
| strikethroughVertical | boolean | Traversée verticale de la boîte bordée |
| strikethroughBottomLeftToTopRight | boolean | Traversée de la boîte bordée du coin inférieur gauche au coin supérieur droit |
| strikethroughTopLeftToBottomRight | boolean | Traversée de la boîte bordée du coin supérieur gauche au coin inférieur droit |

**Returns:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box with this element placed inside
### toBox() {#toBox--}
```
public abstract IMathBox toBox()


Place cet élément dans une boîte non visuelle (groupement logique) qui sert à regrouper les composants d’une équation ou d’une autre instance de texte mathématique. Un objet encadré peut (par exemple) servir d’émulateur d’opérateur avec ou sans point d’alignement, servir de point de rupture de ligne, ou être groupé de manière à ne pas autoriser les sauts de ligne à l’intérieur.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**Retourne :**
[IMathBox](../../com.aspose.slides/imathbox) - Boîte logique contenant cet élément placé à l’intérieur