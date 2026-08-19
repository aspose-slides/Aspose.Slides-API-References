---
title: IMathElement
second_title: Aspose.Slides for Java API Reference
description: Base interface of any mathematical element  fraction mathmatical text function expression with multiple elements etc
type: docs
url: /cs/com.aspose.slides/imathelement/
---```
public interface IMathElement
```

Základní rozhraní libovolného matematického elementu: zlomek, matematický text, funkce, výraz s více elementy atd.

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
> ```

## Metody

| Metoda | Popis |
| --- | --- |
| [getChildren()](#getChildren--) | Získá podřízené elementy |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Spojí matematický element a vytvoří matematický blok |
| [join(String mathText)](#join-java.lang.String-) | Spojí matematický text a vytvoří matematický blok |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [divide(String denominator)](#divide-java.lang.String-) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [enclose()](#enclose--) | Obalí matematický element závorkami |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Obalí tento element určenými znaky, jako jsou závorky nebo jiné znaky jako rámování |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Přijme funkci argumentu a použije tuto instanci jako název funkce |
| [function(String functionArgument)](#function-java.lang.String-) | Přijme funkci argumentu a použije tuto instanci jako název funkce |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Přijme zadanou funkci a použije tuto instanci jako argument |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Přijme zadanou funkci a použije tuto instanci jako argument |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Přijme zadanou funkci a použije tuto instanci jako argument |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Přijme zadanou funkci a použije tuto instanci jako argument a určený dodatečný argument |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Přijme zadanou funkci a použije tuto instanci jako argument a určený dodatečný argument |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Vytvoří dolní index |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Vytvoří dolní index |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Vytvoří horní index |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Vytvoří horní index |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Vytvoří dolní a horní index napravo |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Vytvoří dolní a horní index napravo |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Vytvoří dolní a horní index nalevo |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Vytvoří dolní a horní index nalevo |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Určuje matematický kořen zadaného řádu z určeného argumentu. |
| [radical(String degree)](#radical-java.lang.String-) | Určuje matematický kořen zadaného řádu z určeného argumentu. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Přijme horní limit |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Přijme horní limit |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Přijme dolní limit |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Přijme dolní limit |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Vytvoří N-ární operátor |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | Vytvoří N-ární operátor |
| [toMathArray()](#toMathArray--) | Umístí do vertikálního pole |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Přijme integrál |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Přijme integrál |
| [integral(int integralType)](#integral-int-) | Přijme integrál bez limitů |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | Přijme integrál |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | Přijme integrál |
| [accent(char accentCharacter)](#accent-char-) | Nastaví diakritiku (znak nad tímto elementem) |
| [overbar()](#overbar--) | Nastaví čáru nad tímto elementem |
| [underbar()](#underbar--) | Nastaví čáru pod tímto elementem |
| [group()](#group--) | Umístí tento element do skupiny pomocí spodní složené závorky |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Umístí tento element do skupiny pomocí seskupovacího znaku, jako je spodní složená závorka nebo jiný |
| [toBorderBox()](#toBorderBox--) | Umístí tento element do rámečkového boxu |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Umístí tento element do rámečkového boxu |
| [toBox()](#toBox--) | Umístí tento element do neviditelného boxu (logické seskupení), který slouží k seskupení komponent rovnice nebo jiné instance matematického textu. |
### getChildren() {#getChildren--}
```
public abstract IMathElement[] getChildren()
```

Získá podřízené elementy

**Vrací:**
com.aspose.slides.IMathElement[]
### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock join(IMathElement mathElement)
```

Spojí matematický element a vytvoří matematický blok

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
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Element, který má být spojen |

**Vrací:**
[IMathBlock](../../com.aspose.slides/imathblock) - Nový IMathBlock obsahující tuto instanci a zadaný argument
### join(String mathText) {#join-java.lang.String-}
```
public abstract IMathBlock join(String mathText)
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
public abstract IMathFraction divide(IMathElement denominator)
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
public abstract IMathFraction divide(String denominator)
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
public abstract IMathFraction divide(IMathElement denominator, int fractionType)
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
public abstract IMathFraction divide(String denominator, int fractionType)
```

Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem

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
public abstract IMathDelimiter enclose()
```

Obalí matematický element závorkami

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**Vrací:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Matematický element typu [IMathDelimiter](../../com.aspose.slides/imathdelimiter) zahrnující určené znaky jako rámování
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Obalí tento element určenými znaky, jako jsou závorky nebo jiné znaky jako rámování

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
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Matematický element typu [IMathDelimiter](../../com.aspose.slides/imathdelimiter) zahrnující určené znaky jako rámování
### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction function(IMathElement functionArgument)
```

Přijme funkci argumentu a použije tuto instanci jako název funkce

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
[IMathFunction](../../com.aspose.slides/imathfunction) - Nový matematický element typu [IMathFunction](../../com.aspose.slides/imathfunction)
### function(String functionArgument) {#function-java.lang.String-}
```
public abstract IMathFunction function(String functionArgument)
```

Přijme funkci argumentu a použije tuto instanci jako název funkce

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
[IMathFunction](../../com.aspose.slides/imathfunction) - Nový matematický element typu [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(IMathElement functionName)
```

Přijme zadanou funkci a použije tuto instanci jako argument

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
[IMathFunction](../../com.aspose.slides/imathfunction) - Nový matematický element typu [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(String functionName)
```

Přijme zadanou funkci a použije tuto instanci jako argument

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
[IMathFunction](../../com.aspose.slides/imathfunction) - Nový matematický element typu [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType)
```

Přijme zadanou funkci a použije tuto instanci jako argument

--------------------

> ```
> Příklad:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| functionType | int | Jedna z běžných typů funkcí pro jeden argument |

**Vrací:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nový matematický element typu [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

Přijme zadanou funkci a použije tuto instanci jako argument a dodatečný argument

--------------------

> ```
> Příklad:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Vrací logaritmus 'x' o základu '5'
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| functionType | int | Jedna z běžných typů funkcí pro dva argumenty: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Dodatečný argument v závislosti na typu funkce |

**Vrací:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nový matematický element typu [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

Přijme zadanou funkci a použije tuto instanci jako argument a dodatečný argument

--------------------

> ```
> Příklad:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Vrací logaritmus 'x' o základu '5'
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| functionType | int | Jedna z běžných typů funkcí pro dva argumenty: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | Dodatečný argument v závislosti na typu funkce |

**Vrací:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nový matematický element typu [IMathFunction](../../com.aspose.slides/imathfunction)
### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSubscriptElement setSubscript(IMathElement subscript)
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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Dolní index (dolní index napravo) |

**Vrací:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Nový matematický element typu [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public abstract IMathSubscriptElement setSubscript(String subscript)
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
| subscript | java.lang.String | Dolní index (dolní index napravo) |

**Vrací:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Nový matematický element typu [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSuperscriptElement setSuperscript(IMathElement superscript)
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
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Nový matematický element typu [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public abstract IMathSuperscriptElement setSuperscript(String superscript)
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
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Nový matematický element typu [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Dolní index (dolní index napravo) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Horní index (vyšší index vpravo) |

**Vrací:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Nový matematický element typu [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```
Vytvoří dolní a horní index vpravo

--------------------

> ```
> Příklad:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | Dolní index (dolní index vpravo) |
| superscript | java.lang.String | Horní index (horní index vpravo) |

**Návratová hodnota:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Nový matematický prvek typu [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```


Vytvoří dolní a horní index vlevo

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
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Dolní index (dolní index vlevo) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Horní index (horní index vlevo) |

**Návratová hodnota:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Nový matematický prvek typu [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```


Vytvoří dolní a horní index vlevo

--------------------

> ```
> Příklad:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | Dolní index (dolní index vlevo) |
| superscript | java.lang.String | Horní index (horní index vlevo) |

**Návratová hodnota:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Nový matematický prvek typu [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public abstract IMathRadical radical(IMathElement degree)
```


Určuje matematický kořen daného stupně z určeného argumentu.

--------------------

> ```
> Příklad:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Argument radikálu |

**Návratová hodnota:**
[IMathRadical](../../com.aspose.slides/imathradical) - Nová instance typu [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public abstract IMathRadical radical(String degree)
```


Určuje matematický kořen daného stupně z určeného argumentu.

--------------------

> ```
> Příklad:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```


**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| degree | java.lang.String | Argument radikálu |

**Návratová hodnota:**
[IMathRadical](../../com.aspose.slides/imathradical) - Nová instance typu [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setUpperLimit(IMathElement limit)
```


Přijímá horní mez

--------------------

> ```
> Příklad:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | mez |

**Návratová hodnota:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nová instance typu [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public abstract IMathLimit setUpperLimit(String limit)
```


Přijímá horní mez

--------------------

> ```
> Příklad:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | java.lang.String | mez |

**Návratová hodnota:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nová instance typu [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setLowerLimit(IMathElement limit)
```


Přijímá spodní mez

--------------------

> ```
> Příklad:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | mez |

**Návratová hodnota:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nová instance typu [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public abstract IMathLimit setLowerLimit(String limit)
```


Přijímá spodní mez

--------------------

> ```
> Příklad:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | java.lang.String | mez |

**Návratová hodnota:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nová instance typu [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```


Vytvoří N-ary operátor

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
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Typ N-ary operátoru |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Spodní mez |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Horní mez |

**Návratová hodnota:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nová instance typu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```


Vytvoří N-ary operátor

--------------------

> ```
> Příklad:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Typ N-ary operátoru |
| lowerLimit | java.lang.String | Spodní mez |
| upperLimit | java.lang.String | Horní mez |

**Návratová hodnota:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nová instance typu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public abstract IMathArray toMathArray()
```


Umístí do svislého pole

--------------------

> ```
> Příklad:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```


**Návratová hodnota:**
[IMathArray](../../com.aspose.slides/imatharray) - Nová instance typu [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```


Přijímá integrál

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
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Typ integrálu |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Spodní mez integrálu |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Horní mez integrálu |
| limitLocations | int | Umístění mezí |

**Návratová hodnota:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nová instance typu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```


Přijímá integrál

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
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Typ integrálu |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Spodní mez integrálu |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Horní mez integrálu |

**Návratová hodnota:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nová instance typu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public abstract IMathNaryOperator integral(int integralType)
```


Přijímá integrál bez mezí

--------------------

> ```
> Příklad:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Typ integrálu |

**Návratová hodnota:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nová instance typu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```


Přijímá integrál

--------------------

> ```
> Příklad:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```


**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Typ integrálu |
| lowerLimit | java.lang.String | Spodní mez integrálu |
| upperLimit | java.lang.String | Horní mez integrálu |
| limitLocations | int | Umístění mezí |

**Návratová hodnota:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nová instance typu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```


Přijímá integrál

--------------------

> ```
> Příklad:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Typ integrálu |
| lowerLimit | java.lang.String | Spodní mez integrálu |
| upperLimit | java.lang.String | Horní mez integrálu |

**Návratová hodnota:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nová instance typu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public abstract IMathAccent accent(char accentCharacter)
```


Nastaví akcent (znak nad tímto prvkem)

--------------------

> ```
> Příklad:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| accentCharacter | char | Znak akcentu. Hodnota by měla být v rozsahu (U+0300\\u2013U+036F) nebo (U+20D0\\u2013U+20EF) |

**Návratová hodnota:**
[IMathAccent](../../com.aspose.slides/imathaccent) - Nová instance typu [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public abstract IMathBar overbar()
```


Nastaví čáru na vrchu tohoto prvku

--------------------

> ```
> Příklad:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**Návratová hodnota:**
[IMathBar](../../com.aspose.slides/imathbar) - Nová instance typu [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public abstract IMathBar underbar()
```


Nastaví čáru na spodku tohoto prvku

--------------------

> ```
> Příklad:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Návratová hodnota:**
[IMathBar](../../com.aspose.slides/imathbar) - Nová instance typu [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public abstract IMathGroupingCharacter group()
```


Umístí tento prvek do skupiny pomocí spodní složené závorky

--------------------

> ```
> Příklad:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**Návratová hodnota:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Nová instance typu [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public abstract IMathGroupingCharacter group(char character, int position, int verticalJustification)
```


Umístí tento prvek do skupiny pomocí skupinového znaku, jako je SPODNÍ SLOŽENÁ ZÁVORKA (U+23DF) nebo jiný

--------------------

> ```
> Příklad:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| character | char | Skupinový znak, například SPODNÍ SLOŽENÁ ZÁVORKA (U+23DF) nebo jakýkoli jiný |
| position | int | Pozice skupinového znaku |
| verticalJustification | int | Vertikální zarovnání skupinového znaku. Určuje zarovnání objektu vzhledem k základní lince. Například když je skupinový znak nad objektem, vertikální zarovnání Top znamená, že horní část objektu leží na základní lince; když je nastaveno na Bottom, spodní část objektu leží na základní lince |

**Návratová hodnota:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Nová instance typu [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public abstract IMathBorderBox toBorderBox()
```


Umístí tento prvek do border-box

--------------------

> ```
> Příklad:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Návratová hodnota:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box s tímto prvkem uvnitř
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Umístí tento prvek do border-box

--------------------

> ```
> Příklad:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| hideTop | boolean | Skrýt horní okraj |
| hideBottom | boolean | Skrýt spodní okraj |
| hideLeft | boolean | Skrýt levý okraj |
| hideRight | boolean | Skrýt pravý okraj |
| strikethroughHorizontal | boolean | Border Box přeškrtnutí horizontální |
| strikethroughVertical | boolean | Border Box přeškrtnutí vertikální |
| strikethroughBottomLeftToTopRight | boolean | Border Box přeškrtnutí z levého dolního do pravého horního |
| strikethroughTopLeftToBottomRight | boolean | Border Box přeškrtnutí z levého horního do pravého dolního |

**Návratová hodnota:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box s tímto prvkem uvnitř
### toBox() {#toBox--}
```
public abstract IMathBox toBox()
```


Umístí tento prvek do neviditelného boxu (logické seskupení), který se používá k seskupení komponent rovnice nebo jiného matematického textu. Boxovaný objekt může (například) sloužit jako emulátor operátoru s nebo bez zarovnávacího bodu, sloužit jako bod zalomení řádku nebo být seskupen tak, aby neumožňoval zalomení řádku uvnitř.

--------------------

> ```
> Příklad:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```


**Návratová hodnota:**
[IMathBox](../../com.aspose.slides/imathbox) - Logický box s tímto prvkem uvnitř