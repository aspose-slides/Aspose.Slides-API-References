---
title: MathElementBase
second_title: Aspose.Slides för Java API-referens
description: Bas-klass för IMathElement med implementationen av vissa metoder som är gemensamma för alla ärvda klasser. Endast för internt bruk.
type: docs
url: /sv/com.aspose.slides/mathelementbase/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

Basisklass för IMathElement med implementationen av vissa metoder som är gemensamma för alla ärvda klasser. Endast för internt bruk. Ärvd klass måste vara IMMathElement.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | Returnerar Parent_Immediate-objekt. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Kombinerar ett matematiskt element och bildar ett matematiskt block. |
| [join(String mathText)](#join-java.lang.String-) | Kombinerar en matematisk text och bildar ett matematiskt block. |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Skapar ett bråk med detta täljare och angiven nämnare. |
| [divide(String denominator)](#divide-java.lang.String-) | Skapar ett bråk med detta täljare och angiven nämnare. |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Skapar ett bråk av angiven typ med detta täljare och angiven nämnare. |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Skapar ett bråk av angiven typ med detta täljare och angiven nämnare. |
| [enclose()](#enclose--) | Omger ett matematiskt element med parenteser. |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Omger ett matematiskt element med angivna tecken, såsom parenteser eller andra tecken som ram. |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Tar en funktion av ett argument med detta objekt som funktionsnamn. |
| [function(String functionArgument)](#function-java.lang.String-) | Tar en funktion av ett argument med detta objekt som funktionsnamn. |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Tar angiven funktion med detta objekt som argument. |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Tar angiven funktion med detta objekt som argument. |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Tar angiven funktion med detta objekt som argument. |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Tar angiven funktion med detta objekt som argument och angivet ytterligare argument. |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Tar angiven funktion med detta objekt som argument och angivet ytterligare argument. |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Skapar nedsänkt index. |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Skapar nedsänkt index. |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Skapar upphöjt index. |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Skapar upphöjt index. |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Skapar nedsänkt och upphöjt index till höger. |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Skapar nedsänkt och upphöjt index till höger. |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Skapar nedsänkt och upphöjt index till vänster. |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Skapar nedsänkt och upphöjt index till vänster. |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Anger den matematiska roten av given grad från det angivna argumentet. |
| [radical(String degree)](#radical-java.lang.String-) | Anger den matematiska roten av given grad från det angivna argumentet. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Tar övre gräns. |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Tar övre gräns. |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Tar nedre gräns. |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Tar nedre gräns. |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Skapar en N-är operator. |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | Skapar en N-är operator. |
| [toMathArray()](#toMathArray--) | Sätter in en vertikal matris. |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Tar integralen. |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tar integralen. |
| [integral(int integralType)](#integral-int-) | Tar integralen utan gränser. |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | Tar integralen. |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | Tar integralen. |
| [accent(char accentCharacter)](#accent-char-) | Ställer in ett accenttecken (ett tecken ovanför detta element). |
| [overbar()](#overbar--) | Sätter ett streck ovanpå detta element. |
| [underbar()](#underbar--) | Sätter ett streck under detta element. |
| [group()](#group--) | Placera detta element i en grupp med en nedre klammerparentes. |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Placera detta element i en grupp med ett grupperande tecken, såsom en nedre klammerparentes eller annat. |
| [toBorderBox()](#toBorderBox--) | Placera detta element i en kantlåda. |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Placera detta element i en kantlåda. |
| [toBox()](#toBox--) | Placera detta element i en icke-visuell låda (logisk gruppering) som används för att gruppera komponenter i en ekvation eller annan matematisk text. |
| [getChildren()](#getChildren--) | Hämta underordnade element. |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objekt. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Kombinerar ett matematiskt element och bildar ett matematiskt block

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Elementet som ska slås ihop |

**Returnerar:**
[IMathBlock](../../com.aspose.slides/imathblock) - Ett nytt IMathBlock som innehåller detta objekt och angivet argument

### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Kombinerar en matematisk text och bildar ett matematiskt block

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathText | java.lang.String | Matematisk text som ska slås ihop |

**Returnerar:**
[IMathBlock](../../com.aspose.slides/imathblock) - Ett nytt IMathBlock som innehåller detta objekt och angivet argument

### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public final IMathFraction divide(IMathElement denominator)
```

Skapar ett bråk med detta täljare och angiven nämnare

--------------------

> ```
> Exempel:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Nämnare |

**Returnerar:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nytt bråk

### divide(String denominator) {#divide-java.lang.String-}
```
public final IMathFraction divide(String denominator)
```

Skapar ett bråk med detta täljare och angiven nämnare

--------------------

> ```
> Exempel:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| denominator | java.lang.String | Nämnare |

**Returnerar:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nytt bråk

### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction divide(IMathElement denominator, int fractionType)
```

Skapar ett bråk av angiven typ med detta täljare och angiven nämnare

--------------------

> ```
> Exempel:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Nämnare |
| fractionType | int | Fraktionstyp: Bar, NoBar, Skewed, Linear |

**Returnerar:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nytt bråk

### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public final IMathFraction divide(String denominator, int fractionType)
```

Skapar ett bråk av angiven typ med detta täljare och angiven nämnare

--------------------

> ```
> Exempel:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| denominator | java.lang.String | Nämnare |
| fractionType | int | Fraktionstyp: Bar, NoBar, Skewed, Linear |

**Returnerar:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nytt bråk

### enclose() {#enclose--}
```
public final IMathDelimiter enclose()
```

Omger ett matematiskt element med parenteser

--------------------

> ```
> Exempel:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```


**Returnerar:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Det matematiska elementet av typ [IMathDelimiter](../../com.aspose.slides/imathdelimiter) som inkluderar parentesen

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Omger ett matematiskt element med angivna tecken, såsom parenteser eller andra tecken som ram

--------------------

> ```
> Exempel:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| beginningCharacter | char | Starttecken (vanligtvis vänster parentes) |
| endingCharacter | char | Sluttecken (vanligtvis höger parentes) |

**Returnerar:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Det matematiska elementet av typ [IMathDelimiter](../../com.aspose.slides/imathdelimiter) som inkluderar angivna tecken som ram

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```

Tar en funktion av ett argument med detta objekt som funktionsnamn

--------------------

> ```
> Exempel:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | Ett argument till funktionen |

**Returnerar:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nytt matematiskt element av typ [IMathFunction](../../com.aspose.slides/imathfunction)

### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```

Tar en funktion av ett argument med detta objekt som funktionsnamn

--------------------

> ```
> Exempel:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functionArgument | java.lang.String | Ett argument till funktionen |

**Returnerar:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nytt matematiskt element av typ [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```

Tar angiven funktion med detta objekt som argument

--------------------

> ```
> Exempel:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | Funktionsnamn |

**Returnerar:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nytt matematiskt element av typ [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(String functionName)
```

Tar angiven funktion med detta objekt som argument

--------------------

> ```
> Exempel:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functionName | java.lang.String | Funktionsnamn |

**Returnerar:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nytt matematiskt element av typ [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public final IMathFunction asArgumentOfFunction(int functionType)
```

Tar angiven funktion med detta objekt som argument

--------------------

> ```
> Exempel:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functionType | int | En av de vanliga funktionstyperna med ett argument |

**Returnerar:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nytt matematiskt element av typ [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

Tar angiven funktion med detta objekt som argument och angivet ytterligare argument

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Returnerar logaritmen av 'x' till basen '5'
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functionType | int | En av de vanliga funktionstyperna med två argument: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Ytterligare argument beroende på funktionstypen |

**Returnerar:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nytt matematiskt element av typ [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

Tar angiven funktion med detta objekt som argument och angivet ytterligare argument

--------------------

> ```
> Exempel:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Returnerar logaritmen av 'x' till basen '5'
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functionType | int | En av de vanliga funktionstyperna med två argument: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | Ytterligare argument beroende på funktionstypen |

**Returnerar:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nytt matematiskt element av typ [IMathFunction](../../com.aspose.slides/imathfunction)

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```

Skapar nedsänkt index

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Nedsänkt index (lägre index till höger) |

**Returnerar:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Nytt matematiskt element av typ [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```

Skapar nedsänkt index

--------------------

> ```
> Exempel:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| subscript | java.lang.String | Nedsänkt index (lägre index till höger) |

**Returnerar:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Nytt matematiskt element av typ [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

Skapar upphöjt index

--------------------

> ```
> Exempel:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Upphöjt index (övre index till höger) |

**Returnerar:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Nytt matematiskt element av typ [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```

Skapar upphöjt index

--------------------

> ```
> Exempel:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| superscript | java.lang.String | Upphöjt index (övre index till höger) |

**Returnerar:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Nytt matematiskt element av typ [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

Skapar nedsänkt och upphöjt index till höger

--------------------

> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Nedsänkt index (lägre index till höger) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Upphöjt index (övre index till höger) |

**Returnerar:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Nytt matematiskt element av typ [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

Skapar nedsänkt och upphöjt index till höger
> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | Nedsänkt (lägre index till höger) |
| superscript | java.lang.String | Upphöjt (övre index till höger) |

**Returns:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Nytt matematiskt element av typen [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Skapar nedsänkt och upphöjt på vänster sida

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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Nedsänkt (lägre index till vänster) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Upphöjt (övre index till vänster) |

**Returns:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Nytt matematiskt element av typen [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Skapar nedsänkt och upphöjt på vänster sida

--------------------

> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | Nedsänkt (lägre index till vänster) |
| superscript | java.lang.String | Upphöjt (övre index till vänster) |

**Returns:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Nytt matematiskt element av typen [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

Specificerar den matematiska roten av den angivna graden från det specificerade argumentet.

--------------------

> ```
> Exempel:
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
[IMathRadical](../../com.aspose.slides/imathradical) - Ny instans av typen [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```

Specificerar den matematiska roten av den angivna graden från det specificerade argumentet.

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
[IMathRadical](../../com.aspose.slides/imathradical) - Ny instans av typen [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```

Tar övre gräns

--------------------

> ```
> Exempel:
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
[IMathLimit](../../com.aspose.slides/imathlimit) - Ny instans av typen [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```

Tar övre gräns

--------------------

> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Ny instans av typen [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
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
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Ny instans av typen [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
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
| limit | java.lang.String | limit |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Ny instans av typen [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
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
| type | int | N-är operatortyp |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Den undre gränsen |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Den övre gränsen |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Ny instans av typen [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
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
| type | int | N-är operatortyp |
| lowerLimit | java.lang.String | Den undre gränsen |
| upperLimit | java.lang.String | Den övre gränsen |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Ny instans av typen [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Sätter in en vertikal matris

--------------------

> ```
> Exempel:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Returns:**
[IMathArray](../../com.aspose.slides/imatharray) - Ny instans av typen [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
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
| integralType | int | Integratortyp |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Undre gräns för integralen |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Övre gräns för integralen |
| limitLocations | int | Placering av gränser |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Ny instans av typen [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
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
| integralType | int | Integratortyp |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Undre gräns för integralen |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Övre gräns för integralen |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Ny instans av typen [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

Tar integralen utan gränser

--------------------

> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Integratortyp |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Ny instans av typen [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

Tar integralen

--------------------

> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Integratortyp |
| lowerLimit | java.lang.String | Undre gräns för integralen |
| upperLimit | java.lang.String | Övre gräns för integralen |
| limitLocations | int | Placering av gränser |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Ny instans av typen [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
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
| integralType | int | Integratortyp |
| lowerLimit | java.lang.String | Undre gräns för integralen |
| upperLimit | java.lang.String | Övre gräns för integralen |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Ny instans av typen [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
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
[IMathAccent](../../com.aspose.slides/imathaccent) - Ny instans av typen [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public final IMathBar overbar()
```

Sätter en linje ovanpå detta element

--------------------

> ```
> Exempel:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```


**Returns:**
[IMathBar](../../com.aspose.slides/imathbar) - Ny instans av typen [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public final IMathBar underbar()
```

Sätter en linje under detta element

--------------------

> ```
> Exempel:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Returns:**
[IMathBar](../../com.aspose.slides/imathbar) - Ny instans av typen [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public final IMathGroupingCharacter group()
```

Placerar detta element i en grupp med en bottenklammer

--------------------

> ```
> Exempel:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**Returns:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Ny instans av typen [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Placerar detta element i en grupp med ett grupperingstecken såsom bottenklammer eller annat

--------------------

> ```
> Exempel:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| character | char | Grupperingstecken såsom BOTTOM CURLY BRACKET (U+23DF) eller annat |
| position | int | Position för grupperingstecken |
| verticalJustification | int | Vertikal justering av grupptecknet. Anger objektets placering i förhållande till baslinjen. Till exempel, när grupptecknet är ovanför objektet innebär VerticalJustification av Top att objektets topp ligger på baslinjen; när VerticalJustification är satt till Bottom ligger objektets botten på baslinjen |

**Returns:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Ny instans av typen [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

Placerar detta element i en kantlåda

--------------------

> ```
> Exempel:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Returns:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Kantlåda med detta element placerat inuti
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Placerar detta element i en kantlåda

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
| hideLeft | boolean | Dölj vänster kant |
| hideRight | boolean | Dölj höger kant |
| strikethroughHorizontal | boolean | Kantlåda genomstrykning horisontell |
| strikethroughVertical | boolean | Kantlåda genomstrykning vertikal |
| strikethroughBottomLeftToTopRight | boolean | Kantlåda genomstrykning nedre vänster till övre höger |
| strikethroughTopLeftToBottomRight | boolean | Kantlåda genomstrykning övre vänster till nedre höger |

**Returns:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Kantlåda med detta element placerat inuti
### toBox() {#toBox--}
```
public final IMathBox toBox()
```

Placerar detta element i en icke-visuell låda (logisk gruppering) som används för att gruppera komponenter i en ekvation eller annan matematisk text. Ett inneslutet objekt kan (till exempel) fungera som en operatoremulator med eller utan en justeringspunkt, fungera som en radbrytningspunkt, eller grupperas så att radbrytningar inte tillåts inom den.

--------------------

> ```
> Exempel:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**Returns:**
[IMathBox](../../com.aspose.slides/imathbox) - Logisk låda med detta element placerat inuti
### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

Hämta underordnade element

**Returns:**
com.aspose.slides.IMathElement[] - Array av [IMathElement](../../com.aspose.slides/imathelement)