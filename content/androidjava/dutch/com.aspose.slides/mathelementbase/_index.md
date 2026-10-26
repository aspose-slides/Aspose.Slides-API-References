---
title: MathElementBase
second_title: Aspose.Slides voor Android via Java API-referentie
description: Basisklasse voor IMathElement met de implementatie van enkele methoden die gemeenschappelijk zijn voor alle afgeleide klassen. Alleen voor intern gebruik.
type: docs
url: /nl/com.aspose.slides/mathelementbase/
---
**Erft van:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

Basis klasse voor IMathElement met de implementatie van enkele methoden die gemeenschappelijk zijn voor alle afgeleide klassen. Alleen voor intern gebruik. Afgeleide klasse moet IMathElement zijn.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | Retourneert Parent_Immediate object. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Voegt een wiskundig element toe en vormt een wiskundig blok |
| [join(String mathText)](#join-java.lang.String-) | Voegt een wiskundige tekst toe en vormt een wiskundig blok |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Creëert een breuk met deze teller en gespecificeerde noemer |
| [divide(String denominator)](#divide-java.lang.String-) | Creëert een breuk met deze teller en gespecificeerde noemer |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Creëert een breuk van het opgegeven type met deze teller en gespecificeerde noemer |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Creëert een breuk van het opgegeven type met deze teller en gespecificeerde noemer |
| [enclose()](#enclose--) | Plaatst een wiskundig element tussen haakjes |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Plaatst een wiskundig element tussen opgegeven tekens, zoals haakjes of andere tekens |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [function(String functionArgument)](#function-java.lang.String-) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Neemt een opgegeven functie waarbij deze instantie als argument en een extra argument wordt gebruikt |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Neemt een opgegeven functie waarbij deze instantie als argument en een extra argument wordt gebruikt |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Creëert subscript |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Creëert subscript |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Creëert superscript |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Creëert superscript |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creëert subscript en superscript aan de rechterkant |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Creëert subscript en superscript aan de rechterkant |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creëert subscript en superscript aan de linkerkant |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Creëert subscript en superscript aan de linkerkant |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Specificeert de wiskundige wortel van de opgegeven graad uit het opgegeven argument. |
| [radical(String degree)](#radical-java.lang.String-) | Specificeert de wiskundige wortel van de opgegeven graad uit het opgegeven argument. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Neemt bovengrens |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Neemt bovengrens |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Neemt ondergrens |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Neemt ondergrens |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creëert een N-ary-operator |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | Creëert een N-ary-operator |
| [toMathArray()](#toMathArray--) | Plaatst in een verticale matrix |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Neemt de integraal |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Neemt de integraal |
| [integral(int integralType)](#integral-int-) | Neemt de integraal zonder grenzen |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | Neemt de integraal |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | Neemt de integraal |
| [accent(char accentCharacter)](#accent-char-) | Zet een accentteken (een teken boven dit element) |
| [overbar()](#overbar--) | Zet een balk boven dit element |
| [underbar()](#underbar--) | Zet een balk onder dit element |
| [group()](#group--) | Plaatst dit element in een groep met een onderste accolades |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Plaatst dit element in een groep met een groeperingsteken, zoals een onderste accolades of een ander teken |
| [toBorderBox()](#toBorderBox--) | Plaatst dit element in een border-box |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Plaatst dit element in een border-box |
| [toBox()](#toBox--) | Plaatst dit element in een niet-visuele box (logische groepering) die wordt gebruikt om componenten van een vergelijking of andere wiskundige tekst te groeperen. |
| [getChildren()](#getChildren--) | Haalt kindelementen op |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Retourneert Parent_Immediate object. Alleen-lezen IDOMObject.

**Retour:**
com.aspose.slides.IDOMObject

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Voegt een wiskundig element toe en vormt een wiskundig blok

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

**Retour:**
[IMathBlock](../../com.aspose.slides/imathblock) - Een nieuw IMathBlock dat deze instantie en het opgegeven argument bevat

### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Voegt een wiskundige tekst toe en vormt een wiskundig blok

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

**Retour:**
[IMathBlock](../../com.aspose.slides/imathblock) - Een nieuw IMathBlock dat deze instantie en het opgegeven argument bevat

### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public final IMathFraction divide(IMathElement denominator)
```

Creëert een breuk met deze teller en gespecificeerde noemer

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

**Retour:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nieuwe breuk

### divide(String denominator) {#divide-java.lang.String-}
```
public final IMathFraction divide(String denominator)
```

Creëert een breuk met deze teller en gespecificeerde noemer

> ```
> Voorbeeld:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| denominator | java.lang.String | Noemer |

**Retour:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nieuwe breuk

### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction divide(IMathElement denominator, int fractionType)
```

Creëert een breuk van het opgegeven type met deze teller en gespecificeerde noemer

> ```
> Voorbeeld:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Noemer |
| fractionType | int | Breuktype: Bar, NoBar, Skewed, Linear |

**Retour:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nieuwe breuk

### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public final IMathFraction divide(String denominator, int fractionType)
```

Creëert een breuk van het opgegeven type met deze teller en gespecificeerde noemer

> ```
> Voorbeeld:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| denominator | java.lang.String | Noemer |
| fractionType | int | Breuktype: Bar, NoBar, Skewed, Linear |

**Retour:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nieuwe breuk

### enclose() {#enclose--}
```
public final IMathDelimiter enclose()
```

Plaatst een wiskundig element tussen haakjes

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**Retour:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Het wiskundige element van type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) dat haakjes bevat

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Plaatst een wiskundig element tussen opgegeven tekens, zoals haakjes of andere tekens

> ```
> Voorbeeld:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| beginningCharacter | char | Beginkarakter (meestal linker haak) |
| endingCharacter | char | Eindkarakter (meestal rechter haak) |

**Retour:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Het wiskundige element van type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) dat de opgegeven tekens als kader bevat

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```

Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | Een argument van de functie |

**Retour:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nieuw wiskundig element van type [IMathFunction](../../com.aspose.slides/imathfunction)

### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```

Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt

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

**Retour:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nieuw wiskundig element van type [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```

Neemt opgegeven functie waarbij deze instantie als argument wordt gebruikt

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

**Retour:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nieuw wiskundig element van type [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(String functionName)
```

Neemt opgegeven functie waarbij deze instantie als argument wordt gebruikt

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

**Retour:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nieuw wiskundig element van type [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public final IMathFunction asArgumentOfFunction(int functionType)
```

Neemt opgegeven functie waarbij deze instantie als argument wordt gebruikt

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| functionType | int | Een van de veelvoorkomende functietypen met één argument |

**Retour:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nieuw wiskundig element van type [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

Neemt opgegeven functie waarbij deze instantie als argument en een extra argument wordt gebruikt

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Retourneert de logaritme van 'x' met basis '5'
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| functionType | int | Een van de veelvoorkomende functietypen met twee argumenten: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Extra argument, afhankelijk van het type functie |

**Retour:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nieuw wiskundig element van type [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

Neemt opgegeven functie waarbij deze instantie als argument en een extra argument wordt gebruikt

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Retourneert de logaritme van 'x' met basis '5'
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| functionType | int | Een van de veelvoorkomende functietypen met twee argumenten: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | Extra argument, afhankelijk van het type functie |

**Retour:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nieuw wiskundig element van type [IMathFunction](../../com.aspose.slides/imathfunction)

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```

Creëert subscript

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subscript (onderindex aan de rechterkant) |

**Retour:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Nieuw wiskundig element van type [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```

Creëert subscript

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| subscript | java.lang.String | Subscript (onderindex aan de rechterkant) |

**Retour:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Nieuw wiskundig element van type [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

Creëert superscript

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
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Superscript (bovindex aan de rechterkant) |

**Retour:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Nieuw wiskundig element van type [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```

Creëert superscript

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| superscript | java.lang.String | Superscript (bovindex aan de rechterkant) |

**Retour:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Nieuw wiskundig element van type [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

Creëert subscript en superscript aan de rechterkant

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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subscript (onderindex aan de rechterkant) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Superscript (bovindex aan de rechterkant) |

**Retour:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Nieuw wiskundig element van type [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

Creëert subscript en superscript aan de rechterkant

> ```
> Voorbeeld:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| subscript | java.lang.String | Subscript (onderindex aan de rechterkant) |
| superscript | java.lang.String | Superscript (bovindex aan de rechterkant) |

**Retour:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Nieuw wiskundig element van type [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Creëert subscript en superscript aan de linkerkant

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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subscript (onderindex aan de linkerkant) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Superscript (bovindex aan de linkerkant) |

**Retour:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Nieuw wiskundig element van type [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)

### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Creëert subscript en superscript aan de linkerkant

> ```
> Voorbeeld:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| subscript | java.lang.String | Subscript (onderindex aan de linkerkant) |
| superscript | java.lang.String | Superscript (bovindex aan de linkerkant) |

**Retour:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Nieuw wiskundig element van type [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)

### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

Specificeert de wiskundige wortel van de opgegeven graad uit het opgegeven argument.

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
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Argument van de wortel |

**Retour:**
[IMathRadical](../../com.aspose.slides/imathradical) - Nieuwe instantie van type [IMathRadical](../../com.aspose.slides/imathradical)

### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```

Specificeert de wiskundige wortel van de opgegeven graad uit het opgegeven argument.

> ```
> Voorbeeld:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| degree | java.lang.String | Argument van de wortel |

**Retour:**
[IMathRadical](../../com.aspose.slides/imathradical) - Nieuwe instantie van type [IMathRadical](../../com.aspose.slides/imathradical)

### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```

Neemt bovengrens

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | bovengrens |

**Retour:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nieuwe instantie van type [IMathLimit](../../com.aspose.slides/imathlimit)

### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```

Neemt bovengrens

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| limit | java.lang.String | bovengrens |

**Retour:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nieuwe instantie van type [IMathLimit](../../com.aspose.slides/imathlimit)

### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

Neemt ondergrens

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
| limit | [IMathElement](../../com.aspose.slides/imathelement) | ondergrens |

**Retour:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nieuwe instantie van type [IMathLimit](../../com.aspose.slides/imathlimit)

### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

Neemt ondergrens

> ```
> Voorbeeld:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| limit | java.lang.String | ondergrens |

**Retour:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nieuwe instantie van type [IMathLimit](../../com.aspose.slides/imathlimit)

### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

Creëert een N-ary-operator

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Het type N-ary-operator |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | De ondergrens |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | De bovengrens |

**Retour:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nieuwe instantie van type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

Creëert een N-ary-operator

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Het type N-ary-operator |
| lowerLimit | java.lang.String | De ondergrens |
| upperLimit | java.lang.String | De bovengrens |

**Retour:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nieuwe instantie van type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Plaatst in een verticale matrix

> ```
> Voorbeeld:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
```

**Retour:**
[IMathArray](../../com.aspose.slides/imatharray) - Nieuwe instantie van type [IMathArray](../../com.aspose.slides/imatharray)

### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

Neemt de integraal

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
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Ondergrens van de integraal |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Bovengrens van de integraal |
| limitLocations | int | Locatie van de grenzen |

**Retour:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nieuwe instantie van type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

Neemt de integraal

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
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Ondergrens van de integraal |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Bovengrens van de integraal |

**Retour:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nieuwe instantie van type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

Neemt de integraal zonder grenzen

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
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nieuwe instantie van type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

Neemt de integraal

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| integralType | int | Type integraal |
| lowerLimit | java.lang.String | Ondergrens van de integraal |
| upperLimit | java.lang.String | Bovengrens van de integraal |
| limitLocations | int | Locatie van de grenzen |

**Retour:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nieuwe instantie van type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

Neemt de integraal

> ```
> Voorbeeld:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| integralType | int | Type integraal |
| lowerLimit | java.lang.String | Ondergrens van de integraal |
| upperLimit | java.lang.String | Bovengrens van de integraal |

**Retour:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nieuwe instantie van type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

Zet een accentteken (een teken boven dit element)

> ```
> Voorbeeld:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| accentCharacter | char | Accentteken. De waarde moet binnen het bereik (U+0300-U+036F) of (U+20D0-U+20EF) liggen |

**Retour:**
[IMathAccent](../../com.aspose.slides/imathaccent) - Nieuwe instantie van type [IMathAccent](../../com.aspose.slides/imathaccent)

### overbar() {#overbar--}
```
public final IMathBar overbar()
```

Zet een balk boven dit element

> ```
> Voorbeeld:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**Retour:**
[IMathBar](../../com.aspose.slides/imathbar) - Nieuwe instantie van type [IMathBar](../../com.aspose.slides/imathbar)

### underbar() {#underbar--}
```
public final IMathBar underbar()
```

Zet een balk onder dit element

> ```
> Voorbeeld:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Retour:**
[IMathBar](../../com.aspose.slides/imathbar) - Nieuwe instantie van type [IMathBar](../../com.aspose.slides/imathbar)

### group() {#group--}
```
public final IMathGroupingCharacter group()
```

Plaatst dit element in een groep met een onderste accolades

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**Retour:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Nieuwe instantie van type [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)

### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Plaatst dit element in een groep met een groeperingsteken, zoals een onderste accolades of een ander teken

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| character | char | Groeperingsteken, zoals BOTTOM CURLY BRACKET (U+23DF) of een ander teken |
| position | int | Positie van het groeperingsteken |
| verticalJustification | int | Verticale uitlijning van het groeperingsteken. Bepaalt de uitlijning van het object ten opzichte van de basislijn. Bijvoorbeeld, wanneer het groeperingsteken boven het object staat, betekent VerticalJustification Top dat de bovenkant van het object op de basislijn valt; wanneer VerticalJustification Bottom is, valt de onderkant van het object op de basislijn. |

**Retour:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Nieuwe instantie van type [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)

### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

Plaatst dit element in een border-box

> ```
> Voorbeeld:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Retour:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box met dit element geplaatst binnen

### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Plaatst dit element in een border-box

> ```
> Voorbeeld:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hideTop | boolean | Verberg bovenrand |
| hideBottom | boolean | Verberg onderrand |
| hideLeft | boolean | Verberg linkerrand |
| hideRight | boolean | Verberg rechterrand |
| strikethroughHorizontal | boolean | Horizontale doorhaling van de border-box |
| strikethroughVertical | boolean | Verticale doorhaling van de border-box |
| strikethroughBottomLeftToTopRight | boolean | Doorhaling van onder-links naar boven-rechts |
| strikethroughTopLeftToBottomRight | boolean | Doorhaling van boven-links naar onder-rechts |

**Retour:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box met dit element geplaatst binnen

### toBox() {#toBox--}
```
public final IMathBox toBox()
```

Plaatst dit element in een niet-visuele box (logische groepering) die wordt gebruikt om componenten van een vergelijking of andere wiskundige tekst te groeperen. Een box kan (bijvoorbeeld) dienen als operator-emulator met of zonder uitlijningspunt, dienen als regel-breekpunt, of gegroepeerd worden zodat geen regelbreuken binnen toegestaan zijn.

> ```
> Voorbeeld:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**Retour:**
[IMathBox](../../com.aspose.slides/imathbox) - Logische box met dit element geplaatst binnen

### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

Haalt kindelementen op

**Retour:**
com.aspose.slides.IMathElement[] - Array van [IMathElement](../../com.aspose.slides/imathelement)