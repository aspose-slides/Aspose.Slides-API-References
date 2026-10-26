---
title: MathElementBase
second_title: Aspose.Slides för Android via Java API-referens
description: Bas klass för IMathElement med implementationen av vissa metoder som är gemensamma för alla ärvda klasser. Endast för internt bruk.
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

Bas klass för IMathElement med implementationen av vissa metoder som är gemensamma för alla ärvda klasser. Endast för internt bruk. Ärvd klass måste vara IMathElement.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | Returnerar Parent_Immediate object. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Fogar samman ett matematiskt element och bildar ett matematiskt block |
| [join(String mathText)](#join-java.lang.String-) | Fogar samman en matematisk text och bildar ett matematiskt block |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Skapar ett bråk med detta täljare och angiven nämnare |
| [divide(String denominator)](#divide-java.lang.String-) | Skapar ett bråk med detta täljare och angiven nämnare |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Skapar ett bråk av den angivna typen med detta täljare och angiven nämnare |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Skapar ett bråk av den angivna typen med detta täljare och angiven nämnare |
| [enclose()](#enclose--) | Omringar ett matematiskt element i parentes |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Omringar ett matematiskt element med angivna tecken såsom parentes eller andra tecken som ram |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Tar en funktion av ett argument med detta objekt som funktionsnamn |
| [function(String functionArgument)](#function-java.lang.String-) | Tar en funktion av ett argument med detta objekt som funktionsnamn |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Tar angiven funktion med detta objekt som argument |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Tar angiven funktion med detta objekt som argument |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Tar angiven funktion med detta objekt som argument |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Tar angiven funktion med detta objekt som argument och angivet ytterligare argument |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Tar angiven funktion med detta objekt som argument och angivet ytterligare argument |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Skapar nedsänkt index |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Skapar nedsänkt index |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Skapar upphöjt index |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Skapar upphöjt index |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Skapar nedsänkt och upphöjt index på högra sidan |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Skapar nedsänkt och upphöjt index på högra sidan |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Skapar nedsänkt och upphöjt index på vänstra sidan |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Skapar nedsänkt och upphöjt index på vänstra sidan |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Anger den matematiska roten av given grad från det angivna argumentet. |
| [radical(String degree)](#radical-java.lang.String-) | Anger den matematiska roten av given grad från det angivna argumentet. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Tar övre gräns |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Tar övre gräns |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Tar nedre gräns |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Tar nedre gräns |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Skapar en N-ary-operator |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | Skapar en N-ary-operator |
| [toMathArray()](#toMathArray--) | Lägger in en vertikal array |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Tar integral |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tar integral |
| [integral(int integralType)](#integral-int-) | Tar integral utan gränser |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | Tar integral |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | Tar integral |
| [accent(char accentCharacter)](#accent-char-) | Ställer in ett accenttecken (ett tecken ovanpå detta element) |
| [overbar()](#overbar--) | Ställer in ett streck ovanpå detta element |
| [underbar()](#underbar--) | Ställer in ett streck under detta element |
| [group()](#group--) | Placera detta element i en grupp med en nedre klammerparentes |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Placera detta element i en grupp med ett grupperingstecken såsom nedre klammerparentes eller annat |
| [toBorderBox()](#toBorderBox--) | Placera detta element i en kantlåda |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Placera detta element i en kantlåda |
| [toBox()](#toBox--) | Placera detta element i en icke-visuell låda (logisk gruppering) som används för att gruppera komponenter i en ekvation eller annan instans av matematisk text. |
| [getChildren()](#getChildren--) | Hämta underordnade element |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate object. Skrivskyddad IDOMObject.

**Returnerar:**  
com.aspose.slides.IDOMObject
### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Fogar samman ett matematiskt element och bildar ett matematiskt block

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
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Elementet som ska fogas samman |

**Returnerar:**
[IMathBlock](../../com.aspose.slides/imathblock) - Ett nytt IMathBlock som innehåller detta objekt och angivet argument
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Fogar samman en matematisk text och bildar ett matematiskt block

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
| mathText | java.lang.String | Matematiskt text som ska fogas samman |

**Returnerar:**
[IMathBlock](../../com.aspose.slides/imathblock) - Ett nytt IMathBlock som innehåller detta objekt och angivet argument
### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public final IMathFraction divide(IMathElement denominator)
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
> Example:
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

Skapar ett bråk av den angivna typen med detta täljare och angiven nämnare

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
| fractionType | int | Bråktyp: Bar, NoBar, Skewed, Linear |

**Returnerar:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nytt bråk
### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public final IMathFraction divide(String denominator, int fractionType)
```

Skapar ett bråk av den angivna typen med detta täljare och angiven nämnare

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
| fractionType | int | Bråktyp: Bar, NoBar, Skewed, Linear |

**Returnerar:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nytt bråk
### enclose() {#enclose--}
```
public final IMathDelimiter enclose()
```

Omringar ett matematiskt element i parentes

--------------------

> ```
> Exempel:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```


**Returnerar:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Matematiskt element av typ [IMathDelimiter](../../com.aspose.slides/imathdelimiter) som inkluderar parentesen
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Omringar ett matematiskt element med angivna tecken såsom parentes eller andra tecken som ram

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| beginningCharacter | char | Inledande tecken (vanligtvis vänster klammer) |
| endingCharacter | char | Avslutande tecken (vanligtvis höger klammer) |

**Returnerar:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Matematiskt element av typ [IMathDelimiter](../../com.aspose.slides/imathdelimiter) som inkluderar de angivna tecknen som ram
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
| functionType | int | En av de vanliga funktionstyperna för ett argument |

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
| functionType | int | En av de vanliga funktionstyperna för två argument: Log, Lim, Min, Max |
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
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Returnerar logaritmen av 'x' till basen '5'
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functionType | int | En av de vanliga funktionstyperna för två argument: Log, Lim, Min, Max |
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
> Exempel:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Nedsänkt index (lägre index på högra sidan) |

**Returnerar:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Nytt matematiskt element av typ [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```

Skapar nedsänkt index

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| subscript | java.lang.String | Nedsänkt index (lägre index på högra sidan) |

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
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Upphöjt index (övre index på högra sidan) |

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
| superscript | java.lang.String | Upphöjt index (övre index på högra sidan) |

**Returnerar:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Nytt matematiskt element av typ [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

Skapar nedsänkt och upphöjt index på högra sidan

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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Nedsänkt index (lägre index på högra sidan) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Upphöjt index (övre index på högra sidan) |

**Returnerar:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Nytt matematiskt element av typ [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

Skapar nedsänkt och upphöjt index på högra sidan

--------------------

> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| subscript | java.lang.String | Nedsänkt index (lägre index på högra sidan) |
| superscript | java.lang.String | Upphöjt index (övre index på högra sidan) |

**Returnerar:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Nytt matematiskt element av typ [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Skapar nedsänkt och upphöjt index på vänstra sidan

--------------------

> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Nedsänkt index (lägre index på vänstra sidan) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Upphöjt index (övre index på vänstra sidan) |

**Returnerar:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Nytt matematiskt element av typ [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Skapar nedsänkt och upphöjt index på vänstra sidan

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| subscript | java.lang.String | Nedsänkt index (lägre index på vänstra sidan) |
| superscript | java.lang.String | Upphöjt index (övre index på vänstra sidan) |

**Returnerar:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Nytt matematiskt element av typ [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

Anger den matematiska roten av given grad från det angivna argumentet.

--------------------

> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Argument för rot |

**Returnerar:**
[IMathRadical](../../com.aspose.slides/imathradical) - Ny instans av typ [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```

Anger den matematiska roten av given grad från det angivna argumentet.

--------------------

> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| degree | java.lang.String | Argument för radikal |

**Returnerar:**
[IMathRadical](../../com.aspose.slides/imathradical) - Ny instans av typ [IMathRadical](../../com.aspose.slides/imathradical)
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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | gräns |

**Returnerar:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Ny instans av typ [IMathLimit](../../com.aspose.slides/imathlimit)
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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| limit | java.lang.String | gräns |

**Returnerar:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Ny instans av typ [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

Tar nedre gräns

--------------------

> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | gräns |

**Returnerar:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Ny instans av typ [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

Tar nedre gräns

--------------------

> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| limit | java.lang.String | gräns |

**Returnerar:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Ny instans av typ [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

Skapar en N-ary-operator

--------------------

> ```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | N-ary-operatorns typ |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Nedre gräns |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Övre gräns |

**Returnerar:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Ny instans av typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

Skapar en N-ary-operator

--------------------

> ```
> Exempel:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | N-ary-operatorns typ |
| lowerLimit | java.lang.String | Nedre gräns |
| upperLimit | java.lang.String | Övre gräns |

**Returnerar:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Ny instans av typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Lägger in en vertikal array

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Returnerar:**
[IMathArray](../../com.aspose.slides/imatharray) - Ny instans av typ [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```java
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

Tar integral

--------------------

> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| integralType | int | Integralt typ |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Nedre gräns för integral |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Övre gräns för integral |
| limitLocations | int | Placering av gränser |

**Returnerar:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Ny instans av typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

Tar integral

--------------------

> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| integralType | int | Integralt typ |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Nedre gräns för integral |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Övre gräns för integral |

**Returnerar:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Ny instans av typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

Tar integral utan gränser

--------------------

> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| integralType | int | Integralt typ |

**Returnerar:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Ny instans av typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

Tar integral

--------------------

> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| integralType | int | Integralt typ |
| lowerLimit | java.lang.String | Nedre gräns för integral |
| upperLimit | java.lang.String | Övre gräns för integral |
| limitLocations | int | Placering av gränser |

**Returnerar:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Ny instans av typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

Tar integral

--------------------

> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| integralType | int | Integralt typ |
| lowerLimit | java.lang.String | Nedre gräns för integral |
| upperLimit | java.lang.String | Övre gräns för integral |

**Returnerar:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Ny instans av typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

Ställer in ett accenttecken (ett tecken ovanpå detta element)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| accentCharacter | char | Accenttecken. Värdet bör ligga inom intervallet (U+0300-U+036F) eller (U+20D0-U+20EF) |

**Returnerar:**
[IMathAccent](../../com.aspose.slides/imathaccent) - Ny instans av typ [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public final IMathBar overbar()
```

Ställer in ett streck ovanpå detta element

--------------------

> ```
> Exempel:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**Returnerar:**
[IMathBar](../../com.aspose.slides/imathbar) - Ny instans av typ [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public final IMathBar underbar()
```

Ställer in ett streck under detta element

--------------------

> ```
> Exempel:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Returnerar:**
[IMathBar](../../com.aspose.slides/imathbar) - Ny instans av typ [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public final IMathGroupingCharacter group()
```

Placera detta element i en grupp med en nedre klammerparentes

--------------------

> ```
> Exempel:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**Returnerar:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Ny instans av typ [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Placera detta element i en grupp med ett grupperingstecken såsom nedre klammerparentes eller annat

--------------------

> ```
> Exempel:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| character | char | Grupperingstecken såsom BOTTOM CURLY BRACKET (U+23DF) eller annat |
| position | int | Position för grupperingstecken |
| verticalJustification | int | Vertikal justering av grupperingstecken. Anger objektets justering i förhållande till baslinjen. Till exempel, när tecknet är över objektet, betyder VerticalJustification Top att objektets topp ligger på baslinjen; när den är Bottom ligger botten på baslinjen. |

**Returnerar:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Ny instans av typ [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

Placera detta element i en kantlåda

--------------------

> ```
> Exempel:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Returnerar:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Kantlåda med detta element placerat inuti
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Placera detta element i en kantlåda

--------------------

> ```
> Exempel:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hideTop | boolean | Dölj överkant |
| hideBottom | boolean | Dölj underkant |
| hideLeft | boolean | Dölj vänsterkant |
| hideRight | boolean | Dölj högerkant |
| strikethroughHorizontal | boolean | Kantlåda genomstruken horisontellt |
| strikethroughVertical | boolean | Kantlåda genomstruken vertikalt |
| strikethroughBottomLeftToTopRight | boolean | Kantlåda genomstruken nedre-vänster till övre-höger |
| strikethroughTopLeftToBottomRight | boolean | Kantlåda genomstruken övre-vänster till nedre-höger |

**Returnerar:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Kantlåda med detta element placerat inuti
### toBox() {#toBox--}
```
public final IMathBox toBox()
```

Placera detta element i en icke-visuell låda (logisk gruppering) som används för att gruppera komponenter i en ekvation eller annan instans av matematisk text. En lådad objekt kan (till exempel) fungera som en operator-emulator med eller utan en justeringspunkt, fungera som en radbrytpunkt eller grupperas så att radbrytningar inte tillåts inom.

--------------------

> ```
> Exempel:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**Returnerar:**
[IMathBox](../../com.aspose.slides/imathbox) - Logisk låda med detta element placerat inuti
### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

Hämta underordnade element

**Returnerar:**
com.aspose.slides.IMathElement[] - Array av [IMathElement](../../com.aspose.slides/imathelement)