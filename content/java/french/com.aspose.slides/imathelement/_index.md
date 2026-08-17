---
title: IMathElement
second_title: Référence API Aspose.Slides pour Java
description: Interface de base de tout élément mathématique : fraction, texte mathématique, fonction, expression avec plusieurs éléments, etc
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

## Méthodes

| Méthode | Description |
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

Obtenir les éléments enfants

**Renvoie :**
com.aspose.slides.IMathElement[]
### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock join(IMathElement mathElement)
```

Joint un élément mathématique et forme un bloc mathématique

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | L'élément à joindre |

**Renvoie :**
[IMathBlock](../../com.aspose.slides/imathblock) - Un nouveau IMathBlock contenant cette instance et l'argument spécifié
### join(String mathText) {#join-java.lang.String-}
```
public abstract IMathBlock join(String mathText)
```

Joint un texte mathématique et forme un bloc mathématique

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | Texte mathématique à joindre |

**Renvoie :**
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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Dénominateur |

**Renvoie :**
[IMathFraction](../../com.aspose.slides/imathfraction) - nouvelle fraction
### divide(String denominator) {#divide-java.lang.String-}
```
public abstract IMathFraction divide(String denominator)
```

Crée une fraction avec ce numérateur et le dénominateur spécifié

--------------------

> ```
> Exemple:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| denominator | java.lang.String | Dénominateur |

**Renvoie :**
[IMathFraction](../../com.aspose.slides/imathfraction) - nouvelle fraction
### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction divide(IMathElement denominator, int fractionType)
```

Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié

--------------------

> ```
> Exemple:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Dénominateur |
| fractionType | int | Type de fraction : Bar, NoBar, Skewed, Linear |

**Renvoie :**
[IMathFraction](../../com.aspose.slides/imathfraction) - nouvelle fraction
### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public abstract IMathFraction divide(String denominator, int fractionType)
```

Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié

--------------------

> ```
> Exemple:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| denominator | java.lang.String | Dénominateur |
| fractionType | int | Type de fraction : Bar, NoBar, Skewed, Linear |

**Renvoie :**
[IMathFraction](../../com.aspose.slides/imathfraction) - nouvelle fraction
### enclose() {#enclose--}
```
public abstract IMathDelimiter enclose()
```

Encadre un élément mathématique entre parenthèses

--------------------

> ```
> Exemple:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```


**Renvoie :**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - L'élément mathématique de type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) qui inclut les parenthèses
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Encadre cet élément avec les caractères spécifiés tels que parenthèses ou d'autres caractères de cadrage

--------------------

> ```
> Exemple:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| beginningCharacter | char | Caractère de début (généralement une accolade gauche) |
| endingCharacter | char | Caractère de fin (généralement une accolade droite) |

**Renvoie :**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - L'élément mathématique de type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) qui inclut les caractères spécifiés comme cadrage
### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction function(IMathElement functionArgument)
```

Prend une fonction d'un argument en utilisant cette instance comme nom de fonction

--------------------

> ```
> Exemple:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argument de la fonction |

**Renvoie :**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nouveau élément mathématique de type [IMathFunction](../../com.aspose.slides/imathfunction)
### function(String functionArgument) {#function-java.lang.String-}
```
public abstract IMathFunction function(String functionArgument)
```

Prend une fonction d'un argument en utilisant cette instance comme nom de fonction

--------------------

> ```
> Exemple:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| functionArgument | java.lang.String | Argument de la fonction |

**Renvoie :**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nouveau élément mathématique de type [IMathFunction](../../com.aspose.slides/imathfunction)
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

**Renvoie :**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nouveau élément mathématique de type [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(String functionName)
```

Prend la fonction spécifiée en utilisant cette instance comme argument

--------------------

> ```
> Exemple:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| functionName | java.lang.String | Nom de la fonction |

**Renvoie :**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nouveau élément mathématique de type [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType)
```

Prend la fonction spécifiée en utilisant cette instance comme argument

--------------------

> ```
> Exemple:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| functionType | int | Un des types de fonction courants à un argument |

**Renvoie :**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nouveau élément mathématique de type [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

Prend la fonction spécifiée en utilisant cette instance comme argument et l'argument additionnel spécifié

--------------------

> ```
> Exemple:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Renvoie le logarithme de 'x' à la base '5'
```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| functionType | int | Un des types de fonction courants à deux arguments : Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argument additionnel dépendant du type de fonction |

**Renvoie :**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nouveau élément mathématique de type [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

Prend la fonction spécifiée en utilisant cette instance comme argument et l'argument additionnel spécifié

--------------------

> ```
> Exemple:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Renvoie le logarithme de 'x' à la base '5'
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| functionType | int | Un des types de fonction courants à deux arguments : Log, Lim, Min, Max |
| additionalArgument | java.lang.String | Argument additionnel dépendant du type de fonction |

**Renvoie :**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nouveau élément mathématique de type [IMathFunction](../../com.aspose.slides/imathfunction)
### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSubscriptElement setSubscript(IMathElement subscript)
```

Crée un indice (subscript)

--------------------

> ```
> Exemple:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Indice (indice inférieur à droite) |

**Renvoie :**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Nouveau élément mathématique de type [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public abstract IMathSubscriptElement setSubscript(String subscript)
```

Crée un indice (subscript)

--------------------

> ```
> Exemple:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | Indice (indice inférieur à droite) |

**Renvoie :**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Nouveau élément mathématique de type [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

Crée un exposant (superscript)

--------------------

> ```
> Exemple:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Exposant (indice supérieur à droite) |

**Renvoie :**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Nouveau élément mathématique de type [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public abstract IMathSuperscriptElement setSuperscript(String superscript)
```

Crée un exposant (superscript)

--------------------

> ```
> Exemple:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| superscript | java.lang.String | Exposant (indice supérieur à droite) |

**Renvoie :**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Nouveau élément mathématique de type [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

Crée un indice et un exposant à droite

--------------------

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Indice (indice inférieur à droite) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Exposant (indice supérieur à droite) |

**Renvoie :**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Nouveau élément mathématique de type [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```
Crée un indice et un exposant à droite

--------------------

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```


**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | Indice (indice inférieur à droite) |
| superscript | java.lang.String | Exposant (indice supérieur à droite) |

**Renvoie:**  
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Nouvel élément mathématique de type [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Crée un indice et un exposant à gauche

--------------------

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Indice (indice inférieur à gauche) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Exposant (indice supérieur à gauche) |

**Renvoie:**  
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Nouvel élément mathématique de type [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Crée un indice et un exposant à gauche

--------------------

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```


**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | Indice (indice inférieur à gauche) |
| superscript | java.lang.String | Exposant (indice supérieur à gauche) |

**Renvoie:**  
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Nouvel élément mathématique de type [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public abstract IMathRadical radical(IMathElement degree)
```

Spécifie la racine mathématique du degré donné à partir de l’argument spécifié.

--------------------

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Argument du radical |

**Renvoie:**  
[IMathRadical](../../com.aspose.slides/imathradical) - Nouvelle instance du type [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public abstract IMathRadical radical(String degree)
```

Spécifie la racine mathématique du degré donné à partir de l’argument spécifié.

--------------------

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| degree | java.lang.String | Argument du radical |

**Renvoie:**  
[IMathRadical](../../com.aspose.slides/imathradical) - Nouvelle instance du type [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setUpperLimit(IMathElement limit)
```

Prend la limite supérieure

--------------------

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limite |

**Renvoie:**  
[IMathLimit](../../com.aspose.slides/imathlimit) - Nouvelle instance du type [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public abstract IMathLimit setUpperLimit(String limit)
```

Prend la limite supérieure

--------------------

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```


**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| limit | java.lang.String | limite |

**Renvoie:**  
[IMathLimit](../../com.aspose.slides/imathlimit) - Nouvelle instance du type [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setLowerLimit(IMathElement limit)
```

Prend la limite inférieure

--------------------

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```


**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limite |

**Renvoie:**  
[IMathLimit](../../com.aspose.slides/imathlimit) - Nouvelle instance du type [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public abstract IMathLimit setLowerLimit(String limit)
```

Prend la limite inférieure

--------------------

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| limit | java.lang.String | limite |

**Renvoie:**  
[IMathLimit](../../com.aspose.slides/imathlimit) - Nouvelle instance du type [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

Crée un opérateur N-aire

--------------------

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```


**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Le type d’opérateur N-aire |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | La limite inférieure |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | La limite supérieure |

**Renvoie:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nouvelle instance du type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

Crée un opérateur N-aire

--------------------

> ```
> Exemple:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```


**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Le type d’opérateur N-aire |
| lowerLimit | java.lang.String | La limite inférieure |
| upperLimit | java.lang.String | La limite supérieure |

**Renvoie:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nouvelle instance du type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public abstract IMathArray toMathArray()
```

Place dans un tableau vertical

--------------------

> ```
> Exemple:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Renvoie:**  
[IMathArray](../../com.aspose.slides/imatharray) - Nouvelle instance du type [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

Prend l’intégrale

--------------------

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| integralType | int | Type d’intégrale |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite inférieure de l’intégrale |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite supérieure de l’intégrale |
| limitLocations | int | position des limites |

**Renvoie:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nouvelle instance du type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

Prend l’intégrale

--------------------

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| integralType | int | Type d’intégrale |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite inférieure de l’intégrale |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite supérieure de l’intégrale |

**Renvoie:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nouvelle instance du type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public abstract IMathNaryOperator integral(int integralType)
```

Prend l’intégrale sans limites

--------------------

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```


**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| integralType | int | Type d’intégrale |

**Renvoie:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nouvelle instance du type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

Prend l’intégrale

--------------------

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```


**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| integralType | int | Type d’intégrale |
| lowerLimit | java.lang.String | Limite inférieure de l’intégrale |
| upperLimit | java.lang.String | Limite supérieure de l’intégrale |
| limitLocations | int | position des limites |

**Renvoie:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nouvelle instance du type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

Prend l’intégrale

--------------------

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```


**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| integralType | int | Type d’intégrale |
| lowerLimit | java.lang.String | Limite inférieure de l’intégrale |
| upperLimit | java.lang.String | Limite supérieure de l’intégrale |

**Renvoie:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nouvelle instance du type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public abstract IMathAccent accent(char accentCharacter)
```

Définit un accent (un caractère au dessus de cet élément)

--------------------

> ```
> Exemple:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| accentCharacter | char | Caractère d’accent. La valeur doit être comprise dans l’intervalle (U+0300\\u2013U+036F) ou (U+20D0\\u2013U+20EF) |

**Renvoie:**  
[IMathAccent](../../com.aspose.slides/imathaccent) - Nouvelle instance du type [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public abstract IMathBar overbar()
```

Définit une barre au dessus de cet élément

--------------------

> ```
public abstract IMathBar overbar()
```

**Renvoie:**  
[IMathBar](../../com.aspose.slides/imathbar) - Nouvelle instance du type [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public abstract IMathBar underbar()
```

Définit une barre au bas de cet élément

--------------------

> ```
public abstract IMathBar underbar()
```

**Renvoie:**  
[IMathBar](../../com.aspose.slides/imathbar) - Nouvelle instance du type [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public abstract IMathGroupingCharacter group()
```

Place cet élément dans un groupe en utilisant une accolade inférieure

--------------------

> ```
> Exemple:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**Renvoie:**  
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Nouvelle instance du type [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public abstract IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Place cet élément dans un groupe en utilisant un caractère de groupement tel qu’une accolade inférieure ou autre

--------------------

> ```
> Exemple:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| character | char | Caractère de groupement tel que ACCOLADE INFÉRIEURE (U+23DF) ou tout autre |
| position | int | Position du caractère de groupement |
| verticalJustification | int | Justification verticale du caractère de groupe. Spécifie l’alignement de l’objet par rapport à la ligne de base. Par exemple, lorsque le caractère de groupe est au-dessus de l’objet, VerticalJustification = Top indique que le haut de l’objet repose sur la ligne de base ; lorsqu’il est à Bottom, le bas de l’objet repose sur la ligne de base |

**Renvoie:**  
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Nouvelle instance du type [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public abstract IMathBorderBox toBorderBox()
```

Place cet élément dans une boîte à bordure

--------------------

> ```
> Exemple:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Renvoie:**  
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Boîte à bordure contenant cet élément
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Place cet élément dans une boîte à bordure

--------------------

> ```
> Exemple:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| hideTop | boolean | Masquer le bord supérieur |
| hideBottom | boolean | Masquer le bord inférieur |
| hideLeft | boolean | Masquer le bord gauche |
| hideRight | boolean | Masquer le bord droit |
| strikethroughHorizontal | boolean | Barré horizontal de la boîte à bordure |
| strikethroughVertical | boolean | Barré vertical de la boîte à bordure |
| strikethroughBottomLeftToTopRight | boolean | Barré de la boîte à bordure de bas-gauche à haut-droite |
| strikethroughTopLeftToBottomRight | boolean | Barré de la boîte à bordure de haut-gauche à bas-droite |

**Renvoie:**  
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Boîte à bordure contenant cet élément
### toBox() {#toBox--}
```
public abstract IMathBox toBox()
```

Place cet élément dans une boîte non visuelle (groupement logique) utilisée pour regrouper les composants d’une équation ou d’un autre texte mathématique. Un objet encadré peut (par exemple) servir d’émulateur d’opérateur avec ou sans point d’alignement, servir de point de rupture de ligne, ou être groupé de façon à empêcher les ruptures de ligne à l’intérieur.

--------------------

> ```
> Exemple:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**Renvoie:**  
[IMathBox](../../com.aspose.slides/imathbox) - Boîte logique contenant cet élément