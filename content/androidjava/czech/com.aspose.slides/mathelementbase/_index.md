---
title: MathElementBase
second_title: Aspose.Slides pro Android prostřednictvím reference Java API
description: Základní třída pro IMathElement s implementací některých metod, které jsou společné pro všechny zděděné třídy. Pouze pro interní použití.
type: docs
url: /cs/com.aspose.slides/mathelementbase/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

Base class for IMathElement with the implementation of some methods that are common to all inherited classes For internal use only. Inherited class must be IMathElement.
## Metody

| Metoda | Popis |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | Vrací objekt Parent_Immediate. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Spojí matematický prvek a vytvoří matematický blok |
| [join(String mathText)](#join-java.lang.String-) | Spojí matematický text a vytvoří matematický blok |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [divide(String denominator)](#divide-java.lang.String-) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [enclose()](#enclose--) | Obalí matematický prvek závorkami |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Obalí matematický prvek určenými znaky, jako jsou závorky nebo jiné znaky, jako rámec |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Získá funkci s argumentem a použije tuto instanci jako název funkce |
| [function(String functionArgument)](#function-java.lang.String-) | Získá funkci s argumentem a použije tuto instanci jako název funkce |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Získá zadanou funkci s touto instancí jako argumentem |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Získá zadanou funkci s touto instancí jako argumentem |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Získá zadanou funkci s touto instancí jako argumentem |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Získá zadanou funkci s touto instancí jako argumentem a zadaným dodatečným argumentem |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Získá zadanou funkci s touto instancí jako argumentem a zadaným dodatečným argumentem |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Vytvoří dolní index |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Vytvoří dolní index |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Vytvoří horní index |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Vytvoří horní index |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Vytvoří dolní a horní index napravo |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Vytvoří dolní a horní index napravo |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Vytvoří dolní a horní index nalevo |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Vytvoří dolní a horní index nalevo |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Určuje matematický odmocninu daného stupně ze zadaného argumentu. |
| [radical(String degree)](#radical-java.lang.String-) | Určuje matematický odmocninu daného stupně ze zadaného argumentu. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Získá horní mez |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Získá horní mez |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Získá dolní mez |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Získá dolní mez |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Vytvoří N-ární operátor |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | Vytvoří N-ární operátor |
| [toMathArray()](#toMathArray--) | Umístí do vertikálního pole |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Získá integrál |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Získá integrál |
| [integral(int integralType)](#integral-int-) | Získá integrál bez mezí |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | Získá integrál |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | Získá integrál |
| [accent(char accentCharacter)](#accent-char-) | Nastaví akcent (znak nad tímto prvkem) |
| [overbar()](#overbar--) | Nastaví čáru nad tímto prvkem |
| [underbar()](#underbar--) | Nastaví čáru pod tímto prvkem |
| [group()](#group--) | Umístí tento prvek do skupiny pomocí dolní složené závorky |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Umístí tento prvek do skupiny pomocí skupinového znaku, jako je dolní složená závorka nebo jiný |
| [toBorderBox()](#toBorderBox--) | Umístí tento prvek do rámečkového pole |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Umístí tento prvek do rámečkového pole |
| [toBox()](#toBox--) | Umístí tento prvek do neviditelného pole (logické seskupení), které slouží ke skupování komponent rovnice nebo jiných instancí matematického textu. |
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

Spojí matematický prvek a vytvoří matematický blok

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
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Prvek, který má být spojen |

**Vrací:**
[IMathBlock](../../com.aspose.slides/imathblock) - Nový IMathBlock obsahující tuto instanci a zadaný argument
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Spojí matematický text a vytvoří matematický blok

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
| mathText | java.lang.String | Matematický text, který má být spojen |

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

Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem

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

Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem

--------------------

> ```
> Příklad:
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

Obalí matematický prvek závorkami

--------------------

> ```
> Příklad:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```


**Vrací:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - The math element of type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) which includes the parenthesis
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Obalí matematický prvek určenými znaky, jako jsou závorky nebo jiné znaky, jako rámec

--------------------

> ```
> Příklad:
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
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - The math element of type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) which includes specified characters as framing
### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```

Získá funkci s argumentem a použije tuto instanci jako název funkce

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
[IMathFunction](../../com.aspose.slides/imathfunction) - New math element of type [IMathFunction](../../com.aspose.slides/imathfunction)
### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```

Získá funkci s argumentem a použije tuto instanci jako název funkce

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
[IMathFunction](../../com.aspose.slides/imathfunction) - New math element of type [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```

Získá zadanou funkci s touto instancí jako argumentem

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
[IMathFunction](../../com.aspose.slides/imathfunction) - New math element of type [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(String functionName)
```

Získá zadanou funkci s touto instancí jako argumentem

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
[IMathFunction](../../com.aspose.slides/imathfunction) - New math element of type [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public final IMathFunction asArgumentOfFunction(int functionType)
```

Získá zadanou funkci s touto instancí jako argumentem

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
| functionType | int | Jeden z běžných typů funkcí s jedním argumentem |

**Vrací:**
[IMathFunction](../../com.aspose.slides/imathfunction) - New math element of type [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

Získá zadanou funkci s touto instancí jako argumentem a zadaným dodatečným argumentem

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Vrací logaritmus 'x' se základem '5'
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| functionType | int | Jeden z běžných typů funkcí se dvěma argumenty: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Dodatečný argument v závislosti na typu funkce |

**Vrací:**
[IMathFunction](../../com.aspose.slides/imathfunction) - New math element of type [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

Získá zadanou funkci s touto instancí jako argumentem a zadaným dodatečným argumentem

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Vrací logaritmus 'x' se základem '5'
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| functionType | int | Jeden z běžných typů funkcí se dvěma argumenty: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | Dodatečný argument v závislosti na typu funkce |

**Vrací:**
[IMathFunction](../../com.aspose.slides/imathfunction) - New math element of type [IMathFunction](../../com.aspose.slides/imathfunction)
### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```

Vytvoří dolní index

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Dolní index (nižší index napravo) |

**Vrací:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - New math element of type [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```

Vytvoří dolní index

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| subscript | java.lang.String | Dolní index (nižší index napravo) |

**Vrací:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - New math element of type [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
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
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Horní index (vyšší index napravo) |

**Vrací:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - New math element of type [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
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
| superscript | java.lang.String | Horní index (vyšší index napravo) |

**Vrací:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - New math element of type [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

Vytvoří dolní a horní index napravo

--------------------

> ```
> Příklad:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Dolní index (nižší index napravo) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Horní index (vyšší index napravo) |

**Vrací:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - New math element of type [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

Vytvoří dolní a horní index napravo

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| subscript | java.lang.String | Dolní index (nižší index napravo) |
| superscript | java.lang.String | Horní index (vyšší index napravo) |

**Vrací:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - New math element of type [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Vytvoří dolní a horní index nalevo

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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Dolní index (nižší index nalevo) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Horní index (vyšší index nalevo) |

**Vrací:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - New math element of type [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Vytvoří dolní a horní index nalevo

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
| subscript | java.lang.String | Dolní index (nižší index nalevo) |
| superscript | java.lang.String | Horní index (vyšší index nalevo) |

**Vrací:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - New math element of type [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

Určuje matematický odmocninu daného stupně ze zadaného argumentu.

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
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Argument radikálu |

**Vrací:**
[IMathRadical](../../com.aspose.slides/imathradical) - New instance of type [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```

Určuje matematický odmocninu daného stupně ze zadaného argumentu.

--------------------

> ```
> Příklad:
>  
```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| degree | java.lang.String | Argument radikálu |

**Vrací:**
[IMathRadical](../../com.aspose.slides/imathradical) - New instance of type [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```

Získá horní mez

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

**Vrací:**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```

Získá horní mez

--------------------

> ```
> Příklad:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Vrací:**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

Získá dolní mez

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

**Vrací:**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

Získá dolní mez

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

**Vrací:**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
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
| type | int | Typ N-árního operátoru |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Dolní mez |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Horní mez |

**Vrací:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

Vytvoří N-ární operátor

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| type | int | Typ N-árního operátoru |
| lowerLimit | java.lang.String | Dolní mez |
| upperLimit | java.lang.String | Horní mez |

**Vrací:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Umístí do vertikálního pole

--------------------

> ```
> Příklad:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Vrací:**
[IMathArray](../../com.aspose.slides/imatharray) - New instance of type [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

Získá integrál

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
| integralType | int | Typ integrálu |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Dolní mez integrálu |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Horní mez integrálu |
| limitLocations | int | umístění mezí |

**Vrací:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

Získá integrál

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
| integralType | int | Typ integrálu |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Dolní mez integrálu |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Horní mez integrálu |

**Vrací:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

Získá integrál bez mezí

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
| integralType | int | Typ integrálu |

**Vrací:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

Získá integrál

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
| integralType | int | Typ integrálu |
| lowerLimit | java.lang.String | Dolní mez integrálu |
| upperLimit | java.lang.String | Horní mez integrálu |
| limitLocations | int | umístění mezí |

**Vrací:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

Získá integrál

--------------------

> ```
> Příklad:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| integralType | int | Typ integrálu |
| lowerLimit | java.lang.String | Dolní mez integrálu |
| upperLimit | java.lang.String | Horní mez integrálu |

**Vrací:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

Nastaví akcent (znak nad tímto prvkem)

--------------------

> ```
> Příklad:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| accentCharacter | char | Akcentní znak. Hodnota by měla spadat do rozsahu (U+0300\\u2013U+036F) nebo (U+20D0\\u2013U+20EF) |

**Vrací:**
[IMathAccent](../../com.aspose.slides/imathaccent) - New instance of type [IMathAccent](../../com.aspose.slides/imathaccent)
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

**Vrací:**
[IMathBar](../../com.aspose.slides/imathbar) - New instance of type [IMathBar](../../com.aspose.slides/imathbar)
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

**Vrací:**
[IMathBar](../../com.aspose.slides/imathbar) - New instance of type [IMathBar](../../com.aspose.slides/imathbar)
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
> ```

**Vrací:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - New instance of type [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Umístí tento prvek do skupiny pomocí skupinového znaku, jako je dolní složená závorka nebo jiný

--------------------

> ```
> Příklad:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| character | char | Skupinový znak, například DOLNÍ SLOŽENÁ ZÁVORKA (U+23DF) nebo jiný |
| position | int | Pozice skupinového znaku |
| verticalJustification | int | Vertikální zarovnání skupinového znaku. Určuje zarovnání objektu vůči základní linii. Například když je skupinový znak nad objektem, Vertikální zarovnání Top znamená, že horní část objektu leží na základní linii; když je nastaveno Vertikální zarovnání Bottom, spodní část objektu leží na základní linii. |

**Vrací:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - New instance of type [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

Umístí tento prvek do rámečkového pole

--------------------

> ```
> Příklad:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Vrací:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box with this element placed inside
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Umístí tento prvek do rámečkového pole

--------------------

> ```
> Příklad:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| hideTop | boolean | Skrýt horní okraj |
| hideBottom | boolean | Skrýt dolní okraj |
| hideLeft | boolean | Skrýt levý okraj |
| hideRight | boolean | Skrýt pravý okraj |
| strikethroughHorizontal | boolean | Překřížka vodorovná |
| strikethroughVertical | boolean | Překřížka svislá |
| strikethroughBottomLeftToTopRight | boolean | Překřížka z levého dolního do pravého horního |
| strikethroughTopLeftToBottomRight | boolean | Překřížka z levého horního do pravého dolního |

**Vrací:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box with this element placed inside
### toBox() {#toBox--}
```
public final IMathBox toBox()
```

Umístí tento prvek do neviditelného pole (logické seskupení), které slouží ke skupování komponent rovnice nebo jiných instancí matematického textu. Objekty v rámečku mohou (například) sloužit jako emulátory operátorů s nebo bez zarovnávacího bodu, sloužit jako místo zalomení řádku, nebo být seskupeny tak, aby nedovolily zalomení řádku uvnitř.

--------------------

> ```
> Příklad:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**Vrací:**
[IMathBox](../../com.aspose.slides/imathbox) - Logical box with this element placed inside
### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

Získá podřízené prvky

**Vrací:**
com.aspose.slides.IMathElement[] - Array of [IMathElement](../../com.aspose.slides/imathelement)