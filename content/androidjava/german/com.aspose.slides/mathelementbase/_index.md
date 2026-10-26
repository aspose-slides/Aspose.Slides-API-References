---
title: MathElementBase
second_title: Aspose.Slides für Android über Java API Referenz
description: Basisklasse für IMathElement mit der Implementierung einiger Methoden, die für alle abgeleiteten Klassen gemeinsam sind. Nur für den internen Gebrauch.
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

Basisklasse für IMathElement mit der Implementierung einiger Methoden, die für alle abgeleiteten Klassen gemeinsam sind. Nur für den internen Gebrauch. Abgeleitete Klasse muss IMathElement sein.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | Gibt das Parent_Immediate-Objekt zurück. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Verbindet ein mathematisches Element und bildet einen mathematischen Block |
| [join(String mathText)](#join-java.lang.String-) | Verbindet einen mathematischen Text und bildet einen mathematischen Block |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [divide(String denominator)](#divide-java.lang.String-) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [enclose()](#enclose--) | Umfasst ein Mathelement in Klammern |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Umfasst ein Mathelement in angegebenen Zeichen wie Klammern oder anderen Zeichen als Rahmen |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird |
| [function(String functionArgument)](#function-java.lang.String-) | Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Nimmt die angegebene Funktion und verwendet diese Instanz als Argument |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Nimmt die angegebene Funktion und verwendet diese Instanz als Argument |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Nimmt die angegebene Funktion und verwendet diese Instanz als Argument |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Nimmt die angegebene Funktion, verwendet diese Instanz als Argument und einen angegebenen zusätzlichen Parameter |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Nimmt die angegebene Funktion, verwendet diese Instanz als Argument und einen angegebenen zusätzlichen Parameter |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Erstellt eine Tiefstellung |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Erstellt eine Tiefstellung |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Erstellt eine Hochstellung |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Erstellt eine Hochstellung |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Erstellt Tief- und Hochstellung rechts |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Erstellt Tief- und Hochstellung rechts |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Erstellt Tief- und Hochstellung links |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Erstellt Tief- und Hochstellung links |
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
| [overbar()](#overbar--) | Setzt einen Balken oben auf dieses Element |
| [underbar()](#underbar--) | Setzt einen Balken unten auf dieses Element |
| [group()](#group--) | Platziert dieses Element in einer Gruppe mittels einer unteren geschweiften Klammer |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Platziert dieses Element in einer Gruppe mittels eines Gruppierungszeichens wie einer unteren geschweiften Klammer oder einem anderen |
| [toBorderBox()](#toBorderBox--) | Platziert dieses Element in einem Rand-Box |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Platziert dieses Element in einem Rand-Box |
| [toBox()](#toBox--) | Platziert dieses Element in einer nicht-sichtbaren Box (logische Gruppierung), die verwendet wird, um Komponenten einer Gleichung oder anderer Instanzen von mathematischem Text zu gruppieren. |
| [getChildren()](#getChildren--) | Kinder-Elemente abrufen |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Gibt das Parent_Immediate-Objekt zurück. Nur lesbar IDOMObject.

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
[IMathBlock](../../com.aspose.slides/imathblock) - Ein neuer IMathBlock, der diese Instanz und das angegebene Argument enthält

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
| mathText | java.lang.String | Zu verbindender mathematischer Text |

**Rückgabe:**
[IMathBlock](../../com.aspose.slides/imathblock) - Ein neuer IMathBlock, der diese Instanz und das angegebene Argument enthält

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
[IMathFraction](../../com.aspose.slides/imathfraction) - neuer Bruch

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
[IMathFraction](../../com.aspose.slides/imathfraction) - neuer Bruch

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
[IMathFraction](../../com.aspose.slides/imathfraction) - neuer Bruch

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
[IMathFraction](../../com.aspose.slides/imathfraction) - neuer Bruch

### enclose() {#enclose--}
```
public final IMathDelimiter enclose()
```

Umfasst ein Mathelement in Klammern

--------------------

> ```
> Beispiel:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**Rückgabe:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Das Mathelement vom Typ [IMathDelimiter](../../com.aspose.slides/imathdelimiter) inklusive der Klammern

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Umfasst ein Mathelement in angegebenen Zeichen wie Klammern oder anderen Zeichen als Rahmen

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
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Das Mathelement vom Typ [IMathDelimiter](../../com.aspose.slides/imathdelimiter) inklusive der angegebenen Zeichen als Rahmen

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```

Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird

--------------------

> ```
> Beispiel:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | Das Argument der Funktion |

**Rückgabe:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Neues Mathelement vom Typ [IMathFunction](../../com.aspose.slides/imathfunction)

### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```

Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird

--------------------

> ```
> Beispiel:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionArgument | java.lang.String | Das Argument der Funktion |

**Rückgabe:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Neues Mathelement vom Typ [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```

Nimmt die angegebene Funktion und verwendet diese Instanz als Argument

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
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | Funktionsname |

**Rückgabe:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Neues Mathelement vom Typ [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(String functionName)
```

Nimmt die angegebene Funktion und verwendet diese Instanz als Argument

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
[IMathFunction](../../com.aspose.slides/imathfunction) - Neues Mathelement vom Typ [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public final IMathFunction asArgumentOfFunction(int functionType)
```

Nimmt die angegebene Funktion und verwendet diese Instanz als Argument

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
| functionType | int | Einer der üblichen Funktionsarten mit einem Argument |

**Rückgabe:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Neues Mathelement vom Typ [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

Nimmt die angegebene Funktion und verwendet diese Instanz als Argument und einen angegebenen zusätzlichen Parameter

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
| functionType | int | Einer der üblichen Funktionsarten mit zwei Argumenten: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Zusätzlicher Parameter je nach Funktionsart |

**Rückgabe:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Neues Mathelement vom Typ [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

Nimmt die angegebene Funktion und verwendet diese Instanz als Argument und einen angegebenen zusätzlichen Parameter

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
| functionType | int | Einer der üblichen Funktionsarten mit zwei Argumenten: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | Zusätzlicher Parameter je nach Funktionsart |

**Rückgabe:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Neues Mathelement vom Typ [IMathFunction](../../com.aspose.slides/imathfunction)

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```

Erstellt eine Tiefstellung

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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Tiefstellung (unterer Index rechts) |

**Rückgabe:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Neues Mathelement vom Typ [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```

Erstellt eine Tiefstellung

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
| subscript | java.lang.String | Tiefstellung (unterer Index rechts) |

**Rückgabe:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Neues Mathelement vom Typ [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

Erstellt eine Hochstellung

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

**Rückgabe:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Neues Mathelement vom Typ [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```

Erstellt eine Hochstellung

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
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Neues Mathelement vom Typ [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

Erstellt Tief- und Hochstellung rechts

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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Tiefstellung (unterer Index rechts) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Hochstellung (oberer Index rechts) |

**Rückgabe:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Neues Mathelement vom Typ [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

Erstellt Tief- und Hochstellung rechts

--------------------

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

**Rückgabe:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Neues Mathelement vom Typ [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Erstellt Tief- und Hochstellung links

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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Tiefstellung (unterer Index links) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Hochstellung (oberer Index links) |

**Rückgabe:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Neues Mathelement vom Typ [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)

### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Erstellt Tief- und Hochstellung links

--------------------

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

**Rückgabe:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Neues Mathelement vom Typ [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)

### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an.

--------------------

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

**Rückgabe:**
[IMathRadical](../../com.aspose.slides/imathradical) - Neue Instanz vom Typ [IMathRadical](../../com.aspose.slides/imathradical)

### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
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

**Rückgabe:**
[IMathRadical](../../com.aspose.slides/imathradical) - Neue Instanz vom Typ [IMathRadical](../../com.aspose.slides/imathradical)

### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```

Nimmt obere Grenze

--------------------

> ```
public final IMathLimit setUpperLimit(IMathElement limit)

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

**Rückgabe:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Neue Instanz vom Typ [IMathLimit](../../com.aspose.slides/imathlimit)

### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```

Nimmt obere Grenze

--------------------

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

**Rückgabe:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Neue Instanz vom Typ [IMathLimit](../../com.aspose.slides/imathlimit)

### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

Nimmt untere Grenze

--------------------

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

**Rückgabe:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Neue Instanz vom Typ [IMathLimit](../../com.aspose.slides/imathlimit)

### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

Nimmt untere Grenze

--------------------

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

**Rückgabe:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Neue Instanz vom Typ [IMathLimit](../../com.aspose.slides/imathlimit)

### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

Erstellt einen N-ären Operator

--------------------

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
| type | int | Der Typ des N-ären Operators |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Untere Grenze |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Obere Grenze |

**Rückgabe:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Neue Instanz vom Typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
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
| type | int | Der Typ des N-ären Operators |
| lowerLimit | java.lang.String | Untere Grenze |
| upperLimit | java.lang.String | Obere Grenze |

**Rückgabe:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Neue Instanz vom Typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Fügt ein vertikales Array ein

--------------------

> ```
> Beispiel:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Rückgabe:**
[IMathArray](../../com.aspose.slides/imatharray) - Neue Instanz vom Typ [IMathArray](../../com.aspose.slides/imatharray)

### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

Nimmt das Integral

--------------------

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

**Rückgabe:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Neue Instanz vom Typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
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

**Rückgabe:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Neue Instanz vom Typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

Nimmt das Integral ohne Grenzen

--------------------

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

**Rückgabe:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Neue Instanz vom Typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
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

**Rückgabe:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Neue Instanz vom Typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
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

**Rückgabe:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Neue Instanz vom Typ [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

Setzt ein Akzentzeichen (ein Zeichen über diesem Element)

--------------------

> ```
> Beispiel:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| accentCharacter | char | Akzentzeichen. Der Wert sollte im Bereich (U+0300\\u2013U+036F) oder (U+20D0\\u2013U+20EF) liegen |

**Rückgabe:**
[IMathAccent](../../com.aspose.slides/imathaccent) - Neue Instanz vom Typ [IMathAccent](../../com.aspose.slides/imathaccent)

### overbar() {#overbar--}
```
public final IMathBar overbar()
```

Setzt einen Balken oben auf dieses Element

--------------------

> ```
> Beispiel:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```


**Rückgabe:**
[IMathBar](../../com.aspose.slides/imathbar) - Neue Instanz vom Typ [IMathBar](../../com.aspose.slides/imathbar)

### underbar() {#underbar--}
```
public final IMathBar underbar()
```

Setzt einen Balken unten auf dieses Element

--------------------

> ```
> Beispiel:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Rückgabe:**
[IMathBar](../../com.aspose.slides/imathbar) - Neue Instanz vom Typ [IMathBar](../../com.aspose.slides/imathbar)

### group() {#group--}
```
public final IMathGroupingCharacter group()
```

Platziert dieses Element in einer Gruppe mittels einer unteren geschweiften Klammer

--------------------

> ```
> Beispiel:
>  
```


**Rückgabe:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Neue Instanz vom Typ [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)

### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Platziert dieses Element in einer Gruppe mittels eines Gruppierungszeichens wie einer unteren geschweiften Klammer oder einem anderen

--------------------

> ```
> Beispiel:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| character | char | Gruppierungszeichen wie UNTERE GESCHWEIFTE KLAMMER (U+23DF) oder ein anderes |
| position | int | Position des Gruppierungszeichens |
| verticalJustification | int | Vertikale Ausrichtung des Gruppierungszeichens. Gibt die Ausrichtung des Objekts relativ zur Grundlinie an. Beispiel: Wenn das Gruppierungszeichen über dem Objekt liegt, bedeutet VerticalJustification = Top, dass die Oberkante des Objekts auf der Grundlinie liegt; bei VerticalJustification = Bottom liegt die Unterkante des Objekts auf der Grundlinie. |

**Rückgabe:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Neue Instanz vom Typ [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)

### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

Platziert dieses Element in einem Rand-Box

--------------------

> ```
> Beispiel:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Rückgabe:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Rand-Box mit diesem Element innen

### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Platziert dieses Element in einem Rand-Box

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
| strikethroughHorizontal | boolean | Horizontale Durchstreichung des Rand-Box |
| strikethroughVertical | boolean | Vertikale Durchstreichung des Rand-Box |
| strikethroughBottomLeftToTopRight | boolean | Durchstreichung von unten-links nach oben-rechts |
| strikethroughTopLeftToBottomRight | boolean | Durchstreichung von oben-links nach unten-rechts |

**Rückgabe:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Rand-Box mit diesem Element innen

### toBox() {#toBox--}
```
public final IMathBox toBox()
```

Platziert dieses Element in einer nicht-sichtbaren Box (logische Gruppierung), die verwendet wird, um Komponenten einer Gleichung oder anderer Instanzen von mathematischem Text zu gruppieren. Ein eingekapseltes Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, als Zeilenumbruch-Punkt fungieren oder so gruppiert werden, dass Zeilenumbrüche innerhalb nicht zulässig sind.

--------------------

> ```
> Beispiel:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**Rückgabe:**
[IMathBox](../../com.aspose.slides/imathbox) - Logische Box mit diesem Element innen

### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

Kinder-Elemente abrufen

**Rückgabe:**
com.aspose.slides.IMathElement[] - Array von [IMathElement](../../com.aspose.slides/imathelement)