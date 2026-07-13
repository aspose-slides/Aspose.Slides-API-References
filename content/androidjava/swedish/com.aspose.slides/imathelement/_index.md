---
title: IMathElement
second_title: Aspose.Slides for Android via Java API Reference
description: Basgränssnitt för alla matematiska element: bråk, matematisk text, funktion, uttryck med flera element osv
type: docs
url: /sv/com.aspose.slides/imathelement/
---```
public interface IMathElement
```

Basgränssnitt för alla matematiska element: bråk, matematisk text, funktion, uttryck med flera element osv

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
> ```
## Metoder

| Method | Description |
| --- | --- |
| [getChildren()](#getChildren--) | Hämta underordnade element |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Sammanfogar ett matematiskt element och skapar ett matematiskt block |
| [join(String mathText)](#join-java.lang.String-) | Sammanfogar en matematisk text och skapar ett matematiskt block |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Skapar ett bråk med detta täljare och angiven nämnare |
| [divide(String denominator)](#divide-java.lang.String-) | Skapar ett bråk med detta täljare och angiven nämnare |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Skapar ett bråk av angiven typ med detta täljare och angiven nämnare |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Skapar ett bråk av angiven typ med detta täljare och angiven nämnare |
| [enclose()](#enclose--) | Innesluter ett matematiskt element i parentes |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Innesluter detta element i specificerade tecken såsom parentes eller andra tecken som ram |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Tar en funktion med ett argument med detta objekt som funktionsnamn |
| [function(String functionArgument)](#function-java.lang.String-) | Tar en funktion med ett argument med detta objekt som funktionsnamn |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Tar specificerad funktion med detta objekt som argument |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Tar specificerad funktion med detta objekt som argument |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Tar specificerad funktion med detta objekt som argument |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Tar specificerad funktion med detta objekt som argument och specificerat ytterligare argument |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Tar specificerad funktion med detta objekt som argument och specificerat ytterligare argument |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Skapar nedsänkt index |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Skapar nedsänkt index |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Skapar upphöjt index |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Skapar upphöjt index |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Skapar nedsänkt och upphöjt index åt höger |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Skapar nedsänkt och upphöjt index åt höger |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Skapar nedsänkt och upphöjt index åt vänster |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Skapar nedsänkt och upphöjt index åt vänster |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Anger den matematiska roten av given grad från det specificerade argumentet. |
| [radical(String degree)](#radical-java.lang.String-) | Anger den matematiska roten av given grad från det specificerade argumentet. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Tar övre gräns |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Tar övre gräns |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Tar undre gräns |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Tar undre gräns |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Skapar en N-är operator |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | Skapar en N-är operator |
| [toMathArray()](#toMathArray--) | Sätter in en vertikal matris |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Tar integralen |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tar integralen |
| [integral(int integralType)](#integral-int-) | Tar integralen utan gränser |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | Tar integralen |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | Tar integralen |
| [accent(char accentCharacter)](#accent-char-) | Sätter ett accenttecken (ett tecken ovanpå detta element) |
| [overbar()](#overbar--) | Sätter ett streck ovanpå detta element |
| [underbar()](#underbar--) | Sätter ett streck under detta element |
| [group()](#group--) | Placera detta element i en grupp med en klammerparentes nere |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Placera detta element i en grupp med ett grupperings-tecken såsom klammerparentes eller annat |
| [toBorderBox()](#toBorderBox--) | Placera detta element i en kantruta |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Placera detta element i en kantruta |
| [toBox()](#toBox--) | Placera detta element i en icke-visuell ruta (logisk gruppering) som används för att gruppera komponenter i en ekvation eller annan matematisk text. |
### getChildren() {#getChildren--}
```
public abstract IMathElement[] getChildren()
```

Hämta underordnade element

**Returns:**
com.aspose.slides.IMathElement[]
### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock join(IMathElement mathElement)
```

Sammanfogar ett matematiskt element och skapar ett matematiskt block

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
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Elementet som ska sammanfogas |

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - Ett nytt IMathBlock som innehåller detta objekt och specificerat argument
### join(String mathText) {#join-java.lang.String-}
```
public abstract IMathBlock join(String mathText)
```

Sammanfogar en matematisk text och skapar ett matematiskt block

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
| mathText | java.lang.String | Matematisk text som ska sammanfogas |

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - Ett nytt IMathBlock som innehåller detta objekt och specificerat argument
### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction divide(IMathElement denominator)
```

Skapar ett bråk med detta täljare och angiven nämnare

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
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Nämnare |

**Returns:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nytt bråk
### divide(String denominator) {#divide-java.lang.String-}
```
public abstract IMathFraction divide(String denominator)
```

Skapar ett bråk med detta täljare och angiven nämnare

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
| denominator | java.lang.String | Nämnare |

**Returns:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nytt bråk
### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction divide(IMathElement denominator, int fractionType)
```

Skapar ett bråk av angiven typ med detta täljare och angiven nämnare

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
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Nämnare |
| fractionType | int | Bråktyp: Bar, NoBar, Skewed, Linear |

**Returns:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nytt bråk
### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public abstract IMathFraction divide(String denominator, int fractionType)
```

Skapar ett bråk av angiven typ med detta täljare och angiven nämnare

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
| denominator | java.lang.String | Nämnare |
| fractionType | int | Bråktyp: Bar, NoBar, Skewed, Linear |

**Returns:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nytt bråk
### enclose() {#enclose--}
```
public abstract IMathDelimiter enclose()
```

Innesluter ett matematiskt element i parentes

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**Returns:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Math-elementet av typ [IMathDelimiter](../../com.aspose.slides/imathdelimiter) som innehåller parentesen
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Innesluter detta element i specificerade tecken såsom parentes eller andra tecken som ram

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
| beginningCharacter | char | Starttecken (vanligtvis vänster parentes) |
| endingCharacter | char | Sluttecken (vanligtvis höger parentes) |

**Returns:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Math-elementet av typ [IMathDelimiter](../../com.aspose.slides/imathdelimiter) som innehåller specificerade tecken som ram
### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction function(IMathElement functionArgument)
```

Tar en funktion med ett argument med detta objekt som funktionsnamn

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
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | Ett argument till funktionen |

**Returns:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nytt math-element av typ [IMathFunction](../../com.aspose.slides/imathfunction)
### function(String functionArgument) {#function-java.lang.String-}
```
public abstract IMathFunction function(String functionArgument)
```

Tar en funktion med ett argument med detta objekt som funktionsnamn

--------------------

> ```
> Exempel:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| functionArgument | java.lang.String | Ett argument till funktionen |

**Returns:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nytt math-element av typ [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(IMathElement functionName)
```

Tar specificerad funktion med detta objekt som argument

--------------------

> ```
> Exempel:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | Funktionsnamn |

**Returns:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nytt math-element av typ [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(String functionName)
```

Tar specificerad funktion med detta objekt som argument

--------------------

> ```
> Exempel:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| functionName | java.lang.String | Funktionsnamn |

**Returns:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nytt math-element av typ [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType)
```

Tar specificerad funktion med detta objekt som argument

--------------------

> ```
> Exempel:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| functionType | int | En av de vanliga funktionstyperna med ett argument |

**Returns:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nytt math-element av typ [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

Tar specificerad funktion med detta objekt som argument och specificerat ytterligare argument

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Returnerar logaritmen av 'x' till basen '5'
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| functionType | int | En av de vanliga funktionstyperna med två argument: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Ytterligare argument beroende på funktionstyp |

**Returns:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nytt math-element av typ [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

Tar specificerad funktion med detta objekt som argument och specificerat ytterligare argument

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Returnerar logaritmen av 'x' till basen '5'
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| functionType | int | En av de vanliga funktionstyperna med två argument: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | Ytterligare argument beroende på funktionstyp |

**Returns:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nytt math-element av typ [IMathFunction](../../com.aspose.slides/imathfunction)
### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSubscriptElement setSubscript(IMathElement subscript)
```

Skapar nedsänkt index

--------------------

> ```
> Exempel:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Nedsänkt index (lägre index till höger) |

**Returns:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Nytt math-element av typ [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public abstract IMathSubscriptElement setSubscript(String subscript)
```

Skapar nedsänkt index

--------------------

> ```
> Exempel:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | Nedsänkt index (lägre index till höger) |

**Returns:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Nytt math-element av typ [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

Skapar upphöjt index

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
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Upphöjt index (övre index till höger) |

**Returns:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Nytt math-element av typ [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public abstract IMathSuperscriptElement setSuperscript(String superscript)
```

Skapar upphöjt index

--------------------

> ```
> Exempel:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| superscript | java.lang.String | Upphöjt index (övre index till höger) |

**Returns:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Nytt math-element av typ [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

Skapar nedsänkt och upphöjt index åt höger

--------------------

> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Nedsänkt index (lägre index till höger) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Upphöjt index (övre index till höger) |

**Returns:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Nytt math-element av typ [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

Skapar nedsänkt och upphöjt index åt höger

--------------------

> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | Nedsänkt index (lägre index till höger) |
| superscript | java.lang.String | Upphöjt index (övre index till höger) |

**Returns:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Nytt math-element av typ [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Skapar nedsänkt och upphöjt index åt vänster

--------------------

> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Nedsänkt index (lägre index till vänster) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Upphöjt index (övre index till vänster) |

**Returns:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Nytt math-element av typ [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Skapar nedsänkt och upphöjt index åt vänster

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
| subscript | java.lang.String | Nedsänkt index (lägre index till vänster) |
| superscript | java.lang.String | Upphöjt index (övre index till vänster) |

**Returns:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Nytt math-element av typ [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public abstract IMathRadical radical(IMathElement degree)
```

Anger den matematiska roten av given grad från det specificerade argumentet.

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
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Argument för roten |

**Returns:**
[IMathRadical](../../com.aspose.slides/imathradical) - Ny instans av typ [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public abstract IMathRadical radical(String degree)
```

Anger den matematiska roten av given grad från det specificerade argumentet.

--------------------

> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| degree | java.lang.String | Argument för roten |

**Returns:**
[IMathRadical](../../com.aspose.slides/imathradical) - Ny instans av typ [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setUpperLimit(IMathElement limit)
```

Tar övre gräns

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
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Gräns |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Ny instans av typ [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public abstract IMathLimit setUpperLimit(String limit)
```

Tar övre gräns

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
| limit | java.lang.String | Gräns |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Ny instans av typ [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setLowerLimit(IMathElement limit)
```

Tar undre gräns

--------------------

> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Gräns |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Ny instans av typ [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public abstract IMathLimit setLowerLimit(String limit)
```

Tar undre gräns

--------------------

> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | java.lang.String | Gräns |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Ny instans av typ [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

Skapar en N-är operator

--------------------

> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Den N-ära operatorns typ |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Undre gräns |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Övre gräns |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Ny instans av typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

Skapar en N-är operator

--------------------

> ```
> Exempel:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Den N-ära operatorns typ |
| lowerLimit | java.lang.String | Undre gräns |
| upperLimit | java.lang.String | Övre gräns |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Ny instans av typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public abstract IMathArray toMathArray()
```

Sätter in en vertikal matris

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Returns:**
[IMathArray](../../com.aspose.slides/imatharray) - Ny instans av typ [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

Tar integralen

--------------------

> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Integraltyp |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Undre gräns för integralen |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Övre gräns för integralen |
| limitLocations | int | Plats för gränser |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Ny instans av typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

Tar integralen

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
| integralType | int | Integraltyp |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Undre gräns för integralen |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Övre gräns för integralen |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Ny instans av typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public abstract IMathNaryOperator integral(int integralType)
```

Tar integralen utan gränser

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
| integralType | int | Integraltyp |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Ny instans av typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

Tar integralen

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
| integralType | int | Integraltyp |
| lowerLimit | java.lang.String | Undre gräns för integralen |
| upperLimit | java.lang.String | Övre gräns för integralen |
| limitLocations | int | Plats för gränser |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Ny instans av typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

Tar integralen

--------------------

> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Integraltyp |
| lowerLimit | java.lang.String | Undre gräns för integralen |
| upperLimit | java.lang.String | Övre gräns för integralen |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Ny instans av typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public abstract IMathAccent accent(char accentCharacter)
```

Sätter ett accenttecken (ett tecken ovanpå detta element)

--------------------

> ```
> Exempel:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| accentCharacter | char | Accenttecken. Värdet bör ligga inom intervallet (U+0300\\u2013U+036F) eller (U+20D0\\u2013U+20EF) |

**Returns:**
[IMathAccent](../../com.aspose.slides/imathaccent) - Ny instans av typ [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public abstract IMathBar overbar()
```

Sätter ett streck ovanpå detta element

--------------------

> ```
> Exempel:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```


**Returns:**
[IMathBar](../../com.aspose.slides/imathbar) - Ny instans av typ [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public abstract IMathBar underbar()
```

Sätter ett streck under detta element

--------------------

> ```
> Exempel:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Returns:**
[IMathBar](../../com.aspose.slides/imathbar) - Ny instans av typ [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public abstract IMathGroupingCharacter group()
```

Placera detta element i en grupp med en klammerparentes nere

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**Returns:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Ny instans av typ [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public abstract IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Placera detta element i en grupp med ett grupperings-tecken såsom klammerparentes eller annat

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| character | char | Grupperande tecken såsom BOTTOM CURLY BRACKET (U+23DF) eller annat |
| position | int | Position för grupperande tecken |
| verticalJustification | int | Vertikal justering av grupptecken. Anger hur objektet ska justeras i förhållande till baslinjen. Till exempel, när grupptecknet är över objektet, betyder VerticalJustification Top att objektets topp ligger på baslinjen; när VerticalJustification är Bottom ligger objektets botten på baslinjen. |

**Returns:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Ny instans av typ [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public abstract IMathBorderBox toBorderBox()
```

Placera detta element i en kantruta

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```


**Returns:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Kantruta med detta element placerat inuti
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Placera detta element i en kantruta

--------------------

> ```
> Exempel:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hideTop | boolean | Dölj övre kant |
| hideBottom | boolean | Dölj nedre kant |
| hideLeft | boolean | Dölj vänsterkant |
| hideRight | boolean | Dölj högerkant |
| strikethroughHorizontal | boolean | Kantlåda genomstruken horisontellt |
| strikethroughVertical | boolean | Kantlåda genomstruken vertikalt |
| strikethroughBottomLeftToTopRight | boolean | Kantlåda genomstruken från nedre vänster till övre höger |
| strikethroughTopLeftToBottomRight | boolean | Kantlåda genomstruken från övre vänster till nedre höger |

**Returns:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Kantlåda med detta element placerat inuti
### toBox() {#toBox--}
```
public abstract IMathBox toBox()
```

Placera detta element i en icke-visuell ruta (logisk gruppering) som används för att gruppera komponenter i en ekvation eller annan matematisk text. En lådad objekt kan (till exempel) fungera som en operator-emulator med eller utan en justeringspunkt, fungera som ett radbrytningstecken, eller grupperas så att radbrytningar inte tillåts inom.

--------------------

> ```
> Exempel:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**Returns:**
[IMathBox](../../com.aspose.slides/imathbox) - Logisk ruta med detta element placerat inuti