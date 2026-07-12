---
title: IMathElement
second_title: Aspose.Slides for Android via Java API Reference
description: Base interface of any mathematical element  fraction mathmatical text function expression with multiple elements etc
type: docs
url: /hu/com.aspose.slides/imathelement/
---```
public interface IMathElement
```

Bármely matematikai elem, például tört, matematikai szöveg, függvény vagy több elemből álló kifejezés alap interfésze

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
> ```
## Módszerek

| Módszer | Leírás |
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


Gyermek elemek lekérése

**Visszatérési érték:**
com.aspose.slides.IMathElement[]
### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock join(IMathElement mathElement)
```


Összekapcsol egy matematikai elemet és egy matematikai blokkot hoz létre

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | A összekapcsolandó elem |

**Visszatérési érték:**
[IMathBlock](../../com.aspose.slides/imathblock) - A new IMathBlock containing this instance and specified argument
### join(String mathText) {#join-java.lang.String-}
```
public abstract IMathBlock join(String mathText)
```


Összekapcsol egy matematikai szöveget és egy matematikai blokkot hoz létre

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathText | java.lang.String | A összekapcsolandó matematikai szöveg |

**Visszatérési érték:**
[IMathBlock](../../com.aspose.slides/imathblock) - A new IMathBlock containing this instance and specified argument
### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction divide(IMathElement denominator)
```


Létrehoz egy törtet a számlálóval és a megadott nevezővel

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Nevező |

**Visszatérési érték:**
[IMathFraction](../../com.aspose.slides/imathfraction) - new fraction
### divide(String denominator) {#divide-java.lang.String-}
```
public abstract IMathFraction divide(String denominator)
```


Létrehoz egy törtet a számlálóval és a megadott nevezővel

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| denominator | java.lang.String | Nevező |

**Visszatérési érték:**
[IMathFraction](../../com.aspose.slides/imathfraction) - new fraction
### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction divide(IMathElement denominator, int fractionType)
```


A megadott típusú törtet hoz létre a számlálóval és a megadott nevezővel

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Nevező |
| fractionType | int | Fraction type: Bar, NoBar, Skewed, Linear |

**Visszatérési érték:**
[IMathFraction](../../com.aspose.slides/imathfraction) - new fraction
### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public abstract IMathFraction divide(String denominator, int fractionType)
```


A megadott típusú törtet hoz létre a számlálóval és a megadott nevezővel

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| denominator | java.lang.String | Nevező |
| fractionType | int | Fraction type: Bar, NoBar, Skewed, Linear |

**Visszatérési érték:**
[IMathFraction](../../com.aspose.slides/imathfraction) - new fraction
### enclose() {#enclose--}
```
public abstract IMathDelimiter enclose()
```


A matematikai elemet zárójelbe helyezi

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**Visszatérési érték:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - The math element of type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) which includes the parenthesis
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```


A megadott karakterekkel (például zárójelek) keretezi az elemet

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| beginningCharacter | char | Kezdő karakter (általában bal zárójel) |
| endingCharacter | char | Záró karakter (általában jobb zárójel) |

**Visszatérési érték:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - The math element of type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) which includes specified characters as framing
### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction function(IMathElement functionArgument)
```


Egy argumentummal rendelkező függvényt hoz létre, a példányt függvény nevének tekintve

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | A függvény argumentuma |

**Visszatérési érték:**
[IMathFunction](../../com.aspose.slides/imathfunction) - New math element of type [IMathFunction](../../com.aspose.slides/imathfunction)
### function(String functionArgument) {#function-java.lang.String-}
```
public abstract IMathFunction function(String functionArgument)
```


Egy argumentummal rendelkező függvényt hoz létre, a példányt függvény nevének tekintve

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionArgument | java.lang.String | A függvény argumentuma |

**Visszatérési érték:**
[IMathFunction](../../com.aspose.slides/imathfunction) - New math element of type [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(IMathElement functionName)
```


Meghatározott függvényt használ az elem argumentumaként

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | Függvény neve |

**Visszatérési érték:**
[IMathFunction](../../com.aspose.slides/imathfunction) - New math element of type [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(String functionName)
```


Meghatározott függvényt használ az elem argumentumaként

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionName | java.lang.String | Függvény neve |

**Visszatérési érték:**
[IMathFunction](../../com.aspose.slides/imathfunction) - New math element of type [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType)
```


Meghatározott függvényt használ az elem argumentumaként

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionType | int | One of the common function type of one argument |

**Visszatérési érték:**
[IMathFunction](../../com.aspose.slides/imathfunction) - New math element of type [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```


Megadott függvényt használ, a példányt argumentumként, valamint egy további megadott argumentumot

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Visszaadja az 'x' logaritmusát az '5' alapra
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionType | int | One of the common function type of two arguments: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Additional argument depending on the type of function |

**Visszatérési érték:**
[IMathFunction](../../com.aspose.slides/imathfunction) - New math element of type [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```


Megadott függvényt használ, a példányt argumentumként, valamint egy további megadott argumentumot

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Visszaadja az 'x' logaritmusát az '5' alapra
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionType | int | One of the common function type of two arguments: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | Additional argument depending on the type of function |

**Visszatérési érték:**
[IMathFunction](../../com.aspose.slides/imathfunction) - New math element of type [IMathFunction](../../com.aspose.slides/imathfunction)
### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSubscriptElement setSubscript(IMathElement subscript)
```


Létrehoz egy alsó indexet

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subscript (lower index on the right) |

**Visszatérési érték:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - New math element of type [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public abstract IMathSubscriptElement setSubscript(String subscript)
```


Létrehoz egy alsó indexet

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subscript | java.lang.String | Subscript (lower index on the right) |

**Visszatérési érték:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - New math element of type [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSuperscriptElement setSuperscript(IMathElement superscript)
```


Létrehoz egy felső indexet

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Superscript (upper index on the right) |

**Visszatérési érték:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - New math element of type [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public abstract IMathSuperscriptElement setSuperscript(String superscript)
```


Létrehoz egy felső indexet

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| superscript | java.lang.String | Superscript (upper index on the right) |

**Visszatérési érték:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - New math element of type [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```


Létrehoz jobb oldali alsó és felső indexet

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subscript (lower index on the right) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Superscript (upper index on the right) |

**Visszatérési érték:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - New math element of type [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```


Létrehoz jobb oldali alsó és felső indexet

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subscript | java.lang.String | Subscript (lower index on the right) |
| superscript | java.lang.String | Superscript (upper index on the right) |

**Visszatérési érték:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - New math element of type [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```


Létrehoz bal oldali alsó és felső indexet

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subscript (lower index on the left) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Superscript (upper index on the left) |

**Visszatérési érték:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - New math element of type [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```


Létrehoz bal oldali alsó és felső indexet

--------------------

> ```
> Példa:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subscript | java.lang.String | Subscript (lower index on the left) |
| superscript | java.lang.String | Superscript (upper index on the left) |

**Visszatérési érték:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - New math element of type [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public abstract IMathRadical radical(IMathElement degree)
```


Megadja a megadott kitevőjű matematikai gyököt a megadott argumentumból

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Argument of Radical |

**Visszatérési érték:**
[IMathRadical](../../com.aspose.slides/imathradical) - New instance of type [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public abstract IMathRadical radical(String degree)
```


Megadja a megadott kitevőjű matematikai gyököt a megadott argumentumból

--------------------

> ```
> Példa:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| degree | java.lang.String | Argument of Radical |

**Visszatérési érték:**
[IMathRadical](../../com.aspose.slides/imathradical) - New instance of type [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setUpperLimit(IMathElement limit)
```


Felül határértéket állít be

--------------------

> ```
> Példa:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Visszatérési érték:**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public abstract IMathLimit setUpperLimit(String limit)
```


Felül határértéket állít be

--------------------

> ```
> Példa:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Visszatérési érték:**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setLowerLimit(IMathElement limit)
```


Alsó határértéket állít be

--------------------

> ```
> Példa:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Visszatérési érték:**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public abstract IMathLimit setLowerLimit(String limit)
```


Alsó határértéket állít be

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Visszatérési érték:**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```


N-értelmű operátort hoz létre

--------------------

> ```
> Példa:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | The N-ary operator type |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | The lower limit |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | The upper limit |

**Visszatérési érték:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```


N-értelmű operátort hoz létre

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | The N-ary operator type |
| lowerLimit | java.lang.String | The lower limit |
| upperLimit | java.lang.String | The upper limit |

**Visszatérési érték:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public abstract IMathArray toMathArray()
```


Függőleges tömböt hoz létre

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Visszatérési érték:**
[IMathArray](../../com.aspose.slides/imatharray) - New instance of type [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```


Integrált számít

--------------------

> ```
> Példa:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| integralType | int | Integral type |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Lower limit of integral |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Upper limit of integral |
| limitLocations | int | location of limits |

**Visszatérési érték:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```


Integrált számít

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| integralType | int | Integral type |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Lower limit of integral |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Upper limit of integral |

**Visszatérési érték:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public abstract IMathNaryOperator integral(int integralType)
```


Integrálást végez korlátok nélkül

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| integralType | int | Integral type |

**Visszatérési érték:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```


Integrált számít

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| integralType | int | Integral type |
| lowerLimit | java.lang.String | Lower limit of integral |
| upperLimit | java.lang.String | Upper limit of integral |
| limitLocations | int | location of limits |

**Visszatérési érték:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```


Integrált számít

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| integralType | int | Integral type |
| lowerLimit | java.lang.String | Lower limit of integral |
| upperLimit | java.lang.String | Upper limit of integral |

**Visszatérési érték:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public abstract IMathAccent accent(char accentCharacter)
```


Akcentus jelet állít be (karakter az elem tetején)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| accentCharacter | char | Accent character. The value should be within the range of (U+0300\\u2013U+036F) or (U+20D0\\u2013U+20EF) |

**Visszatérési érték:**
[IMathAccent](../../com.aspose.slides/imathaccent) - New instance of type [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public abstract IMathBar overbar()
```


Felső vonalat helyez az elemre

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**Visszatérési érték:**
[IMathBar](../../com.aspose.slides/imathbar) - New instance of type [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public abstract IMathBar underbar()
```


Alsó vonalat helyez az elemre

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Visszatérési érték:**
[IMathBar](../../com.aspose.slides/imathbar) - New instance of type [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public abstract IMathGroupingCharacter group()
```


Az elemet alsó kapcsos zárójel segítségével csoportba helyezi

--------------------

> ```
public abstract IMathGroupingCharacter group()
```

**Visszatérési érték:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - New instance of type [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public abstract IMathGroupingCharacter group(char character, int position, int verticalJustification)
```


Az elemet egy csoportba helyezi egy csoportosító karakter segítségével, például alsó kapcsos zárójel vagy más

--------------------

> ```
> Példa:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| character | char | Grouping Character such as BOTTOM CURLY BRACKET (U+23DF) or any other |
| position | int | Position of grouping character |
| verticalJustification | int | Vertical justification of group character. Specifies the alignment of the object with respect to the baseline. For example, when the group character is above the object, VerticalJustification of Top signifies that the top of the object falls on the baseline; when VerticalJustification is set to Bottom, the bottom of the object is on the baseline |

**Visszatérési érték:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - New instance of type [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public abstract IMathBorderBox toBorderBox()
```


Az elemet keretdobozba helyezi

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Visszatérési érték:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box with this element placed inside
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Az elemet keretdobozba helyezi

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hideTop | boolean | Hide Top Edge |
| hideBottom | boolean | Hide Bottom Edge |
| hideLeft | boolean | Hide Left Edge |
| hideRight | boolean | Hide Right Edge |
| strikethroughHorizontal | boolean | Border Box Strikethrough Horizontal |
| strikethroughVertical | boolean | Border Box Strikethrough Vertical |
| strikethroughBottomLeftToTopRight | boolean | Border Box Strikethrough Bottom-Left to Top-Right |
| strikethroughTopLeftToBottomRight | boolean | Border Box Strikethrough Top-Left to Bottom-Right |

**Visszatérési érték:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box with this element placed inside
### toBox() {#toBox--}
```
public abstract IMathBox toBox()
```


Az elemet nem látható dobozba (logikai csoportosítás) helyezi, amelyet egyenlet vagy más matematikai szöveg komponenseinek csoportosítására használnak. A doboz például operátor emulátorként, vonaltörés pontként vagy úgy is használható, hogy megakadályozza a sortöréseket az adott részen.

--------------------

> ```
public abstract IMathBox toBox()
```

**Visszatérési érték:**
[IMathBox](../../com.aspose.slides/imathbox) - Logical box with this element placed inside