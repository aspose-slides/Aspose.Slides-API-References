---
title: MathElementBase
second_title: Aspose.Slides pro Java API referenci
description: Základní třída pro IMathElement s implementací některých metod, které jsou společné pro všechny zděděné třídy. Pouze pro interní použití.
type: docs
url: /cs/com.aspose.slides/mathelementbase/
---
**Dědění:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

Základní třída pro IMathElement s implementací některých metod, které jsou společné pro všechny odvozené třídy. Pouze pro interní použití. Odvozená třída musí být IMathElement.
## Metody

| Metoda | Popis |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | Vrací objekt Parent_Immediate. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Spojuje matematický prvek a vytváří matematický blok |
| [join(String mathText)](#join-java.lang.String-) | Spojuje matematický text a vytváří matematický blok |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [divide(String denominator)](#divide-java.lang.String-) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Vytvoří zlomek daného typu s tímto čitatelem a zadaným jmenovatelem |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Vytvoří zlomek daného typu s tímto čitatelem a zadaným jmenovatelem |
| [enclose()](#enclose--) | Obalí matematický prvek do závorek |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Obalí matematický prvek určenými znaky, jako jsou závorky nebo jiné znaky, jako rámeček |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Přijímá funkci argumentu a používá tuto instanci jako název funkce |
| [function(String functionArgument)](#function-java.lang.String-) | Přijímá funkci argumentu a používá tuto instanci jako název funkce |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Přijímá zadanou funkci a používá tuto instanci jako argument |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Přijímá zadanou funkci a používá tuto instanci jako argument |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Přijímá zadanou funkci a používá tuto instanci jako argument |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Přijímá zadanou funkci a používá tuto instanci jako argument a zadaný další argument |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Přijímá zadanou funkci a používá tuto instanci jako argument a zadaný další argument |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Vytvoří dolní index |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Vytvoří dolní index |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Vytvoří horní index |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Vytvoří horní index |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Vytvoří dolní a horní index vpravo |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Vytvoří dolní a horní index vpravo |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Vytvoří dolní a horní index vlevo |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Vytvoří dolní a horní index vlevo |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Určuje matematický kořen daného řádu ze zadaného argumentu. |
| [radical(String degree)](#radical-java.lang.String-) | Určuje matematický kořen daného řádu ze zadaného argumentu. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Přijímá horní limit |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Přijímá horní limit |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Přijímá dolní limit |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Přijímá dolní limit |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Vytvoří N-ární operátor |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | Vytvoří N-ární operátor |
| [toMathArray()](#toMathArray--) | Vloží svislé pole |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Přijímá integrál |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Přijímá integrál |
| [integral(int integralType)](#integral-int-) | Přijímá integrál bez mezí |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | Přijímá integrál bez mezí |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | Přijímá integrál bez mezí |
| [accent(char accentCharacter)](#accent-char-) | Nastaví akcent (znak nad tímto prvkem) |
| [overbar()](#overbar--) | Nastaví čáru nad tímto prvkem |
| [underbar()](#underbar--) | Nastaví čáru pod tímto prvkem |
| [group()](#group--) | Umístí tento prvek do skupiny pomocí spodní složené závorky |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Umístí tento prvek do skupiny pomocí seskupovacího znaku, jako je spodní složená závorka nebo jiný |
| [toBorderBox()](#toBorderBox--) | Umístí tento prvek do rámečkového pole |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Umístí tento prvek do rámečkového pole |
| [toBox()](#toBox--) | Umístí tento prvek do neviditelného pole (logické seskupení), které se používá k seskupení komponent rovnice nebo jiných instancí matematického textu. |
| [getChildren()](#getChildren--) | Získá podřízené prvky |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Vrací objekt Parent_Immediate. Pouze pro čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Spojuje matematický prvek a vytváří matematický blok

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Prvek, který se má spojit |

**Vrací:**
[IMathBlock](../../com.aspose.slides/imathblock) - Nový IMathBlock obsahující tuto instanci a zadaný argument

### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Spojuje matematický text a vytváří matematický blok

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| mathText | java.lang.String | Matematický text, který se má spojit |

**Vrací:**
[IMathBlock](../../com.aspose.slides/imathblock) - Nový IMathBlock obsahující tuto instanci a zadaný argument

### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public final IMathFraction divide(IMathElement denominator)
```

Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Jmenovatel |

**Vrací:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nový zlomek

### divide(String denominator) {#divide-java.lang.String-}
```
public final IMathFraction divide(String denominator)
```

Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| denominator | java.lang.String | Jmenovatel |

**Vrací:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nový zlomek

### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction divide(IMathElement denominator, int fractionType)
```

Vytvoří zlomek daného typu s tímto čitatelem a zadaným jmenovatelem

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Jmenovatel |
| fractionType | int | Typ zlomku: Bar, NoBar, Skewed, Linear |

**Vrací:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nový zlomek

### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public final IMathFraction divide(String denominator, int fractionType)
```

Vytvoří zlomek daného typu s tímto čitatelem a zadaným jmenovatelem

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| denominator | java.lang.String | Jmenovatel |
| fractionType | int | Typ zlomku: Bar, NoBar, Skewed, Linear |

**Vrací:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nový zlomek

### enclose() {#enclose--}
```
public final IMathDelimiter enclose()
```

Obalí matematický prvek do závorek

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```


**Vrací:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Matematický prvek typu [IMathDelimiter](../../com.aspose.slides/imathdelimiter) zahrnující závorky

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Obalí matematický prvek určenými znaky, jako jsou závorky nebo jiné znaky, jako rámeček

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| beginningCharacter | char | Počáteční znak (obvykle levá závorka) |
| endingCharacter | char | Koncový znak (obvykle pravá závorka) |

**Vrací:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Matematický prvek typu [IMathDelimiter](../../com.aspose.slides/imathdelimiter) zahrnující určené znaky jako rámeček

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```

Přijímá funkci argumentu a používá tuto instanci jako název funkce

--------------------

> ```
> Příklad:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argument funkce |

**Vrací:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nový matematický prvek typu [IMathFunction](../../com.aspose.slides/imathfunction)

### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```

Přijímá funkci argumentu a používá tuto instanci jako název funkce

--------------------

> ```
> Příklad:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| functionArgument | java.lang.String | Argument funkce |

**Vrací:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nový matematický prvek typu [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```

Přijímá zadanou funkci a používá tuto instanci jako argument

--------------------

> ```
> Příklad:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | Název funkce |

**Vrací:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nový matematický prvek typu [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(String functionName)
```

Přijímá zadanou funkci a používá tuto instanci jako argument

--------------------

> ```
> Příklad:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| functionName | java.lang.String | Název funkce |

**Vrací:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nový matematický prvek typu [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public final IMathFunction asArgumentOfFunction(int functionType)
```

Přijímá zadanou funkci a používá tuto instanci jako argument

--------------------

> ```
> Příklad:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| functionType | int | Jeden ze společných typů funkce s jedním argumentem |

**Vrací:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nový matematický prvek typu [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

Přijímá zadanou funkci a používá tuto instanci jako argument a zadaný další argument

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Returns the logarithm of 'x' to the base '5'
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| functionType | int | Jeden ze společných typů funkce se dvěma argumenty: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Další argument v závislosti na typu funkce |

**Vrací:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nový matematický prvek typu [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

Přijímá zadanou funkci a používá tuto instanci jako argument a zadaný další argument

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Vrací logaritmus 'x' k základu '5'
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| functionType | int | Jeden ze společných typů funkce se dvěma argumenty: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | Další argument v závislosti na typu funkce |

**Vrací:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nový matematický prvek typu [IMathFunction](../../com.aspose.slides/imathfunction)

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```

Vytvoří dolní index

--------------------

> ```
> Příklad:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Dolní index (nižší index vpravo) |

**Vrací:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Nový matematický prvek typu [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```

Vytvoří dolní index

--------------------

> ```
> Příklad:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| subscript | java.lang.String | Dolní index (nižší index vpravo) |

**Vrací:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Nový matematický prvek typu [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

Vytvoří horní index

--------------------

> ```
> Příklad:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Horní index (vyšší index vpravo) |

**Vrací:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Nový matematický prvek typu [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```

Vytvoří horní index

--------------------

> ```
> Příklad:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| superscript | java.lang.String | Horní index (vyšší index vpravo) |

**Vrací:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Nový matematický prvek typu [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

Vytvoří dolní a horní index vpravo

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Dolní index (nižší index vpravo) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Horní index (vyšší index vpravo) |

**Vrací:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Nový matematický prvek typu [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

Vytvoří dolní a horní index vpravo
> ```
> Příklad:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| subscript | java.lang.String | Subscript (lower index on the right) |
| superscript | java.lang.String | Superscript (upper index on the right) |

**Návratová hodnota:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Nový matematický prvek typu [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Vytvoří dolní index a horní index vlevo

--------------------

> ```
> Příklad:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subscript (lower index on the left) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Superscript (upper index on the left) |

**Návratová hodnota:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Nový matematický prvek typu [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Vytvoří dolní index a horní index vlevo

--------------------

> ```
> Příklad:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| subscript | java.lang.String | Subscript (lower index on the left) |
| superscript | java.lang.String | Superscript (upper index on the left) |

**Návratová hodnota:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Nový matematický prvek typu [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

Určuje matematickou odmocninu zadaného řádu ze zadaného argumentu.

--------------------

> ```
> Příklad:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Argument of Radical |

**Návratová hodnota:**
[IMathRadical](../../com.aspose.slides/imathradical) - Nový výskyt typu [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```

Určuje matematickou odmocninu zadaného řádu ze zadaného argumentu.

--------------------

> ```
> Příklad:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| degree | java.lang.String | Argument of Radical |

**Návratová hodnota:**
[IMathRadical](../../com.aspose.slides/imathradical) - Nový výskyt typu [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```

Přijímá horní limit

--------------------

> ```
> Příklad:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Návratová hodnota:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nový výskyt typu [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```

Přijímá horní limit

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Návratová hodnota:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nový výskyt typu [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

Přijímá dolní limit

--------------------

> ```
> Příklad:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Návratová hodnota:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nový výskyt typu [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

Přijímá dolní limit

--------------------

> ```
> Příklad:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Návratová hodnota:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nový výskyt typu [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

Vytvoří N-ární operátor

--------------------

> ```
> Příklad:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| type | int | The N-ary operator type |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | The lower limit |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | The upper limit |

**Návratová hodnota:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nový výskyt typu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

Vytvoří N-ární operátor

--------------------

> ```
> Příklad:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| type | int | The N-ary operator type |
| lowerLimit | java.lang.String | The lower limit |
| upperLimit | java.lang.String | The upper limit |

**Návratová hodnota:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nový výskyt typu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Umístí do svislého pole

--------------------

> ```
> Příklad:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Návratová hodnota:**
[IMathArray](../../com.aspose.slides/imatharray) - Nový výskyt typu [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

Vytvoří integrál

--------------------

> ```
> Příklad:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| integralType | int | Integral type |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Lower limit of integral |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Upper limit of integral |
| limitLocations | int | location of limits |

**Návratová hodnota:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nový výskyt typu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

Vytvoří integrál

--------------------

> ```
> Příklad:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| integralType | int | Integral type |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Lower limit of integral |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Upper limit of integral |

**Návratová hodnota:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nový výskyt typu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

Vytvoří integrál bez limitů

--------------------

> ```
> Příklad:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| integralType | int | Integral type |

**Návratová hodnota:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nový výskyt typu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

Vytvoří integrál

--------------------

> ```
> Příklad:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| integralType | int | Integral type |
| lowerLimit | java.lang.String | Lower limit of integral |
| upperLimit | java.lang.String | Upper limit of integral |
| limitLocations | int | location of limits |

**Návratová hodnota:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nový výskyt typu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

Vytvoří integrál

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| integralType | int | Integral type |
| lowerLimit | java.lang.String | Lower limit of integral |
| upperLimit | java.lang.String | Upper limit of integral |

**Návratová hodnota:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nový výskyt typu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

Nastaví akcent (znak nad tímto prvkem)

--------------------

> ```
public final IMathAccent accent(char accentCharacter)
```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| accentCharacter | char | Accent character. The value should be within the range of (U+0300\\u2013U+036F) or (U+20D0\\u2013U+20EF) |

**Návratová hodnota:**
[IMathAccent](../../com.aspose.slides/imathaccent) - Nový výskyt typu [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public final IMathBar overbar()
```

Nastaví čáru nad tímto prvkem

--------------------

> ```
> Příklad:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**Návratová hodnota:**
[IMathBar](../../com.aspose.slides/imathbar) - Nový výskyt typu [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public final IMathBar underbar()
```

Nastaví čáru pod tímto prvkem

--------------------

> ```
> Příklad:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```


**Návratová hodnota:**
[IMathBar](../../com.aspose.slides/imathbar) - Nový výskyt typu [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public final IMathGroupingCharacter group()
```

Umístí tento prvek do skupiny pomocí dolní složené závorky

--------------------

> ```
> Příklad:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
```

**Návratová hodnota:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Nový výskyt typu [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Umístí tento prvek do skupiny pomocí skupinového znaku, například dolní složené závorky nebo jiného

--------------------

> ```
> Příklad:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| character | char | Grouping Character such as BOTTOM CURLY BRACKET (U+23DF) or any other |
| position | int | Position of grouping character |
| verticalJustification | int | Vertical justification of group character. Specifies the alignment of the object with respect to the baseline. For example, when the group character is above the object, VerticalJustification of Top signifies that the top of the object falls on the baseline; when VerticalJustification is set to Bottom, the bottom of the object is on the baseline |

**Návratová hodnota:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Nový výskyt typu [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

Umístí tento prvek do rámečku

--------------------

> ```
> Příklad:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```


**Návratová hodnota:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Okrajový rámeček s tímto prvkem umístěným uvnitř
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Umístí tento prvek do rámečku

--------------------

> ```
> Příklad:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| hideTop | boolean | Hide Top Edge |
| hideBottom | boolean | Hide Bottom Edge |
| hideLeft | boolean | Hide Left Edge |
| hideRight | boolean | Hide Right Edge |
| strikethroughHorizontal | boolean | Border Box Strikethrough Horizontal |
| strikethroughVertical | boolean | Border Box Strikethrough Vertical |
| strikethroughBottomLeftToTopRight | boolean | Border Box Strikethrough Bottom-Left to Top-Right |
| strikethroughTopLeftToBottomRight | boolean | Border Box Strikethrough Top-Left to Bottom-Right |

**Návratová hodnota:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Okrajový rámeček s tímto prvkem umístěným uvnitř
### toBox() {#toBox--}
```
public final IMathBox toBox()
```

Umístí tento prvek do neviditelného rámečku (logické seskupení), který se používá k seskupení komponent rovnice nebo jiného matematického textu. Zkrácený objekt může (například) sloužit jako emulace operátoru s nebo bez zarovnávacího bodu, sloužit jako bod zalomení řádku, nebo být seskupen tak, aby neumožňoval zalomení řádku uvnitř.

--------------------

> ```
> Příklad:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```


**Návratová hodnota:**
[IMathBox](../../com.aspose.slides/imathbox) - Logický rámeček s tímto prvkem umístěným uvnitř
### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

Získá podřízené prvky

**Návratová hodnota:**
com.aspose.slides.IMathElement[] - Pole [IMathElement](../../com.aspose.slides/imathelement)