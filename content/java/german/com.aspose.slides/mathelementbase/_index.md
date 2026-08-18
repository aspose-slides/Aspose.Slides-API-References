---
title: MathElementBase
second_title: Aspose.Slides für Java API-Referenz
description: Basisklasse für IMathElement mit der Implementierung einiger Methoden, die allen abgeleiteten Klassen gemeinsam sind. Nur für den internen Gebrauch.
type: docs
url: /de/com.aspose.slides/mathelementbase/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

Basisklasse für IMathElement mit der Implementierung einiger Methoden, die für alle abgeleiteten Klassen gemeint sind. Nur für den internen Gebrauch. Abgeleitete Klasse muss IMathElement sein.
## Methoden

| Method | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | Gibt das Parent_Immediate-Objekt zurück. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Verbindet ein mathematisches Element und bildet einen mathematischen Block |
| [join(String mathText)](#join-java.lang.String-) | Verbindet einen mathematischen Text und bildet einen mathematischen Block |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [divide(String denominator)](#divide-java.lang.String-) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [enclose()](#enclose--) | Umschließt ein mathematisches Element in Klammern |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Umschließt ein mathematisches Element in angegebenen Zeichen, z. B. Klammern oder anderen Rahmenzeichen |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Erzeugt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird |
| [function(String functionArgument)](#function-java.lang.String-) | Erzeugt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Verwendet die angegebene Funktion mit dieser Instanz als Argument |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Verwendet die angegebene Funktion mit dieser Instanz als Argument |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Verwendet die angegebene Funktion mit dieser Instanz als Argument |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Verwendet die angegebene Funktion mit dieser Instanz als Argument und einem zusätzlichen Argument |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Verwendet die angegebene Funktion mit dieser Instanz als Argument und einem zusätzlichen Argument |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Erstellt einen Tiefstellung |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Erstellt einen Tiefstellung |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Erstellt einen Hochstellung |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Erstellt einen Hochstellung |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Erstellt Tief- und Hochstellung rechts vom Element |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Erstellt Tief- und Hochstellung rechts vom Element |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Erstellt Tief- und Hochstellung links vom Element |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Erstellt Tief- und Hochstellung links vom Element |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an |
| [radical(String degree)](#radical-java.lang.String-) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Nimmt obere Grenze |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Nimmt obere Grenze |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Nimmt untere Grenze |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Nimmt untere Grenze |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Erstellt einen N-stelligen Operator |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | Erstellt einen N-stelligen Operator |
| [toMathArray()](#toMathArray--) | Setzt in ein vertikales Array |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Nimmt das Integral |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Nimmt das Integral |
| [integral(int integralType)](#integral-int-) | Nimmt das Integral ohne Grenzen |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | Nimmt das Integral |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | Nimmt das Integral |
| [accent(char accentCharacter)](#accent-char-) | Setzt ein Akzentzeichen (ein Zeichen über diesem Element) |
| [overbar()](#overbar--) | Setzt einen Balken über diesem Element |
| [underbar()](#underbar--) | Setzt einen Balken unter diesem Element |
| [group()](#group--) | Platziert dieses Element in einer Gruppe mit einer geschweiften Klammer unten |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Platziert dieses Element in einer Gruppe mit einem Gruppierungszeichen, z. B. einer geschweiften Klammer unten oder einem anderen |
| [toBorderBox()](#toBorderBox--) | Platziert dieses Element in einem Rahmen-Box |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Platziert dieses Element in einem Rahmen-Box |
| [toBox()](#toBox--) | Platziert dieses Element in einer nicht-visuellen Box (logische Gruppierung), die verwendet wird, um Komponenten einer Gleichung oder eines anderen mathematischen Textes zu gruppieren |
| [getChildren()](#getChildren--) | Gibt Kind-Elemente zurück |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```


Gibt das Parent_Immediate-Objekt zurück. Schreibgeschützt IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject
### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```


Verbindet ein mathematisches Element und bildet einen mathematischen Block

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

**Rückgabe:**
[IMathBlock](../../com.aspose.slides/imathblock) – Ein neues IMathBlock, das diese Instanz und das angegebene Argument enthält
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```


Verbindet einen mathematischen Text und bildet einen mathematischen Block

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
| mathText | java.lang.String | Der zu verbindende mathematische Text |

**Rückgabe:**
[IMathBlock](../../com.aspose.slides/imathblock) – Ein neues IMathBlock, das diese Instanz und das angegebene Argument enthält
### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public final IMathFraction divide(IMathElement denominator)
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

**Rückgabe:**
[IMathFraction](../../com.aspose.slides/imathfraction) – neuer Bruch
### divide(String denominator) {#divide-java.lang.String-}
```
public final IMathFraction divide(String denominator)
```


Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| denominator | java.lang.String | Nenner |

**Rückgabe:**
[IMathFraction](../../com.aspose.slides/imathfraction) – neuer Bruch
### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction divide(IMathElement denominator, int fractionType)
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

**Rückgabe:**
[IMathFraction](../../com.aspose.slides/imathfraction) – neuer Bruch
### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public final IMathFraction divide(String denominator, int fractionType)
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

**Rückgabe:**
[IMathFraction](../../com.aspose.slides/imathfraction) – neuer Bruch
### enclose() {#enclose--}
```
public final IMathDelimiter enclose()
```


Umschließt ein mathematisches Element in Klammern

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```


**Rückgabe:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) – Das mathematische Element vom Typ [IMathDelimiter](../../com.aspose.slides/imathdelimiter), das die Klammern enthält
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```


Umschließt ein mathematisches Element in angegebenen Zeichen, z. B. Klammern oder anderen Rahmenzeichen

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
| beginningCharacter | char | Anfangszeichen (gewöhnlich linke Klammer) |
| endingCharacter | char | Endzeichen (gewöhnlich rechte Klammer) |

**Rückgabe:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) – Das mathematische Element vom Typ [IMathDelimiter](../../com.aspose.slides/imathdelimiter), das die angegebenen Zeichen als Rahmen enthält
### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```


Erzeugt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird

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

**Rückgabe:**
[IMathFunction](../../com.aspose.slides/imathfunction) – Neues mathematisches Element vom Typ [IMathFunction](../../com.aspose.slides/imathfunction)
### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```


Erzeugt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird

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

**Rückgabe:**
[IMathFunction](../../com.aspose.slides/imathfunction) – Neues mathematisches Element vom Typ [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```


Verwendet die angegebene Funktion mit dieser Instanz als Argument

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

**Rückgabe:**
[IMathFunction](../../com.aspose.slides/imathfunction) – Neues mathematisches Element vom Typ [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(String functionName)
```


Verwendet die angegebene Funktion mit dieser Instanz als Argument

--------------------

> ```
> Beispiel:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionName | java.lang.String | Funktionsname |

**Rückgabe:**
[IMathFunction](../../com.aspose.slides/imathfunction) – Neues mathematisches Element vom Typ [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public final IMathFunction asArgumentOfFunction(int functionType)
```


Verwendet die angegebene Funktion mit dieser Instanz als Argument

--------------------

> ```
> Beispiel:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionType | int | Einer der üblichen Funktionstypen mit einem Argument |

**Rückgabe:**
[IMathFunction](../../com.aspose.slides/imathfunction) – Neues mathematisches Element vom Typ [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```


Verwendet die angegebene Funktion mit dieser Instanz als Argument und einem zusätzlichen Argument

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
| functionType | int | Einer der üblichen Funktionstypen mit zwei Argumenten: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Zusätzliches Argument, abhängig vom Funktionstyp |

**Rückgabe:**
[IMathFunction](../../com.aspose.slides/imathfunction) – Neues mathematisches Element vom Typ [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```


Verwendet die angegebene Funktion mit dieser Instanz als Argument und einem zusätzlichen Argument

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
| functionType | int | Einer der üblichen Funktionstypen mit zwei Argumenten: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | Zusätzliches Argument, abhängig vom Funktionstyp |

**Rückgabe:**
[IMathFunction](../../com.aspose.slides/imathfunction) – Neues mathematisches Element vom Typ [IMathFunction](../../com.aspose.slides/imathfunction)
### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```


Erstellt einen Tiefstellung

--------------------

> ```
> Beispiel:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Tiefstellung (niedriger Index rechts) |

**Rückgabe:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) – Neues mathematisches Element vom Typ [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```


Erstellt einen Tiefstellung

--------------------

> ```
> Beispiel:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| subscript | java.lang.String | Tiefstellung (niedriger Index rechts) |

**Rückgabe:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) – Neues mathematisches Element vom Typ [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```


Erstellt einen Hochstellung

--------------------

> ```
> Beispiel:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Hochstellung (oberer Index rechts) |

**Rückgabe:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) – Neues mathematisches Element vom Typ [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```


Erstellt einen Hochstellung

--------------------

> ```
> Beispiel:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| superscript | java.lang.String | Hochstellung (oberer Index rechts) |

**Rückgabe:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) – Neues mathematisches Element vom Typ [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```


Erstellt Tief- und Hochstellung rechts vom Element

--------------------

> ```
> Beispiel:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Tiefstellung (niedriger Index rechts) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Hochstellung (oberer Index rechts) |

**Rückgabe:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) – Neues mathematisches Element vom Typ [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```


Erstellt Tief- und Hochstellung rechts vom Element
> ```
> Beispiel:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| subscript | java.lang.String | Tiefstellung (unterer Index rechts) |
| superscript | java.lang.String | Hochstellung (oberer Index rechts) |

**Rückgabewert:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Neues mathematisches Element vom Typ [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Erstellt Subscript und Superscript auf der linken Seite

---

> ```
> Beispiel:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Tiefstellung (unterer Index links) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Hochstellung (oberer Index links) |

**Rückgabewert:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Neues mathematisches Element vom Typ [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Erstellt Subscript und Superscript auf der linken Seite

---

> ```
> Beispiel:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| subscript | java.lang.String | Tiefstellung (unterer Index links) |
| superscript | java.lang.String | Hochstellung (oberer Index links) |

**Rückgabewert:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Neues mathematisches Element vom Typ [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

Legt die mathematische Wurzel des angegebenen Grades des angegebenen Arguments fest.

---

> ```
> Beispiel:
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
public final IMathRadical radical(String degree)
```

Legt die mathematische Wurzel des angegebenen Grades des angegebenen Arguments fest.

---

> ```
> Beispiel:
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
public final IMathLimit setUpperLimit(IMathElement limit)
```

Nimmt obere Grenze

---

> ```
> Beispiel:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Grenze |

**Rückgabewert:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Neue Instanz vom Typ [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```

Nimmt obere Grenze

---

> ```
> Beispiel:
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
public final IMathLimit setLowerLimit(IMathElement limit)
```

Nimmt untere Grenze

---

> ```
> Beispiel:
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
public final IMathLimit setLowerLimit(String limit)
```

Nimmt untere Grenze

---

> ```
> Beispiel:
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
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

Erzeugt einen N-ary-Operator

---

> ```
> Beispiel:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Der N-ary-Operator-Typ |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Untere Grenze |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Obere Grenze |

**Rückgabewert:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Neue Instanz vom Typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

Erzeugt einen N-ary-Operator

---

> ```
> Beispiel:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Der N-ary-Operator-Typ |
| lowerLimit | java.lang.String | Untere Grenze |
| upperLimit | java.lang.String | Obere Grenze |

**Rückgabewert:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Neue Instanz vom Typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Platziert in einem vertikalen Array

---

> ```
> Beispiel:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Rückgabewert:**
[IMathArray](../../com.aspose.slides/imatharray) - Neue Instanz vom Typ [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

Nimmt das Integral

---

> ```
> Beispiel:
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
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

Nimmt das Integral

---

> ```
> Beispiel:
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
public final IMathNaryOperator integral(int integralType)
```

Nimmt das Integral ohne Grenzen

---

> ```
> Beispiel:
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
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

Nimmt das Integral

---

> ```
> Beispiel:
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
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

Nimmt das Integral

---

> ```
> Beispiel:
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
public final IMathAccent accent(char accentCharacter)
```

Setzt ein Akzentzeichen (ein Zeichen über diesem Element)

---

> ```
> Beispiel:
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
public final IMathBar overbar()
```

Setzt einen Balken über diesem Element

---

> ```
> Beispiel:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```


**Rückgabewert:**
[IMathBar](../../com.aspose.slides/imathbar) - Neue Instanz vom Typ [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public final IMathBar underbar()
```

Setzt einen Balken unter diesem Element

---

> ```
> Beispiel:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Rückgabewert:**
[IMathBar](../../com.aspose.slides/imathbar) - Neue Instanz vom Typ [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public final IMathGroupingCharacter group()
```

Platziert dieses Element in einer Gruppe mit einer unteren geschweiften Klammer

---

> ```
> Beispiel:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**Rückgabewert:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Neue Instanz vom Typ [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Platziert dieses Element in einer Gruppe mittels eines Gruppierungszeichens wie einer unteren geschweiften Klammer oder einem anderen Zeichen

---

> ```
> Beispiel:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| character | char | Gruppierungszeichen, z. B. UNTERE GESCHWEIFTE KLAMMER (U+23DF) oder ein anderes |
| position | int | Position des Gruppierungszeichens |
| verticalJustification | int | Vertikale Ausrichtung des Gruppierungszeichens. Gibt die Ausrichtung des Objekts relativ zur Grundlinie an. Beispiel: Wenn das Gruppierungszeichen über dem Objekt liegt, bedeutet VerticalJustification = Top, dass die Oberseite des Objekts auf der Grundlinie liegt; bei VerticalJustification = Bottom liegt die Unterseite des Objekts auf der Grundlinie. |

**Rückgabewert:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Neue Instanz vom Typ [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

Platziert dieses Element in einer Border-Box

---

> ```
> Beispiel:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Rückgabewert:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-Box mit diesem Element innen
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Platziert dieses Element in einer Border-Box

---

> ```
> Beispiel:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hideTop | boolean | Obere Kante ausblenden |
| hideBottom | boolean | Untere Kante ausblenden |
| hideLeft | boolean | Linke Kante ausblenden |
| hideRight | boolean | Rechte Kante ausblenden |
| strikethroughHorizontal | boolean | Horizontaler Durchstreichen der Border-Box |
| strikethroughVertical | boolean | Vertikaler Durchstreichen der Border-Box |
| strikethroughBottomLeftToTopRight | boolean | Durchstreichen von unten-links nach oben-rechts |
| strikethroughTopLeftToBottomRight | boolean | Durchstreichen von oben-links nach unten-rechts |

**Rückgabewert:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-Box mit diesem Element innen
### toBox() {#toBox--}
```
public final IMathBox toBox()
```

Platziert dieses Element in einer nicht-sichtbaren Box (logische Gruppierung), die verwendet wird, um Komponenten einer Gleichung oder eines anderen mathematischen Textes zu gruppieren. Ein in einer Box befindliches Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, als Zeilenumbruch-Punkt fungieren oder so gruppiert sein, dass Zeilenumbrüche innerhalb verhindert werden.

---

> ```
> Beispiel:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**Rückgabewert:**
[IMathBox](../../com.aspose.slides/imathbox) - Logische Box mit diesem Element innen
### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

Kindelemente abrufen

**Rückgabewert:**
com.aspose.slides.IMathElement[] - Array von [IMathElement](../../com.aspose.slides/imathelement)