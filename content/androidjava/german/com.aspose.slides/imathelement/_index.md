---
title: IMathElement
second_title: Aspose.Slides für Android über Java API-Referenz
description: Basisschnittstelle jedes mathematischen Elements: Bruch, mathematischer Text, Funktion, Ausdruck mit mehreren Elementen usw.
type: docs
url: /de/com.aspose.slides/imathelement/
---```
public interface IMathElement
```

Basisschnittstelle jedes mathematischen Elements: Bruch, mathematischer Text, Funktion, Ausdruck mit mehreren Elementen usw.

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
> ```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getChildren()](#getChildren--) | Kind-Elemente abrufen |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Fügt ein mathematisches Element hinzu und bildet einen mathematischen Block |
| [join(String mathText)](#join-java.lang.String-) | Fügt einen mathematischen Text hinzu und bildet einen mathematischen Block |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [divide(String denominator)](#divide-java.lang.String-) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [enclose()](#enclose--) | Umschließt ein mathematisches Element in Klammern |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Umschließt dieses Element in angegebenen Zeichen wie Klammern oder anderen Zeichen als Rahmen |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird |
| [function(String functionArgument)](#function-java.lang.String-) | Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument verwendet wird |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument verwendet wird |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument verwendet wird |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument verwendet wird, sowie ein angegebenes zusätzliches Argument |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument verwendet wird, sowie ein angegebenes zusätzliches Argument |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Erzeugt eine Tiefstellung |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Erzeugt eine Tiefstellung |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Erzeugt eine Hochstellung |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Erzeugt eine Hochstellung |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Erzeugt Tief- und Hochstellung auf der rechten Seite |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Erzeugt Tief- und Hochstellung auf der rechten Seite |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Erzeugt Tief- und Hochstellung auf der linken Seite |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Erzeugt Tief- und Hochstellung auf der linken Seite |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [radical(String degree)](#radical-java.lang.String-) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Nimmt obere Grenze |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Nimmt obere Grenze |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Nimmt untere Grenze |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Nimmt untere Grenze |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Erstellt einen N-ären Operator |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | Erstellt einen N-ären Operator |
| [toMathArray()](#toMathArray--) | Fügt ein vertikales Array ein |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Nimmt das Integral |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Nimmt das Integral |
| [integral(int integralType)](#integral-int-) | Nimmt das Integral ohne Grenzen |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | Nimmt das Integral |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | Nimmt das Integral |
| [accent(char accentCharacter)](#accent-char-) | Setzt ein Akzentzeichen (ein Zeichen über diesem Element) |
| [overbar()](#overbar--) | Setzt einen Balken über diesem Element |
| [underbar()](#underbar--) | Setzt einen Balken unter diesem Element |
| [group()](#group--) | Platziert dieses Element in einer Gruppe mittels einer unteren geschweiften Klammer |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Platziert dieses Element in einer Gruppe mittels eines Gruppierungszeichens, z. B. einer unteren geschweiften Klammer oder einem anderen |
| [toBorderBox()](#toBorderBox--) | Platziert dieses Element in einer Rand-Box |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Platziert dieses Element in einer Rand-Box |
| [toBox()](#toBox--) | Platziert dieses Element in einer nicht sichtbaren Box (logische Gruppierung), die verwendet wird, um Komponenten einer Gleichung oder andere Instanzen mathematischen Textes zu gruppieren. |

### getChildren() {#getChildren--}
```
public abstract IMathElement[] getChildren()
```


Ruft Kind-Elemente ab

**Rückgabewert:**
com.aspose.slides.IMathElement[]

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock join(IMathElement mathElement)
```


Fügt ein mathematisches Element hinzu und bildet einen mathematischen Block

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Das zu verbindende Element |

**Rückgabewert:**
[IMathBlock](../../com.aspose.slides/imathblock) - Ein neuer IMathBlock, der diese Instanz und das angegebene Argument enthält

### join(String mathText) {#join-java.lang.String-}
```
public abstract IMathBlock join(String mathText)
```


Fügt einen mathematischen Text hinzu und bildet einen mathematischen Block

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathText | java.lang.String | Mathematischer Text, der hinzugefügt werden soll |

**Rückgabewert:**
[IMathBlock](../../com.aspose.slides/imathblock) - Ein neuer IMathBlock, der diese Instanz und das angegebene Argument enthält

### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction divide(IMathElement denominator)
```


Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Nenner |

**Rückgabewert:**
[IMathFraction](../../com.aspose.slides/imathfraction) - neuer Bruch

### divide(String denominator) {#divide-java.lang.String-}
```
public abstract IMathFraction divide(String denominator)
```


Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner

--------------------

> ```
> Example:
>  
>  IMMathElement numerator = new MathematicalText("x");
>  IMMathFraction fraction = numerator.divide("y");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| denominator | java.lang.String | Nenner |

**Rückgabewert:**
[IMathFraction](../../com.aspose.slides/imathfraction) - neuer Bruch

### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction divide(IMathElement denominator, int fractionType)
```


Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Nenner |
| fractionType | int | Bruchtyp: Bar, NoBar, Skewed, Linear |

**Rückgabewert:**
[IMathFraction](../../com.aspose.slides/imathfraction) - neuer Bruch

### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public abstract IMathFraction divide(String denominator, int fractionType)
```


Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| denominator | java.lang.String | Nenner |
| fractionType | int | Bruchtyp: Bar, NoBar, Skewed, Linear |

**Rückgabewert:**
[IMathFraction](../../com.aspose.slides/imathfraction) - neuer Bruch

### enclose() {#enclose--}
```
public abstract IMathDelimiter enclose()
```


Umschließt ein mathematisches Element in Klammern

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**Rückgabewert:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Das Math-Element vom Typ [IMathDelimiter](../../com.aspose.slides/imathdelimiter) inklusive der Klammern

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```


Umschließt dieses Element in angegebenen Zeichen wie Klammern oder anderen Zeichen als Rahmen

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| beginningCharacter | char | Anfangszeichen (meist linke Klammer) |
| endingCharacter | char | Endzeichen (meist rechte Klammer) |

**Rückgabewert:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Das Math-Element vom Typ [IMathDelimiter](../../com.aspose.slides/imathdelimiter) inklusive der angegebenen Rahmenzeichen

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction function(IMathElement functionArgument)
```


Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | Ein Argument der Funktion |

**Rückgabewert:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Neues Math-Element vom Typ [IMathFunction](../../com.aspose.slides/imathfunction)

### function(String functionArgument) {#function-java.lang.String-}
```
public abstract IMathFunction function(String functionArgument)
```


Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionArgument | java.lang.String | Ein Argument der Funktion |

**Rückgabewert:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Neues Math-Element vom Typ [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(IMathElement functionName)
```


Nimmt die angegebene Funktion, wobei diese Instanz als Argument verwendet wird

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | Funktionsname |

**Rückgabewert:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Neues Math-Element vom Typ [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(String functionName)
```


Nimmt die angegebene Funktion, wobei diese Instanz als Argument verwendet wird

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionName | java.lang.String | Funktionsname |

**Rückgabewert:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Neues Math-Element vom Typ [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType)
```


Nimmt die angegebene Funktion, wobei diese Instanz als Argument verwendet wird

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionType | int | Einer der gebräuchlichen Funktionstypen mit einem Argument |

**Rückgabewert:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Neues Math-Element vom Typ [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```


Nimmt die angegebene Funktion, wobei diese Instanz als Argument verwendet wird, und einen zusätzlichen Argument

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Gibt den Logarithmus von 'x' zur Basis '5' zurück
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionType | int | Einer der gebräuchlichen Funktionstypen mit zwei Argumenten: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Zusätzliches Argument abhängig vom Funktionstyp |

**Rückgabewert:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Neues Math-Element vom Typ [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```


Nimmt die angegebene Funktion, wobei diese Instanz als Argument verwendet wird, und ein zusätzliches Argument

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Gibt den Logarithmus von 'x' zur Basis '5' zurück
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionType | int | Einer der gebräuchlichen Funktionstypen mit zwei Argumenten: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | Zusätzliches Argument abhängig vom Funktionstyp |

**Rückgabewert:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Neues Math-Element vom Typ [IMathFunction](../../com.aspose.slides/imathfunction)

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSubscriptElement setSubscript(IMathElement subscript)
```


Erzeugt eine Tiefstellung

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Tiefstellung (tiefer Index rechts) |

**Rückgabewert:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Neues Math-Element vom Typ [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public abstract IMathSubscriptElement setSubscript(String subscript)
```


Erzeugt eine Tiefstellung

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| subscript | java.lang.String | Tiefstellung (tiefer Index rechts) |

**Rückgabewert:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Neues Math-Element vom Typ [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSuperscriptElement setSuperscript(IMathElement superscript)
```


Erzeugt eine Hochstellung

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Hochstellung (oberer Index rechts) |

**Rückgabewert:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Neues Math-Element vom Typ [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public abstract IMathSuperscriptElement setSuperscript(String superscript)
```


Erzeugt eine Hochstellung

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| superscript | java.lang.String | Hochstellung (oberer Index rechts) |

**Rückgabewert:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Neues Math-Element vom Typ [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```


Erzeugt Tief- und Hochstellung auf der rechten Seite

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Tiefstellung (tiefer Index rechts) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Hochstellung (oberer Index rechts) |

**Rückgabewert:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Neues Math-Element vom Typ [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```


Erzeugt Tief- und Hochstellung auf der rechten Seite

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| subscript | java.lang.String | Tiefstellung (tiefer Index rechts) |
| superscript | java.lang.String | Hochstellung (oberer Index rechts) |

**Rückgabewert:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Neues Math-Element vom Typ [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```


Erzeugt Tief- und Hochstellung auf der linken Seite

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Tiefstellung (tiefer Index links) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Hochstellung (oberer Index links) |

**Rückgabewert:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Neues Math-Element vom Typ [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)

### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```


Erzeugt Tief- und Hochstellung auf der linken Seite

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| subscript | java.lang.String | Tiefstellung (tiefer Index links) |
| superscript | java.lang.String | Hochstellung (oberer Index links) |

**Rückgabewert:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Neues Math-Element vom Typ [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)

### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public abstract IMathRadical radical(IMathElement degree)
```


Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Argument des Radikals |

**Rückgabewert:**
[IMathRadical](../../com.aspose.slides/imathradical) - Neue Instanz vom Typ [IMathRadical](../../com.aspose.slides/imathradical)

### radical(String degree) {#radical-java.lang.String-}
```
public abstract IMathRadical radical(String degree)
```


Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| degree | java.lang.String | Argument des Radikals |

**Rückgabewert:**
[IMathRadical](../../com.aspose.slides/imathradical) - Neue Instanz vom Typ [IMathRadical](../../com.aspose.slides/imathradical)

### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setUpperLimit(IMathElement limit)
```


Nimmt obere Grenze

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Grenze |

**Rückgabewert:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Neue Instanz vom Typ [IMathLimit](../../com.aspose.slides/imathlimit)

### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public abstract IMathLimit setUpperLimit(String limit)
```


Nimmt obere Grenze

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| limit | java.lang.String | Grenze |

**Rückgabewert:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Neue Instanz vom Typ [IMathLimit](../../com.aspose.slides/imathlimit)

### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setLowerLimit(IMathElement limit)
```


Nimmt untere Grenze

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Grenze |

**Rückgabewert:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Neue Instanz vom Typ [IMathLimit](../../com.aspose.slides/imathlimit)

### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public abstract IMathLimit setLowerLimit(String limit)
```


Nimmt untere Grenze

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| limit | java.lang.String | Grenze |

**Rückgabewert:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Neue Instanz vom Typ [IMathLimit](../../com.aspose.slides/imathlimit)

### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```


Erstellt einen N-ären Operator

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Der N-äre Operator-Typ |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Untere Grenze |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Obere Grenze |

**Rückgabewert:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Neue Instanz vom Typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```


Erstellt einen N-ären Operator

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Der N-äre Operator-Typ |
| lowerLimit | java.lang.String | Untere Grenze |
| upperLimit | java.lang.String | Obere Grenze |

**Rückgabewert:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Neue Instanz vom Typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### toMathArray() {#toMathArray--}
```
public abstract IMathArray toMathArray()
```


Fügt ein vertikales Array ein

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Rückgabewert:**
[IMathArray](../../com.aspose.slides/imatharray) - Neue Instanz vom Typ [IMathArray](../../com.aspose.slides/imatharray)

### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```


Nimmt das Integral

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| integralType | int | Integraltyp |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Untere Grenze des Integrals |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Obere Grenze des Integrals |
| limitLocations | int | Position der Grenzen |

**Rückgabewert:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Neue Instanz vom Typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```


Nimmt das Integral

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| integralType | int | Integraltyp |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Untere Grenze des Integrals |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Obere Grenze des Integrals |

**Rückgabewert:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Neue Instanz vom Typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType) {#integral-int-}
```
public abstract IMathNaryOperator integral(int integralType)
```


Nimmt das Integral ohne Grenzen

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| integralType | int | Integraltyp |

**Rückgabewert:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Neue Instanz vom Typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```


Nimmt das Integral

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| integralType | int | Integraltyp |
| lowerLimit | java.lang.String | Untere Grenze des Integrals |
| upperLimit | java.lang.String | Obere Grenze des Integrals |
| limitLocations | int | Position der Grenzen |

**Rückgabewert:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Neue Instanz vom Typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```


Nimmt das Integral

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| integralType | int | Integraltyp |
| lowerLimit | java.lang.String | Untere Grenze des Integrals |
| upperLimit | java.lang.String | Obere Grenze des Integrals |

**Rückgabewert:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Neue Instanz vom Typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### accent(char accentCharacter) {#accent-char-}
```
public abstract IMathAccent accent(char accentCharacter)
```


Setzt ein Akzentzeichen (ein Zeichen über diesem Element)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| accentCharacter | char | Akzentzeichen. Der Wert sollte im Bereich (U+0300\\u2013U+036F) oder (U+20D0\\u2013U+20EF) liegen |

**Rückgabewert:**
[IMathAccent](../../com.aspose.slides/imathaccent) - Neue Instanz vom Typ [IMathAccent](../../com.aspose.slides/imathaccent)

### overbar() {#overbar--}
```
public abstract IMathBar overbar()
```


Setzt einen Balken über diesem Element

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**Rückgabewert:**
[IMathBar](../../com.aspose.slides/imathbar) - Neue Instanz vom Typ [IMathBar](../../com.aspose.slides/imathbar)

### underbar() {#underbar--}
```
public abstract IMathBar underbar()
```


Setzt einen Balken unter diesem Element

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Rückgabewert:**
[IMathBar](../../com.aspose.slides/imathbar) - Neue Instanz vom Typ [IMathBar](../../com.aspose.slides/imathbar)

### group() {#group--}
```
public abstract IMathGroupingCharacter group()
```


Platziert dieses Element in einer Gruppe mittels einer unteren geschweiften Klammer

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**Rückgabewert:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Neue Instanz vom Typ [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)

### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public abstract IMathGroupingCharacter group(char character, int position, int verticalJustification)
```


Platziert dieses Element in einer Gruppe mittels eines Gruppierungszeichens wie einer unteren geschweiften Klammer oder einem anderen

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| character | char | Gruppierungszeichen wie UNTERE GESCHWEIFTE KLAMMER (U+23DF) oder ein beliebiges anderes |
| position | int | Position des Gruppierungszeichens |
| verticalJustification | int | Vertikale Ausrichtung des Gruppierungszeichens. Gibt die Ausrichtung des Objekts relativ zur Grundlinie an. Beispiel: Wenn das Gruppierungszeichen über dem Objekt liegt, bedeutet VerticalJustification = Top, dass die Oberkante des Objekts auf der Grundlinie liegt; bei VerticalJustification = Bottom liegt die Unterkante des Objekts auf der Grundlinie. |

**Rückgabewert:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Neue Instanz vom Typ [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)

### toBorderBox() {#toBorderBox--}
```
public abstract IMathBorderBox toBorderBox()
```


Platziert dieses Element in einer Rand-Box

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Rückgabewert:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Rand-Box mit diesem Element innen

### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Platziert dieses Element in einer Rand-Box

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hideTop | boolean | Obere Kante verbergen |
| hideBottom | boolean | Untere Kante verbergen |
| hideLeft | boolean | Linke Kante verbergen |
| hideRight | boolean | Rechte Kante verbergen |
| strikethroughHorizontal | boolean | Horizontale Durchstreichung der Rand-Box |
| strikethroughVertical | boolean | Vertikale Durchstreichung der Rand-Box |
| strikethroughBottomLeftToTopRight | boolean | Diagonale Durchstreichung von unten-links nach oben-rechts |
| strikethroughTopLeftToBottomRight | boolean | Diagonale Durchstreichung von oben-links nach unten-rechts |

**Rückgabewert:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Rand-Box mit diesem Element innen

### toBox() {#toBox--}
```
public abstract IMathBox toBox()
```


Platziert dieses Element in einer nicht-sichtbaren Box (logische Gruppierung), die verwendet wird, um Komponenten einer Gleichung oder andere Instanzen mathematischen Textes zu gruppieren. Ein eingeschlossenes Objekt kann (z. B.) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, als Zeilenumbruch-Punkt fungieren oder so gruppiert werden, dass Zeilenumbrüche innerhalb nicht zulässig sind.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**Rückgabewert:**
[IMathBox](../../com.aspose.slides/imathbox) - Logische Box mit diesem Element innen