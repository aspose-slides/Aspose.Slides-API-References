---
title: MathElementBase
second_title: Aspose.Slides for Android via Java API Reference
description: Base class for IMathElement with the implementation of some methods that are common to all inherited classes For internal use only.
type: docs
weight: 323
url: /androidjava/com.aspose.slides/mathelementbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

Base class for IMathElement with the implementation of some methods that are common to all inherited classes For internal use only. Inherited class must be IMathElement.
## Methods

| Method | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | Returns Parent\_Immediate object. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Joins a mathematical element and forms a mathematical block |
| [join(String mathText)](#join-java.lang.String-) | Joins a mathematical text and forms a mathematical block |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Creates a fraction with this numerator and specified denominator |
| [divide(String denominator)](#divide-java.lang.String-) | Creates a fraction with this numerator and specified denominator |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Creates a fraction of the specified type with this numerator and specified denominator |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Creates a fraction of the specified type with this numerator and specified denominator |
| [enclose()](#enclose--) | Encloses a math element in parenthesis |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Encloses a math element in specified characters such as parenthesis or another characters as framing |
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
| [getChildren()](#getChildren--) | Get children elements |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
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
public IMathBlock join(String mathText)
```


Joins a mathematical text and forms a mathematical block

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | Mathematical text to be joined |

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - A new IMathBlock containing this instance and specified argument
### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public final IMathFraction divide(IMathElement denominator)
```


Creates a fraction with this numerator and specified denominator

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
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominator |

**Returns:**
[IMathFraction](../../com.aspose.slides/imathfraction) - new fraction
### divide(String denominator) {#divide-java.lang.String-}
```
public final IMathFraction divide(String denominator)
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
public final IMathFraction divide(IMathElement denominator, int fractionType)
```


Creates a fraction of the specified type with this numerator and specified denominator

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominator |
| fractionType | int | Fraction type: Bar, NoBar, Skewed, Linear |

**Returns:**
[IMathFraction](../../com.aspose.slides/imathfraction) - new fraction
### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public final IMathFraction divide(String denominator, int fractionType)
```


Creates a fraction of the specified type with this numerator and specified denominator

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| denominator | java.lang.String | Denominator |
| fractionType | int | Fraction type: Bar, NoBar, Skewed, Linear |

**Returns:**
[IMathFraction](../../com.aspose.slides/imathfraction) - new fraction
### enclose() {#enclose--}
```
public final IMathDelimiter enclose()
```


Encloses a math element in parenthesis

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**Returns:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - The math element of type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) which includes the parenthesis
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```


Encloses a math element in specified characters such as parenthesis or another characters as framing

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char | Beginning character (usually left bracket) |
| endingCharacter | char | Ending character (usually right bracket) |

**Returns:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - The math element of type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) which includes specified characters as framing
### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```


Takes a function of an argument using this instance as the function name

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | An argument of the function |

**Returns:**
[IMathFunction](../../com.aspose.slides/imathfunction) - New math element of type [IMathFunction](../../com.aspose.slides/imathfunction)
### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```


Takes a function of an argument using this instance as the function name

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
| functionArgument | java.lang.String | An argument of the function |

**Returns:**
[IMathFunction](../../com.aspose.slides/imathfunction) - New math element of type [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```


Takes specified function using this instance as the argument

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | Function name |

**Returns:**
[IMathFunction](../../com.aspose.slides/imathfunction) - New math element of type [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(String functionName)
```


Takes specified function using this instance as the argument

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| functionName | java.lang.String | Function name |

**Returns:**
[IMathFunction](../../com.aspose.slides/imathfunction) - New math element of type [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public final IMathFunction asArgumentOfFunction(int functionType)
```


Takes specified function using this instance as the argument

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| functionType | int | One of the common function type of one argument |

**Returns:**
[IMathFunction](../../com.aspose.slides/imathfunction) - New math element of type [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```


Takes specified function using this instance as the argument and specified additional argument

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Returns the logarithm of 'x' to the base '5'
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
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```


Takes specified function using this instance as the argument and specified additional argument

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Returns the logarithm of 'x' to the base '5'
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
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```


Creates subscript

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subscript (lower index on the right) |

**Returns:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - New math element of type [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```


Creates subscript

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | Subscript (lower index on the right) |

**Returns:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - New math element of type [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```


Creates superscript

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Superscript (upper index on the right) |

**Returns:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - New math element of type [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```


Creates superscript

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| superscript | java.lang.String | Superscript (upper index on the right) |

**Returns:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - New math element of type [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```


Creates subscript and superscript on the right

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subscript (lower index on the right) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Superscript (upper index on the right) |

**Returns:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - New math element of type [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```


Creates subscript and superscript on the right

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | Subscript (lower index on the right) |
| superscript | java.lang.String | Superscript (upper index on the right) |

**Returns:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - New math element of type [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
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
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```


Creates subscript and superscript on the left

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | Subscript (lower index on the left) |
| superscript | java.lang.String | Superscript (upper index on the left) |

**Returns:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - New math element of type [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```


Specifies the mathematical root of the given degree from the specified argument.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Argument of Radical |

**Returns:**
[IMathRadical](../../com.aspose.slides/imathradical) - New instance of type [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```


Specifies the mathematical root of the given degree from the specified argument.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| degree | java.lang.String | Argument of Radical |

**Returns:**
[IMathRadical](../../com.aspose.slides/imathradical) - New instance of type [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```


Takes upper limit

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```


Takes upper limit

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```


Takes lower limit

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```


Takes lower limit

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```


Creates a N-ary operator

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | The N-ary operator type |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | The lower limit |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | The upper limit |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```


Creates a N-ary operator

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

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```


Puts in a vertical array

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Returns:**
[IMathArray](../../com.aspose.slides/imatharray) - New instance of type [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```


Takes the integral

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Integral type |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Lower limit of integral |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Upper limit of integral |
| limitLocations | int | location of limits |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```


Takes the integral

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Integral type |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Lower limit of integral |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Upper limit of integral |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```


Takes the integral without limits

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Integral type |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```


Takes the integral

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Integral type |
| lowerLimit | java.lang.String | Lower limit of integral |
| upperLimit | java.lang.String | Upper limit of integral |
| limitLocations | int | location of limits |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
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
public final IMathAccent accent(char accentCharacter)
```


Sets an accent mark (a character on the top of this element)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| accentCharacter | char | Accent character. The value should be within the range of (U+0300\\u2013U+036F) or (U+20D0\\u2013U+20EF) |

**Returns:**
[IMathAccent](../../com.aspose.slides/imathaccent) - New instance of type [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public final IMathBar overbar()
```


Sets a bar on the top of this element

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**Returns:**
[IMathBar](../../com.aspose.slides/imathbar) - New instance of type [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public final IMathBar underbar()
```


Sets a bar on the bottom of this element

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Returns:**
[IMathBar](../../com.aspose.slides/imathbar) - New instance of type [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public final IMathGroupingCharacter group()
```


Places this element in a group using a bottom curly bracket

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**Returns:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - New instance of type [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```


Places this element in a group using a grouping character such as bottom curly bracket or another

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| character | char | Grouping Character such as BOTTOM CURLY BRACKET (U+23DF) or any other |
| position | int | Position of grouping character |
| verticalJustification | int | Vertical justification of group character. Specifies the alignment of the object with respect to the baseline. For example, when the group character is above the object, VerticalJustification of Top signifies that the top of the object falls on the baseline; when VerticalJustification is set to Bottom, the bottom of the object is on the baseline |

**Returns:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - New instance of type [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```


Places this element in a border-box

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Returns:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box with this element placed inside
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Places this element in a border-box

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hideTop | boolean | Hide Top Edge |
| hideBottom | boolean | Hide Bottom Edge |
| hideLeft | boolean | Hide Left Edge |
| hideRight | boolean | Hide Right Edge |
| strikethroughHorizontal | boolean | Border Box Strikethrough Horizontal |
| strikethroughVertical | boolean | Border Box Strikethrough Vertical |
| strikethroughBottomLeftToTopRight | boolean | Border Box Strikethrough Bottom-Left to Top-Right |
| strikethroughTopLeftToBottomRight | boolean | Border Box Strikethrough Top-Left to Bottom-Right |

**Returns:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box with this element placed inside
### toBox() {#toBox--}
```
public final IMathBox toBox()
```


Places this element in a non-visual box (logical grouping) which is used to group components of an equation or other instance of mathematical text. A boxed object can (for example) serve as an operator emulator with or without an alignment point, serve as a line break point, or be grouped such as not to allow line breaks within.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**Returns:**
[IMathBox](../../com.aspose.slides/imathbox) - Logical box with this element placed inside
### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```


Get children elements

**Returns:**
com.aspose.slides.IMathElement[] - Array of [IMathElement](../../com.aspose.slides/imathelement)
