---
title: IMathElement
second_title: Aspose.Slides for Java API-referenciája
description: Az összes matematikai elem alapinterfésze: tört, matematikai szöveg, függvény, több elemből álló kifejezés stb.
type: docs
url: /hu/com.aspose.slides/imathelement/
---```
public interface IMathElement
```

Az összes matematikai elem alapinterfésze: tört, matematikai szöveg, függvény, több elemből álló kifejezés stb.

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
> ```
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getChildren()](#getChildren--) | Lekéri a gyermekelemeket |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Összekapcsol egy matematikai elemet, és matematikai blokkot hoz létre |
| [join(String mathText)](#join-java.lang.String-) | Összekapcsol egy matematikai szöveget, és matematikai blokkot hoz létre |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Létrehozza a törtet ezzel a számlálóval és a megadott nevezővel |
| [divide(String denominator)](#divide-java.lang.String-) | Létrehozza a törtet ezzel a számlálóval és a megadott nevezővel |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Létrehozza a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Létrehozza a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [enclose()](#enclose--) | Matematikai elemet zárójelbe tesz |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | A megadott karakterekkel keretezi ezt az elemet, például zárójelekkel vagy egyéb karakterekkel |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Függvényt vesz egy argumentummal, az aktuális példányt használva függvénynévként |
| [function(String functionArgument)](#function-java.lang.String-) | Függvényt vesz egy argumentummal, az aktuális példányt használva függvénynévként |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Megadott függvényt vesz, az aktuális példányt használva argumentumként |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Megadott függvényt vesz, az aktuális példányt használva argumentumként |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Megadott függvényt vesz, az aktuális példányt használva argumentumként |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Megadott függvényt vesz, az aktuális példányt használva argumentumként, valamint megadott további argumentummal |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Megadott függvényt vesz, az aktuális példányt használva argumentumként, valamint megadott további argumentummal |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Alsó indexet hoz létre |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Alsó indexet hoz létre |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Felső indexet hoz létre |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Felső indexet hoz létre |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Alsó és felső indexet hoz létre jobbra |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Alsó és felső indexet hoz létre jobbra |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Alsó és felső indexet hoz létre balra |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Alsó és felső indexet hoz létre balra |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Megadja a megadott fokú matematikai gyököt a meghatározott argumentumból. |
| [radical(String degree)](#radical-java.lang.String-) | Megadja a megadott fokú matematikai gyököt a meghatározott argumentumból. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Felső határt vesz |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Felső határt vesz |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Alsó határt vesz |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Alsó határt vesz |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | N-értékű operátort hoz létre |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | N-értékű operátort hoz létre |
| [toMathArray()](#toMathArray--) | Függőleges tömbbe helyezi |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Integrált vesz |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Integrált vesz |
| [integral(int integralType)](#integral-int-) | Integrált vesz határok nélkül |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | Integrált vesz |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | Integrált vesz |
| [accent(char accentCharacter)](#accent-char-) | Akcentusjelet állít be (karakter az elem tetején) |
| [overbar()](#overbar--) | Vonalat helyez az elem tetejére |
| [underbar()](#underbar--) | Vonalat helyez az elem aljára |
| [group()](#group--) | Az elemet csoportba helyezi egy alsó kapcsos záróval |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Az elemet csoportba helyezi egy csoportosító karakterrel, például alsó kapcsos záróval vagy más |
| [toBorderBox()](#toBorderBox--) | Az elemet keretdobozba helyezi |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Az elemet keretdobozba helyezi |
| [toBox()](#toBox--) | Az elemet egy nem látható dobozba (logikai csoportosítás) helyezi, amely egyenlet komponenseinek vagy más matematikai szöveg példányainak csoportosítására szolgál. |

### getChildren() {#getChildren--}
```
public abstract IMathElement[] getChildren()
```

Lekéri a gyermekelemeket

**Visszatérési érték:**
com.aspose.slides.IMathElement[]

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock join(IMathElement mathElement)
```

Összekapcsol egy matematikai elemet, és matematikai blokkot hoz létre

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Az összekapcsolandó elem |

**Visszatérési érték:**
[IMathBlock](../../com.aspose.slides/imathblock) - Egy új IMathBlock, amely tartalmazza ezt a példányt és a megadott argumentumot

### join(String mathText) {#join-java.lang.String-}
```
public abstract IMathBlock join(String mathText)
```

Összekapcsol egy matematikai szöveget, és matematikai blokkot hoz létre

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathText | java.lang.String | Az összekapcsolandó matematikai szöveg |

**Visszatérési érték:**
[IMathBlock](../../com.aspose.slides/imathblock) - Egy új IMathBlock, amely tartalmazza ezt a példányt és a megadott argumentumot

### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction divide(IMathElement denominator)
```

Létrehozza a törtet ezzel a számlálóval és a megadott nevezővel

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Nevező |

**Visszatérési érték:**
[IMathFraction](../../com.aspose.slides/imathfraction) - új tört

### divide(String denominator) {#divide-java.lang.String-}
```
public abstract IMathFraction divide(String denominator)
```

Létrehozza a törtet ezzel a számlálóval és a megadott nevezővel

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| denominator | java.lang.String | Nevező |

**Visszatérési érték:**
[IMathFraction](../../com.aspose.slides/imathfraction) - új tört

### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction divide(IMathElement denominator, int fractionType)
```

Létrehozza a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Nevező |
| fractionType | int | Törttípus: Bar, NoBar, Skewed, Linear |

**Visszatérési érték:**
[IMathFraction](../../com.aspose.slides/imathfraction) - új tört

### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public abstract IMathFraction divide(String denominator, int fractionType)
```

Létrehozza a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| denominator | java.lang.String | Nevező |
| fractionType | int | Törttípus: Bar, NoBar, Skewed, Linear |

**Visszatérési érték:**
[IMathFraction](../../com.aspose.slides/imathfraction) - új tört

### enclose() {#enclose--}
```
public abstract IMathDelimiter enclose()
```

Matematikai elemet zárójelbe tesz

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**Visszatérési érték:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - A [IMathDelimiter](../../com.aspose.slides/imathdelimiter) típusú matematikai elem, amely tartalmazza a zárójeleket

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

A megadott karakterekkel keretezi ezt az elemet, például zárójelekkel vagy egyéb karakterekkel

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| beginningCharacter | char | Kezdő karakter (általában bal zárójel) |
| endingCharacter | char | Záró karakter (általában jobb zárójel) |

**Visszatérési érték:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - A [IMathDelimiter](../../com.aspose.slides/imathdelimiter) típusú matematikai elem, amely tartalmazza a megadott karaktereket keretezésként

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction function(IMathElement functionArgument)
```

Függvényt vesz egy argumentummal, az aktuális példányt használva függvénynévként

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | A függvény argumentuma |

**Visszatérési érték:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Új [IMathFunction](../../com.aspose.slides/imathfunction) típusú matematikai elem

### function(String functionArgument) {#function-java.lang.String-}
```
public abstract IMathFunction function(String functionArgument)
```

Függvényt vesz egy argumentummal, az aktuális példányt használva függvénynévként

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionArgument | java.lang.String | A függvény argumentuma |

**Visszatérési érték:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Új [IMathFunction](../../com.aspose.slides/imathfunction) típusú matematikai elem

### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(IMathElement functionName)
```

Megadott függvényt vesz, az aktuális példányt használva argumentumként

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | Függvény neve |

**Visszatérési érték:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Új [IMathFunction](../../com.aspose.slides/imathfunction) típusú matematikai elem

### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(String functionName)
```

Megadott függvényt vesz, az aktuális példányt használva argumentumként

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionName | java.lang.String | Függvény neve |

**Visszatérési érték:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Új [IMathFunction](../../com.aspose.slides/imathfunction) típusú matematikai elem

### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType)
```

Megadott függvényt vesz, az aktuális példányt használva argumentumként

--------------------

> ```
> Példa:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionType | int | Egy közös egyargumentumos függvény típusa |

**Visszatérési érték:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Új [IMathFunction](../../com.aspose.slides/imathfunction) típusú matematikai elem

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

Megadott függvényt vesz, az aktuális példányt használva argumentumként és megadott további argumentummal

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Visszaadja a 'x' logaritmusát az '5' alapra
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionType | int | Kétargumentumos közös függvény típusa: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | További argumentum a függvény típusától függően |

**Visszatérési érték:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Új [IMathFunction](../../com.aspose.slides/imathfunction) típusú matematikai elem

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

Megadott függvényt vesz, az aktuális példányt használva argumentumként és megadott további argumentummal

--------------------

> ```
> Példa:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Visszaadja a 'x' logaritmusát az '5' alapra
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionType | int | Kétargumentumos közös függvény típusa: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | További argumentum a függvény típusától függően |

**Visszatérési érték:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Új [IMathFunction](../../com.aspose.slides/imathfunction) típusú matematikai elem

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSubscriptElement setSubscript(IMathElement subscript)
```

Alsó indexet hoz létre

--------------------

> ```
> Példa:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Alsó index (alsó szám a jobboldalon) |

**Visszatérési érték:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Új [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) típusú matematikai elem

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public abstract IMathSubscriptElement setSubscript(String subscript)
```

Alsó indexet hoz létre

--------------------

> ```
> Példa:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subscript | java.lang.String | Alsó index (alsó szám a jobboldalon) |

**Visszatérési érték:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Új [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) típusú matematikai elem

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

Felső indexet hoz létre

--------------------

> ```
> Példa:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Felső index (felső szám a jobboldalon) |

**Visszatérési érték:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Új [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) típusú matematikai elem

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public abstract IMathSuperscriptElement setSuperscript(String superscript)
```

Felső indexet hoz létre

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| superscript | java.lang.String | Felső index (felső szám a jobboldalon) |

**Visszatérési érték:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Új [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) típusú matematikai elem

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

Alsó és felső indexet hoz létre jobbra

--------------------

> ```
> Példa:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Alsó index (alsó szám a jobboldalon) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Felső index (felső szám a jobboldalon) |

**Visszatérési érték:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Új [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) típusú matematikai elem

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```
Létrehoz alsó- és felső indexet a jobb oldalon
--------------------

> ```
> Példa:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subscript | java.lang.String | Alsó index (alsó index a jobb oldalon) |
| superscript | java.lang.String | Felső index (felső index a jobb oldalon) |

**Visszatérési érték:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - New math element of type [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Létrehoz alsó- és felső indexet a bal oldalon
--------------------

> ```
> Példa:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Alsó index (alsó index a bal oldalon) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Felső index (felső index a bal oldalon) |

**Visszatérési érték:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - New math element of type [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Létrehoz alsó- és felső indexet a bal oldalon
--------------------

> ```
> Példa:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subscript | java.lang.String | Alsó index (alsó index a bal oldalon) |
| superscript | java.lang.String | Felső index (felső index a bal oldalon) |

**Visszatérési érték:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - New math element of type [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public abstract IMathRadical radical(IMathElement degree)
```

Megadja a megadott fokú matematikai gyököt a megadott argumentumból.
--------------------

> ```
> Példa:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Radikálus argumentuma |

**Visszatérési érték:**
[IMathRadical](../../com.aspose.slides/imathradical) - New instance of type [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public abstract IMathRadical radical(String degree)
```

Megadja a megadott fokú matematikai gyököt a megadott argumentumból.
--------------------

> ```
> Példa:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| degree | java.lang.String | Radikálus argumentuma |

**Visszatérési érték:**
[IMathRadical](../../com.aspose.slides/imathradical) - New instance of type [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setUpperLimit(IMathElement limit)
```

Felső határ
--------------------

> ```
> Példa:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Visszatérési érték:**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public abstract IMathLimit setUpperLimit(String limit)
```

Felső határ
--------------------

> ```
> Példa:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Visszatérési érték:**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setLowerLimit(IMathElement limit)
```

Alsó határ
--------------------

> ```
> Példa:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Visszatérési érték:**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public abstract IMathLimit setLowerLimit(String limit)
```

Alsó határ
--------------------

> ```
> Példa:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Visszatérési érték:**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

Létrehoz N-operandusú operátort
--------------------

> ```
> Példa:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | Az N-operandusú operátor típusa |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Az alsó határ |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Az felső határ |

**Visszatérési érték:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

Létrehoz N-operandusú operátort
--------------------

> ```
> Példa:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | Az N-operandusú operátor típusa |
| lowerLimit | java.lang.String | Az alsó határ |
| upperLimit | java.lang.String | Az felső határ |

**Visszatérési érték:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public abstract IMathArray toMathArray()
```

Függőleges tömbbe helyezi
--------------------

> ```
> Példa:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Visszatérési érték:**
[IMathArray](../../com.aspose.slides/imatharray) - New instance of type [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

Integrált vesz fel
--------------------

> ```
> Példa:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| integralType | int | Integrál típusa |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Integrál alsó határa |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Integrál felső határa |
| limitLocations | int | Határhelyek elhelyezkedése |

**Visszatérési érték:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

Integrált vesz fel
--------------------

> ```
> Példa:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| integralType | int | Integrál típusa |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Integrál alsó határa |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Integrál felső határa |

**Visszatérési érték:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public abstract IMathNaryOperator integral(int integralType)
```

Integrált vesz fel határok nélkül
--------------------

> ```
> Példa:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| integralType | int | Integrál típusa |

**Visszatérési érték:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

Integrált vesz fel
--------------------

> ```
> Példa:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| integralType | int | Integrál típusa |
| lowerLimit | java.lang.String | Integrál alsó határa |
| upperLimit | java.lang.String | Integrál felső határa |
| limitLocations | int | Határhelyek elhelyezkedése |

**Visszatérési érték:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

Integrált vesz fel
--------------------

> ```
> Példa:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| integralType | int | Integrál típusa |
| lowerLimit | java.lang.String | Integrál alsó határa |
| upperLimit | java.lang.String | Integrál felső határa |

**Visszatérési érték:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public abstract IMathAccent accent(char accentCharacter)
```

Beállít egy akcentus jelet (karakter az elem tetején)
--------------------

> ```
> Példa:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| accentCharacter | char | Akcentus karakter. Az értéknek a (U+0300\\u2013U+036F) vagy (U+20D0\\u2013U+20EF) tartományon belül kell lennie |

**Visszatérési érték:**
[IMathAccent](../../com.aspose.slides/imathaccent) - New instance of type [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public abstract IMathBar overbar()
```

Az elem tetejére vonalat helyez
--------------------

> ```
> Példa:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**Visszatérési érték:**
[IMathBar](../../com.aspose.slides/imathbar) - New instance of type [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public abstract IMathBar underbar()
```

Az elem aljára vonalat helyez
--------------------

> ```
> Példa:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Visszatérési érték:**
[IMathBar](../../com.aspose.slides/imathbar) - New instance of type [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public abstract IMathGroupingCharacter group()
```

Az elemet egy csoportba helyezi alsó kapcsos zárójel használatával
--------------------

> ```
> Példa:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**Visszatérési érték:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - New instance of type [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public abstract IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Az elemet egy csoportba helyezi egy csoportosító karakter, például alsó kapcsos zárójel vagy más karakter használatával
--------------------

> ```
> Példa:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| character | char | Csoportosító karakter, például ALSÓ KAPCSOS ZÁRÓJEL (U+23DF) vagy bármely más |
| position | int | A csoportosító karakter pozíciója |
| verticalJustification | int | A csoportosító karakter függőleges igazítása. Megadja az objektum igazítását az alapsoron. Például ha a csoportosító karakter az objektum felett van, a Top függőleges igazítás azt jelenti, hogy az objektum teteje az alapsoron helyezkedik el; ha a Bottom értékre van állítva, az objektum alja az alapsoron van |

**Visszatérési érték:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - New instance of type [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public abstract IMathBorderBox toBorderBox()
```

Az elemet egy keretdobozba helyezi
--------------------

> ```
> Példa:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Visszatérési érték:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box with this element placed inside
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Az elemet egy keretdobozba helyezi
--------------------

> ```
> Példa:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hideTop | boolean | Felső él elrejtése |
| hideBottom | boolean | Alsó él elrejtése |
| hideLeft | boolean | Bal él elrejtése |
| hideRight | boolean | jobb él elrejtése |
| strikethroughHorizontal | boolean | Border Box Áthúzás vízszintesen |
| strikethroughVertical | boolean | Border Box Áthúzás függőlegesen |
| strikethroughBottomLeftToTopRight | boolean | Border Box Áthúzás bal alsó-tól jobb felső-ig |
| strikethroughTopLeftToBottomRight | boolean | Border Box Áthúzás bal felső-tól jobb alsó-ig |

**Visszatérési érték:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box with this element placed inside
### toBox() {#toBox--}
```
public abstract IMathBox toBox()
```

Az elemet egy nem látható dobozba (logikai csoportosítás) helyezi, amelyet egyenlet vagy egyéb matematikai szöveg összetevőinek csoportosítására használnak. Egy dobozba helyezett objektum (például) operátoros emulátorként szolgálhat igazítási ponttal vagy anélkül, vonaltörés pontként működhet, vagy úgy csoportosítható, hogy ne engedje meg a vonaltöréseket benne.
--------------------

> ```
> Példa:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**Visszatérési érték:**
[IMathBox](../../com.aspose.slides/imathbox) - Logical box with this element placed inside