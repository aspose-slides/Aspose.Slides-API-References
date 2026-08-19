---
title: IMathElement
second_title: Aspose.Slides for Java API Reference
description: Basisinterface van elk wiskundig element: breuk, wiskundige tekst, functie, expressie met meerdere elementen enz.
type: docs
url: /nl/com.aspose.slides/imathelement/
---```
public interface IMathElement
```

Basisinterface van elk wiskundig element: breuk, wiskundige tekst, functie, expressie met meerdere elementen enz.

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
> ```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getChildren()](#getChildren--) | Haalt onderliggende elementen op |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Voegt een wiskundig element samen en vormt een wiskundig blok |
| [join(String mathText)](#join-java.lang.String-) | Voegt een wiskundige tekst samen en vormt een wiskundig blok |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Maakt een breuk met deze teller en de opgegeven noemer |
| [divide(String denominator)](#divide-java.lang.String-) | Maakt een breuk met deze teller en de opgegeven noemer |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Maakt een breuk van het opgegeven type met deze teller en de opgegeven noemer |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Maakt een breuk van het opgegeven type met deze teller en de opgegeven noemer |
| [enclose()](#enclose--) | Plaats een wiskundig element tussen haakjes |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Omringt dit element met opgegeven tekens, zoals haakjes of andere tekens als kader |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Neemt een functie van een argument met dit exemplaar als functienaam |
| [function(String functionArgument)](#function-java.lang.String-) | Neemt een functie van een argument met dit exemplaar als functienaam |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Neemt opgegeven functie met dit exemplaar als argument |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Neemt opgegeven functie met dit exemplaar als argument |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Neemt opgegeven functie met dit exemplaar als argument |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Neemt opgegeven functie met dit exemplaar als argument en opgegeven extra argument |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Neemt opgegeven functie met dit exemplaar als argument en opgegeven extra argument |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Maakt subscript |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Maakt subscript |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Maakt superscript |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Maakt superscript |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Maakt subscript en superscript rechts |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Maakt subscript en superscript rechts |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Maakt subscript en superscript links |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Maakt subscript en superscript links |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Specificeert de wiskundige wortel van de gegeven graad vanuit het opgegeven argument |
| [radical(String degree)](#radical-java.lang.String-) | Specificeert de wiskundige wortel van de gegeven graad vanuit het opgegeven argument |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Neemt bovengrens |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Neemt bovengrens |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Neemt ondergrens |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Neemt ondergrens |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Maakt een N-aire operator |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | Maakt een N-aire operator |
| [toMathArray()](#toMathArray--) | Plaatst in een verticale array |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Neemt de integraal |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Neemt de integraal |
| [integral(int integralType)](#integral-int-) | Neemt de integraal zonder grenzen |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | Neemt de integraal |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | Neemt de integraal |
| [accent(char accentCharacter)](#accent-char-) | Stelt een accentteken in (een teken boven dit element) |
| [overbar()](#overbar--) | Stelt een balk boven dit element in |
| [underbar()](#underbar--) | Stelt een balk onder dit element in |
| [group()](#group--) | Plaatst dit element in een groep met een onderste accolade |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Plaatst dit element in een groep met een groeppenthe zoals een onderste accolade of een andere |
| [toBorderBox()](#toBorderBox--) | Plaatst dit element in een randvak |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Plaatst dit element in een randvak |
| [toBox()](#toBox--) | Plaatst dit element in een niet-visueel vak (logische groepering) dat wordt gebruikt om componenten van een vergelijking of andere wiskundige tekst te groeperen |

### getChildren() {#getChildren--}
```
public abstract IMathElement[] getChildren()
```

Haalt onderliggende elementen op

**Retourneert:**
com.aspose.slides.IMathElement[]

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock join(IMathElement mathElement)
```

Voegt een wiskundig element samen en vormt een wiskundig blok

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Het element dat moet worden samengevoegd |

**Retourneert:**
[IMathBlock](../../com.aspose.slides/imathblock) - Een nieuw IMathBlock dat deze instantie en het opgegeven argument bevat

### join(String mathText) {#join-java.lang.String-}
```
public abstract IMathBlock join(String mathText)
```

Voegt een wiskundige tekst samen en vormt een wiskundig blok

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathText | java.lang.String | Wiskundige tekst die moet worden samengevoegd |

**Retourneert:**
[IMathBlock](../../com.aspose.slides/imathblock) - Een nieuw IMathBlock dat deze instantie en het opgegeven argument bevat

### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction divide(IMathElement denominator)
```

Maakt een breuk met deze teller en de opgegeven noemer

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Noemer |

**Retourneert:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nieuwe breuk

### divide(String denominator) {#divide-java.lang.String-}
```
public abstract IMathFraction divide(String denominator)
```

Maakt een breuk met deze teller en de opgegeven noemer

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| denominator | java.lang.String | Noemer |

**Retourneert:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nieuwe breuk

### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction divide(IMathElement denominator, int fractionType)
```

Maakt een breuk van het opgegeven type met deze teller en de opgegeven noemer

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Noemer |
| fractionType | int | Type breuk: Bar, NoBar, Skewed, Linear |

**Retourneert:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nieuwe breuk

### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public abstract IMathFraction divide(String denominator, int fractionType)
```

Maakt een breuk van het opgegeven type met deze teller en de opgegeven noemer

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| denominator | java.lang.String | Noemer |
| fractionType | int | Type breuk: Bar, NoBar, Skewed, Linear |

**Retourneert:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nieuwe breuk

### enclose() {#enclose--}
```
public abstract IMathDelimiter enclose()
```

Plaats een wiskundig element tussen haakjes

--------------------

> ```
> Voorbeeld:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```


**Retourneert:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Het wiskundige element van type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) dat de haakjes bevat

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Omringt dit element met opgegeven tekens, zoals haakjes of andere tekens als kader

--------------------

> ```
> Voorbeeld:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| beginningCharacter | char | Beginteken (meestal linker haak) |
| endingCharacter | char | Eindsymbool (meestal rechter haak) |

**Retourneert:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Het wiskundige element van type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) dat de opgegeven tekens als kader bevat

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction function(IMathElement functionArgument)
```

Neemt een functie van een argument met dit exemplaar als functienaam

--------------------

> ```
> Voorbeeld:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | Een argument van de functie |

**Retourneert:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nieuw wiskundig element van type [IMathFunction](../../com.aspose.slides/imathfunction)

### function(String functionArgument) {#function-java.lang.String-}
```
public abstract IMathFunction function(String functionArgument)
```

Neemt een functie van een argument met dit exemplaar als functienaam

--------------------

> ```
> Voorbeeld:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| functionArgument | java.lang.String | Een argument van de functie |

**Retourneert:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nieuw wiskundig element van type [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(IMathElement functionName)
```

Neemt opgegeven functie met dit exemplaar als argument

--------------------

> ```
> Voorbeeld:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | Functienaam |

**Retourneert:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nieuw wiskundig element van type [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(String functionName)
```

Neemt opgegeven functie met dit exemplaar als argument

--------------------

> ```
> Voorbeeld:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| functionName | java.lang.String | Functienaam |

**Retourneert:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nieuw wiskundig element van type [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType)
```

Neemt opgegeven functie met dit exemplaar als argument

--------------------

> ```
> Voorbeeld:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| functionType | int | Een van de gangbare functietypen met één argument |

**Retourneert:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nieuw wiskundig element van type [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

Neemt opgegeven functie met dit exemplaar als argument en opgegeven extra argument

--------------------

> ```
> Voorbeeld:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Retourneert de logaritme van 'x' met grondtal '5'
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| functionType | int | Een van de gangbare functietypen met twee argumenten: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Extra argument, afhankelijk van het type functie |

**Retourneert:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nieuw wiskundig element van type [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

Neemt opgegeven functie met dit exemplaar als argument en opgegeven extra argument

--------------------

> ```
> Voorbeeld:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Retourneert de logaritme van 'x' met grondtal '5'
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| functionType | int | Een van de gangbare functietypen met twee argumenten: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | Extra argument, afhankelijk van het type functie |

**Retourneert:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nieuw wiskundig element van type [IMathFunction](../../com.aspose.slides/imathfunction)

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSubscriptElement setSubscript(IMathElement subscript)
```

Maakt subscript

--------------------

> ```
> Voorbeeld:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subscript (onderindex rechts) |

**Retourneert:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Nieuw wiskundig element van type [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public abstract IMathSubscriptElement setSubscript(String subscript)
```

Maakt subscript

--------------------

> ```
> Voorbeeld:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| subscript | java.lang.String | Subscript (onderindex rechts) |

**Retourneert:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Nieuw wiskundig element van type [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

Maakt superscript

--------------------

> ```
> Voorbeeld:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Superscript (bovindex rechts) |

**Retourneert:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Nieuw wiskundig element van type [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public abstract IMathSuperscriptElement setSuperscript(String superscript)
```

Maakt superscript

--------------------

> ```
> Voorbeeld:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| superscript | java.lang.String | Superscript (bovindex rechts) |

**Retourneert:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Nieuw wiskundig element van type [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

Maakt subscript en superscript rechts

--------------------

> ```
> Voorbeeld:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subscript (onderindex rechts) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Superscript (bovindex rechts) |

**Retourneert:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Nieuw wiskundig element van type [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```
Creëert subscript en superscript aan de rechterkant
--------------------

> ```
> Voorbeeld:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| subscript | java.lang.String | Subscript (lagere index aan de rechterkant) |
| superscript | java.lang.String | Superscript (hogere index aan de rechterkant) |

**Retour:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Nieuw wiskundig element van het type [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Creëert subscript en superscript aan de linkerkant
--------------------

> ```
> Voorbeeld:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subscript (lagere index aan de linkerkant) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Superscript (hogere index aan de linkerkant) |

**Retour:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Nieuw wiskundig element van het type [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Creëert subscript en superscript aan de linkerkant
--------------------

> ```
> Voorbeeld:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| subscript | java.lang.String | Subscript (lagere index aan de linkerkant) |
| superscript | java.lang.String | Superscript (hogere index aan de linkerkant) |

**Retour:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Nieuw wiskundig element van het type [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public abstract IMathRadical radical(IMathElement degree)
```

Specificeert de wiskundige wortel van de gegeven graad uit het opgegeven argument.
--------------------

> ```
> Voorbeeld:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Argument van radical |

**Retour:**
[IMathRadical](../../com.aspose.slides/imathradical) - Nieuwe instantie van het type [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public abstract IMathRadical radical(String degree)
```

Specificeert de wiskundige wortel van de gegeven graad uit het opgegeven argument.
--------------------

> ```
> Voorbeeld:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| degree | java.lang.String | Argument van radical |

**Retour:**
[IMathRadical](../../com.aspose.slides/imathradical) - Nieuwe instantie van het type [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setUpperLimit(IMathElement limit)
```

Neemt de bovengrens
--------------------

> ```
> Voorbeeld:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | grens |

**Retour:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nieuwe instantie van het type [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public abstract IMathLimit setUpperLimit(String limit)
```

Neemt de bovengrens
--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| limit | java.lang.String | grens |

**Retour:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nieuwe instantie van het type [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setLowerLimit(IMathElement limit)
```

Neemt de ondergrens
--------------------

> ```
> Voorbeeld:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | grens |

**Retour:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nieuwe instantie van het type [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public abstract IMathLimit setLowerLimit(String limit)
```

Neemt de ondergrens
--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| limit | java.lang.String | grens |

**Retour:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nieuwe instantie van het type [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

Creëert een N-aire operator
--------------------

> ```
> Voorbeeld:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Het type N-aire operator |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | De ondergrens |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | De bovengrens |

**Retour:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nieuwe instantie van het type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

Creëert een N-aire operator
--------------------

> ```
> Voorbeeld:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Het type N-aire operator |
| lowerLimit | java.lang.String | De ondergrens |
| upperLimit | java.lang.String | De bovengrens |

**Retour:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nieuwe instantie van het type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public abstract IMathArray toMathArray()
```

Plaatst in een verticale array
--------------------

> ```
> Voorbeeld:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Retour:**
[IMathArray](../../com.aspose.slides/imatharray) - Nieuwe instantie van het type [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

Neemt de integraal
--------------------

> ```
> Voorbeeld:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| integralType | int | Type integraal |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Ondergrens van integraal |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Bovengrens van integraal |
| limitLocations | int | positie van de grenzen |

**Retour:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nieuwe instantie van het type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

Neemt de integraal
--------------------

> ```
> Voorbeeld:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| integralType | int | Type integraal |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Ondergrens van integraal |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Bovengrens van integraal |

**Retour:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nieuwe instantie van het type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public abstract IMathNaryOperator integral(int integralType)
```

Neemt de integraal zonder grenzen
--------------------

> ```
> Voorbeeld:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| integralType | int | Type integraal |

**Retour:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nieuwe instantie van het type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

Neemt de integraal
--------------------

> ```
> Voorbeeld:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| integralType | int | Type integraal |
| lowerLimit | java.lang.String | Ondergrens van integraal |
| upperLimit | java.lang.String | Bovengrens van integraal |
| limitLocations | int | positie van de grenzen |

**Retour:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nieuwe instantie van het type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

Neemt de integraal
--------------------

> ```
> Voorbeeld:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| integralType | int | Type integraal |
| lowerLimit | java.lang.String | Ondergrens van integraal |
| upperLimit | java.lang.String | Bovengrens van integraal |

**Retour:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nieuwe instantie van het type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public abstract IMathAccent accent(char accentCharacter)
```

Stelt een accentteken in (een teken bovenop dit element)
--------------------

> ```
> Voorbeeld:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| accentCharacter | char | Accentteken. De waarde moet vallen binnen het bereik (U+0300\\u2013U+036F) of (U+20D0\\u2013U+20EF) |

**Retour:**
[IMathAccent](../../com.aspose.slides/imathaccent) - Nieuwe instantie van het type [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public abstract IMathBar overbar()
```

Stelt een balk boven dit element in
--------------------

> ```
> Voorbeeld:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```


**Retour:**
[IMathBar](../../com.aspose.slides/imathbar) - Nieuwe instantie van het type [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public abstract IMathBar underbar()
```

Stelt een balk onder dit element in
--------------------

> ```
> Voorbeeld:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```


**Retour:**
[IMathBar](../../com.aspose.slides/imathbar) - Nieuwe instantie van het type [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public abstract IMathGroupingCharacter group()
```

Plaats dit element in een groep met een onderste accolade
--------------------

> ```
> Voorbeeld:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**Retour:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Nieuwe instantie van het type [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public abstract IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Plaats dit element in een groep met een groepeerkarakter zoals een onderste accolade of een ander
--------------------

> ```
> Voorbeeld:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| character | char | Groepeerkarakter zoals BOTTOM CURLY BRACKET (U+23DF) of een ander |
| position | int | Positie van het groepeerkarakter |
| verticalJustification | int | Verticale uitlijning van het groepeerkarakter. Bepaalt de uitlijning van het object ten opzichte van de basislijn. Bijvoorbeeld, wanneer het groepeerkarakter boven het object staat, betekent VerticalJustification Top dat de bovenkant van het object op de basislijn valt; wanneer VerticalJustification Bottom is, ligt de onderkant van het object op de basislijn |

**Retour:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Nieuwe instantie van het type [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public abstract IMathBorderBox toBorderBox()
```

Plaatst dit element in een border-box
--------------------

> ```
> Voorbeeld:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Retour:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box met dit element erin geplaatst
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Plaatst dit element in een border-box
--------------------

> ```
> Voorbeeld:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hideTop | boolean | Verberg bovenkant |
| hideBottom | boolean | Verberg onderkant |
| hideLeft | boolean | Verberg linkerkant |
| hideRight | boolean | Verberg rechterkant |
| strikethroughHorizontal | boolean | Border Box Doorhalen Horizontaal |
| strikethroughVertical | boolean | Border Box Doorhalen Verticaal |
| strikethroughBottomLeftToTopRight | boolean | Border Box Doorhalen van linksonder naar rechtsboven |
| strikethroughTopLeftToBottomRight | boolean | Border Box Doorhalen van linksboven naar rechtsonder |

**Retour:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box met dit element erin geplaatst
### toBox() {#toBox--}
```
public abstract IMathBox toBox()
```

Plaatst dit element in een niet-visuele box (logische groepering) die wordt gebruikt om componenten van een vergelijking of andere wiskundige tekst te groeperen. Een ingekiste object kan (bijvoorbeeld) dienen als operator-emulator met of zonder een uitlijningspunt, dienen als regel-breekpunt, of gegroepeerd worden zodat geen regelbreuken binnen toegestaan zijn.
--------------------

> ```
> Voorbeeld:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**Retour:**
[IMathBox](../../com.aspose.slides/imathbox) - Logische box met dit element erin geplaatst