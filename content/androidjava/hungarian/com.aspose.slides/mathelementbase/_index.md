---
title: MathElementBase
second_title: Aspose.Slides Android számára Java API hivatkozás
description: Az IMathElement alaposztálya, amely bizonyos, az összes örökölt osztályra közös módszerek megvalósítását tartalmazza. Csak belső használatra.
type: docs
url: /hu/com.aspose.slides/mathelementbase/
---
**Öröklés:**
java.lang.Object

**Az összes megvalósított interfész:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

Az IMathElement alaposztálya, amely néhány, az összes örökölt osztályra közös metódust valósít meg. Csak belső használatra. Az örökölt osztálynak IMathElementnek kell lennie.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | Visszaadja a Parent_Immediate objektumot. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Összekapcsol egy matematikai elemet és létrehoz egy matematikai blokkot |
| [join(String mathText)](#join-java.lang.String-) | Összekapcsol egy matematikai szöveget és létrehoz egy matematikai blokkot |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Létrehoz egy törtet az aktuális számlálóval és a megadott nevezővel |
| [divide(String denominator)](#divide-java.lang.String-) | Létrehoz egy törtet az aktuális számlálóval és a megadott nevezővel |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Létrehoz a megadott típussal egy törtet az aktuális számlálóval és a megadott nevezővel |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Létrehoz a megadott típussal egy törtet az aktuális számlálóval és a megadott nevezővel |
| [enclose()](#enclose--) | Zár egy matematikai elemet zárójelek közé |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Zár egy matematikai elemet megadott karakterekkel, például zárójelekkel vagy más karakterekkel keretként |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Függvényt vesz egy argumentummal, és ezt az példányt használja a függvény nevének |
| [function(String functionArgument)](#function-java.lang.String-) | Függvényt vesz egy argumentummal, és ezt az példányt használja a függvény nevének |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Megadott függvényt vesz, és ezt az példányt használja argumentumként |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Megadott függvényt vesz, és ezt az példányt használja argumentumként |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Megadott függvényt vesz, és ezt az példányt használja argumentumként |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Megadott függvényt vesz, ezt az példányt használja argumentumként, valamint egy megadott további argumentumot |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Megadott függvényt vesz, ezt az példányt használja argumentumként, valamint egy megadott további argumentumot |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Létrehoz alsó indexet |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Létrehoz alsó indexet |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Létrehoz felső indexet |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Létrehoz felső indexet |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Létrehoz alsó és felső indexet jobbra |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Létrehoz alsó és felső indexet jobbra |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Létrehoz alsó és felső indexet balra |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Létrehoz alsó és felső indexet balra |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [radical(String degree)](#radical-java.lang.String-) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Felveszi a felső határt |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Felveszi a felső határt |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Felveszi az alsó határt |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Felveszi az alsó határt |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Létrehoz egy N-áris operátort |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | Létrehoz egy N-áris operátort |
| [toMathArray()](#toMathArray--) | Feltessz egy függőleges tömböt |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Felveszi az integrált |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Felveszi az integrált |
| [integral(int integralType)](#integral-int-) | Felveszi az integrált határok nélkül |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | Felveszi az integrált |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | Felveszi az integrált |
| [accent(char accentCharacter)](#accent-char-) | Beállít egy hangsúlyjelet (egy karaktert az elem tetején) |
| [overbar()](#overbar--) | Lehelyez egy vonalat az elem tetejére |
| [underbar()](#underbar--) | Lehelyez egy vonalat az elem aljára |
| [group()](#group--) | Ezt az elemet egy csoportba helyezi egy alsó kapcsos zárójel segítségével |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Ezt az elemet egy csoportba helyezi egy csoportosító karakterrel, például alsó kapcsos zárójellel vagy más karakterrel |
| [toBorderBox()](#toBorderBox--) | Ezt az elemet egy keretdobozba helyezi |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Ezt az elemet egy keretdobozba helyezi |
| [toBox()](#toBox--) | Ezt az elemet egy nem látható dobozba (logikai csoportosítás) helyezi, amelyet egyenlet komponensek vagy más matematikai szöveg példányok csoportosítására használnak. |
| [getChildren()](#getChildren--) | Gyermekelemek lekérése |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Összekapcsol egy matematikai elemet és létrehoz egy matematikai blokkot

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

**Visszatér:**
[IMathBlock](../../com.aspose.slides/imathblock) - Egy új IMathBlock, amely ezt a példányt és a megadott argumentumot tartalmazza

### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Összekapcsol egy matematikai szöveget és létrehoz egy matematikai blokkot

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
| mathText | java.lang.String | A csatlakoztatandó matematikai szöveg |

**Visszatér:**
[IMathBlock](../../com.aspose.slides/imathblock) - Egy új IMathBlock, amely ezt a példányt és a megadott argumentumot tartalmazza

### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public final IMathFraction divide(IMathElement denominator)
```

Létrehoz egy törtet az aktuális számlálóval és a megadott nevezővel

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

**Visszatér:**
[IMathFraction](../../com.aspose.slides/imathfraction) - új tört

### divide(String denominator) {#divide-java.lang.String-}
```
public final IMathFraction divide(String denominator)
```

Létrehoz egy törtet az aktuális számlálóval és a megadott nevezővel

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

**Visszatér:**
[IMathFraction](../../com.aspose.slides/imathfraction) - új tört

### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction divide(IMathElement denominator, int fractionType)
```

Létrehoz a megadott típussal egy törtet az aktuális számlálóval és a megadott nevezővel

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
| fractionType | int | Tört típusa: Bar, NoBar, Skewed, Linear |

**Visszatér:**
[IMathFraction](../../com.aspose.slides/imathfraction) - új tört

### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public final IMathFraction divide(String denominator, int fractionType)
```

Létrehoz a megadott típussal egy törtet az aktuális számlálóval és a megadott nevezővel

--------------------

> ```
> Példa:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| denominator | java.lang.String | Nevező |
| fractionType | int | Tört típusa: Bar, NoBar, Skewed, Linear |

**Visszatér:**
[IMathFraction](../../com.aspose.slides/imathfraction) - új tört

### enclose() {#enclose--}
```
public final IMathDelimiter enclose()
```

Zár egy matematikai elemet zárójelek közé

--------------------

> ```
> Példa:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```


**Visszatér:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - A [IMathDelimiter](../../com.aspose.slides/imathdelimiter) típusú matematikai elem, amely tartalmazza a zárójeleket

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Zár egy matematikai elemet megadott karakterekkel, például zárójelekkel vagy más karakterekkel keretként

--------------------

> ```
> Példa:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| beginningCharacter | char | Kezdő karakter (általában bal zárójel) |
| endingCharacter | char | Záró karakter (általában jobb zárójel) |

**Visszatér:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - A [IMathDelimiter](../../com.aspose.slides/imathdelimiter) típusú matematikai elem, amely tartalmazza a megadott karaktereket keretként

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```

Függvényt vesz egy argumentummal, és ezt az példányt használja a függvény nevének

--------------------

> ```
> Példa:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | A függvény argumentuma |

**Visszatér:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Új [IMathFunction](../../com.aspose.slides/imathfunction) típusú matematikai elem

### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```

Függvényt vesz egy argumentummal, és ezt az példányt használja a függvény nevének

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

**Visszatér:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Új [IMathFunction](../../com.aspose.slides/imathfunction) típusú matematikai elem

### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```

Megadott függvényt vesz, és ezt az példányt használja argumentumként

--------------------

> ```
> Példa:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | Függvény neve |

**Visszatér:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Új [IMathFunction](../../com.aspose.slides/imathfunction) típusú matematikai elem

### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(String functionName)
```

Megadott függvényt vesz, és ezt az példányt használja argumentumként

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

**Visszatér:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Új [IMathFunction](../../com.aspose.slides/imathfunction) típusú matematikai elem

### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public final IMathFunction asArgumentOfFunction(int functionType)
```

Megadott függvényt vesz, és ezt az példányt használja argumentumként

--------------------

> ```
> Példa:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionType | int | Egy, egy argumentumot elfogadó közös függvény típusa |

**Visszatér:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Új [IMathFunction](../../com.aspose.slides/imathfunction) típusú matematikai elem

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

Megadott függvényt vesz, ezt az példányt használja argumentumként, valamint egy megadott további argumentumot

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Visszaadja a 'x' logaritmusát a '5' alapra
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionType | int | Két argumentumot elfogadó közös függvény típusa: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | További argumentum a függvény típusától függően |

**Visszatér:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Új [IMathFunction](../../com.aspose.slides/imathfunction) típusú matematikai elem

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

Megadott függvényt vesz, ezt az példányt használja argumentumként, valamint egy megadott további argumentumot

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Visszaadja a 'x' logaritmusát a '5' alapra
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionType | int | Két argumentumot elfogadó közös függvény típusa: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | További argumentum a függvény típusától függően |

**Visszatér:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Új [IMathFunction](../../com.aspose.slides/imathfunction) típusú matematikai elem

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```

Létrehoz alsó indexet

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Alsó index (a jobb oldalon lévő alsó index) |

**Visszatér:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Új [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) típusú matematikai elem

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```

Létrehoz alsó indexet

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
| subscript | java.lang.String | Alsó index (a jobb oldalon lévő alsó index) |

**Visszatér:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Új [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) típusú matematikai elem

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

Létrehoz felső indexet

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
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Felső index (a jobb oldalon lévő felső index) |

**Visszatér:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Új [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) típusú matematikai elem

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```

Létrehoz felső indexet

--------------------

> ```
> Példa:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| superscript | java.lang.String | Felső index (a jobb oldalon lévő felső index) |

**Visszatér:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Új [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) típusú matematikai elem

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

Létrehoz alsó és felső indexet jobbra

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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Alsó index (a jobb oldalon lévő alsó index) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Felső index (a jobb oldalon lévő felső index) |

**Visszatér:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Új [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) típusú matematikai elem

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

Létrehoz alsó és felső indexet jobbra

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
| subscript | java.lang.String | Alsó index (a jobb oldalon lévő alsó index) |
| superscript | java.lang.String | Felső index (a jobb oldalon lévő felső index) |

**Visszatér:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Új [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) típusú matematikai elem

### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Létrehoz alsó és felső indexet balra

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Alsó index (a bal oldalon lévő alsó index) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Felső index (a bal oldalon lévő felső index) |

**Visszatér:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Új [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) típusú matematikai elem

### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Létrehoz alsó és felső indexet balra

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
| subscript | java.lang.String | Alsó index (a bal oldalon lévő alsó index) |
| superscript | java.lang.String | Felső index (a bal oldalon lévő felső index) |

**Visszatér:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Új [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) típusú matematikai elem

### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
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
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Gyök argumentuma |

**Visszatér:**
[IMathRadical](../../com.aspose.slides/imathradical) - Új [IMathRadical](../../com.aspose.slides/imathradical) típusú példány

### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
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
| degree | java.lang.String | Gyök argumentuma |

**Visszatér:**
[IMathRadical](../../com.aspose.slides/imathradical) - Új [IMathRadical](../../com.aspose.slides/imathradical) típusú példány

### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```

Felveszi a felső határt

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
| limit | [IMathElement](../../com.aspose.slides/imathelement) | határ |

**Visszatér:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Új [IMathLimit](../../com.aspose.slides/imathlimit) típusú példány

### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```

Felveszi a felső határt

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
| limit | java.lang.String | határ |

**Visszatér:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Új [IMathLimit](../../com.aspose.slides/imathlimit) típusú példány

### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

Felveszi az alsó határt

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
| limit | [IMathElement](../../com.aspose.slides/imathelement) | határ |

**Visszatér:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Új [IMathLimit](../../com.aspose.slides/imathlimit) típusú példány

### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

Felveszi az alsó határt

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
| limit | java.lang.String | határ |

**Visszatér:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Új [IMathLimit](../../com.aspose.slides/imathlimit) típusú példány

### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

Létrehoz egy N-áris operátort

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
| type | int | Az N-áris operátor típusa |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Az alsó határ |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Az felső határ |

**Visszatér:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Új [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) típusú példány

### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

Létrehoz egy N-áris operátort

--------------------

> ```
> Példa:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | Az N-áris operátor típusa |
| lowerLimit | java.lang.String | Az alsó határ |
| upperLimit | java.lang.String | Az felső határ |

**Visszatér:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Új [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) típusú példány

### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Feltessz egy függőleges tömböt

--------------------

> ```
> Példa:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Visszatér:**
[IMathArray](../../com.aspose.slides/imatharray) - Új [IMathArray](../../com.aspose.slides/imatharray) típusú példány

### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

Felveszi az integrált

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
| limitLocations | int | Határok helye |

**Visszatér:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Új [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) típusú példány

### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

Felveszi az integrált

--------------------

> ```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| integralType | int | Integrál típusa |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Integrál alsó határa |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Integrál felső határa |

**Visszatér:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Új [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) típusú példány

### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

Felveszi az integrált határok nélkül

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

**Visszatér:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Új [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) típusú példány

### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

Felveszi az integrált

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
| limitLocations | int | Határok helye |

**Visszatér:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Új [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) típusú példány

### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

Felveszi az integrált

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

**Visszatér:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Új [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) típusú példány

### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

Beállít egy hangsúlyjelet (egy karaktert az elem tetején)

--------------------

> ```
> Példa:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| accentCharacter | char | Hangsúly karakter. Az értéknek a (U+0300\\u2013U+036F) vagy (U+20D0\\u2013U+20EF) tartományon belül kell lennie |

**Visszatér:**
[IMathAccent](../../com.aspose.slides/imathaccent) - Új [IMathAccent](../../com.aspose.slides/imathaccent) típusú példány

### overbar() {#overbar--}
```
public final IMathBar overbar()
```

Lehelyez egy vonalat az elem tetejére

--------------------

> ```
> Példa:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**Visszatér:**
[IMathBar](../../com.aspose.slides/imathbar) - Új [IMathBar](../../com.aspose.slides/imathbar) típusú példány

### underbar() {#underbar--}
```
public final IMathBar underbar()
```

Lehelyez egy vonalat az elem aljára

--------------------

> ```
> Példa:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Visszatér:**
[IMathBar](../../com.aspose.slides/imathbar) - Új [IMathBar](../../com.aspose.slides/imathbar) típusú példány

### group() {#group--}
```
public final IMathGroupingCharacter group()
```

Ezt az elemet egy csoportba helyezi egy alsó kapcsos zárójel segítségével

--------------------

> ```
> Példa:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**Visszatér:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Új [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) típusú példány

### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Ezt az elemet egy csoportba helyezi egy csoportosító karakterrel, például alsó kapcsos zárójellel vagy más karakterrel

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| character | char | Csoportosító karakter, például BOTTOM CURLY BRACKET (U+23DF) vagy bármely más |
| position | int | A csoportosító karakter pozíciója |
| verticalJustification | int | A csoportkarakter függőleges igazítása. Megadja a objektum igazítását az alapvonalhoz képest. Például, ha a csoportkarakter az objektum felett van, a Top függőleges igazítás azt jelenti, hogy az objektum teteje az alapvonalra esik; ha Bottom van beállítva, az objektum alja az alapvonalra esik. |

**Visszatér:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Új [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) típusú példány

### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

Ezt az elemet egy keretdobozba helyezi

--------------------

> ```
> Példa:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Visszatér:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Keretdoboz, amelyben ez az elem helyezkedik el

### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Ezt az elemet egy keretdobozba helyezi

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
| hideRight | boolean | Jobb él elrejtése |
| strikethroughHorizontal | boolean | Horizontális áthúzás a Border Box-ban |
| strikethroughVertical | boolean | Vertikális áthúzás a Border Box-ban |
| strikethroughBottomLeftToTopRight | boolean | Áthúzás Bal alsó sarokból jobb felső sarokba |
| strikethroughTopLeftToBottomRight | boolean | Áthúzás Bal felső sarokból jobb alsó sarokba |

**Visszatér:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Keretdoboz, amelyben ez az elem helyezkedik el

### toBox() {#toBox--}
```
public final IMathBox toBox()
```

Ezt az elemet egy nem látható dobozba (logikai csoportosítás) helyezi, amelyet egyenlet komponensek vagy más matematikai szöveg példányok csoportosítására használnak. Egy dobozos objektum például operátorémulátorként szolgálhat igazítási pont nélkül vagy azzal, sorvégi pontként vagy úgy, hogy a sorok törését ne engedje.

--------------------

> ```
> Példa:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**Visszatér:**
[IMathBox](../../com.aspose.slides/imathbox) - Logikai doboz, amelyben ez az elem helyezkedik el

### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

Gyermekelemek lekérése

**Visszatér:**
com.aspose.slides.IMathElement[] - [IMathElement](../../com.aspose.slides/imathelement) tömb

