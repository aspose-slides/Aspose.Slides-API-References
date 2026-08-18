---
title: MathElementBase
second_title: Aspose.Slides for Java API Referencia
description: Az IMathElement alap osztálya, amely néhány, az összes leszármazott osztályra jellemző metódus implementációját tartalmazza. Csak belső használatra.
type: docs
url: /hu/com.aspose.slides/mathelementbase/
---
**Öröklődés:**
java.lang.Object

**Az összes megvalósított interfész:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

Alaposztály az IMathElement számára, amely néhány, az összes örökölt osztályra jellemző metódus implementációját tartalmazza. Csak belső használatra. Az örökölt osztálynak IMathElement-nek kell lennie.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | Visszaadja a Parent_Immediate objektumot. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Összevon egy matematikai elemet és egy matematikai blokkot hoz létre |
| [join(String mathText)](#join-java.lang.String-) | Összevon egy matematikai szöveget és egy matematikai blokkot hoz létre |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [divide(String denominator)](#divide-java.lang.String-) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Létrehoz egy megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Létrehoz egy megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [enclose()](#enclose--) | Zárja be a matematikai elemet zárójelek közé |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Zárja be a matematikai elemet megadott karakterek közé, például zárójelek vagy más karakterek keretezésként |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Függvényt vesz egy argumentummal, ez az példány a függvény neve |
| [function(String functionArgument)](#function-java.lang.String-) | Függvényt vesz egy argumentummal, ez az példány a függvény neve |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Megadott függvényt vesz, amelyben ez a példány az argumentum |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Megadott függvényt vesz, amelyben ez a példány az argumentum |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Megadott függvényt vesz, amelyben ez a példány az argumentum |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Megadott függvényt vesz, amelyben ez a példány az argumentum, plusz egy megadott további argumentum |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Megadott függvényt vesz, amelyben ez a példány az argumentum, plusz egy megadott további argumentum |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Alsó indexet hoz létre |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Alsó indexet hoz létre |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Felső indexet hoz létre |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Felső indexet hoz létre |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Létrehoz jobb oldali alsó és felső indexet |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Létrehoz jobb oldali alsó és felső indexet |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Létrehoz balra elhelyezett alsó és felső indexet |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Létrehoz balra elhelyezett alsó és felső indexet |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Megadja a megadott argumentum n-d ik gyökét. |
| [radical(String degree)](#radical-java.lang.String-) | Megadja a megadott argumentum n-d ik gyökét. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Felső határt vesz |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Felső határt vesz |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Alsó határt vesz |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Alsó határt vesz |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Létrehoz N-értelmű operátort |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | Létrehoz N-értelmű operátort |
| [toMathArray()](#toMathArray--) | Függőleges tömböt helyez el |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Integrált vesz fel |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Integrált vesz fel |
| [integral(int integralType)](#integral-int-) | Integrált vesz fel határok nélkül |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | Integrált vesz fel |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | Integrált vesz fel |
| [accent(char accentCharacter)](#accent-char-) | Akcentusjelet állít be (karakter az elem tetején) |
| [overbar()](#overbar--) | Vízszintes vonalat helyez az elem tetejére |
| [underbar()](#underbar--) | Vízszintes vonalat helyez az elem aljára |
| [group()](#group--) | Az elemet alsó kapcsos zárójelettel csoportba helyezi |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Az elemet egy csoportba helyezi egy csoportosító karakterrel, például alsó kapcsos zárójelez vagy más |
| [toBorderBox()](#toBorderBox--) | Az elemet keretdobozba helyezi |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Az elemet keretdobozba helyezi |
| [toBox()](#toBox--) | Az elemet nem látható dobozba (logikai csoportosítás) helyezi, amelyet egyenlet vagy más matematikai szöveg összetevőinek csoportosítására használnak. |
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


Összevon egy matematikai elemet és egy matematikai blokkot hoz létre

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
[IMathBlock](../../com.aspose.slides/imathblock) - Új IMathBlock, amely ezt a példányt és a megadott argumentumot tartalmaz
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```


Összevon egy matematikai szöveget és egy matematikai blokkot hoz létre

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
| mathText | java.lang.String | Összekapcsolandó matematikai szöveg |

**Visszatér:**
[IMathBlock](../../com.aspose.slides/imathblock) - Új IMathBlock, amely ezt a példányt és a megadott argumentumot tartalmaz
### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public final IMathFraction divide(IMathElement denominator)
```


Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel

--------------------

> ```
> Példa:
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


Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel

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


Létrehoz egy megadott típusú törtet ezzel a számlálóval és a megadott nevezővel

--------------------

> ```
> Példa:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Nevező |
| fractionType | int | Típus: Bar, NoBar, Skewed, Linear |

**Visszatér:**
[IMathFraction](../../com.aspose.slides/imathfraction) - új tört
### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public final IMathFraction divide(String denominator, int fractionType)
```


Létrehoz egy megadott típusú törtet ezzel a számlálóval és a megadott nevezővel

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
| fractionType | int | Típus: Bar, NoBar, Skewed, Linear |

**Visszatér:**
[IMathFraction](../../com.aspose.slides/imathfraction) - új tört
### enclose() {#enclose--}
```
public final IMathDelimiter enclose()
```


Zárja be a matematikai elemet zárójelek közé

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


Zárja be a matematikai elemet megadott karakterek közé, például zárójelek vagy más karakterek keretezésként

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
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - A [IMathDelimiter](../../com.aspose.slides/imathdelimiter) típusú matematikai elem, amely tartalmazza a megadott karaktereket keretezésként
### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```


Függvényt vesz egy argumentummal, ez az példány a függvény neve

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


Függvényt vesz egy argumentummal, ez az példány a függvény neve

--------------------

> ```
> Példa:
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


Megadott függvényt vesz, amelyben ez a példány az argumentum

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


Megadott függvényt vesz, amelyben ez a példány az argumentum

--------------------

> ```
> Példa:
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


Megadott függvényt vesz, amelyben ez a példány az argumentum

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
| functionType | int | Az egyargumentumos közös függvények egyike |

**Visszatér:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Új [IMathFunction](../../com.aspose.slides/imathfunction) típusú matematikai elem
### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```


Megadott függvényt vesz, amelyben ez a példány az argumentum, plusz egy megadott további argumentum

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Returns the logarithm of 'x' to the base '5'
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionType | int | A kétargumentumos közös függvények egyike: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | A függvénytől függő további argumentum |

**Visszatér:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Új [IMathFunction](../../com.aspose.slides/imathfunction) típusú matematikai elem
### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```


Megadott függvényt vesz, amelyben ez a példány az argumentum, plusz egy megadott további argumentum

--------------------

> ```
> Példa:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Visszaadja az 'x' logaritmusát az '5' alapra
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionType | int | A kétargumentumos közös függvények egyike: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | A függvénytől függő további argumentum |

**Visszatér:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Új [IMathFunction](../../com.aspose.slides/imathfunction) típusú matematikai elem
### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Alsó index (jobb oldali alsó index) |

**Visszatér:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Új [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) típusú matematikai elem
### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
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
| subscript | java.lang.String | Alsó index (jobb oldali alsó index) |

**Visszatér:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Új [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) típusú matematikai elem
### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
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
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Felső index (jobb oldali felső index) |

**Visszatér:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Új [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) típusú matematikai elem
### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```


Felső indexet hoz létre

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
| superscript | java.lang.String | Felső index (jobb oldali felső index) |

**Visszatér:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Új [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) típusú matematikai elem
### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```


Létrehoz jobb oldali alsó és felső indexet

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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Alsó index (jobb oldali alsó index) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Felső index (jobb oldali felső index) |

**Visszatér:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Új [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) típusú matematikai elem
### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```


Létrehoz jobb oldali alsó és felső indexet
> ```
> Példa:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subscript | java.lang.String | Alsó index (a jobb oldalon) |
| superscript | java.lang.String | Felső index (a jobb oldalon) |

**Visszatérési érték:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Új matematikai elem a(z) [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) típusból
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Alá- és felszkripciót hoz létre bal oldalon

---

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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Alsó index (a bal oldalon) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Felső index (a bal oldalon) |

**Visszatérési érték:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Új matematikai elem a(z) [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) típusból
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Alá- és felszkripciót hoz létre bal oldalon

---

> ```
> Példa:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subscript | java.lang.String | Alsó index (a bal oldalon) |
| superscript | java.lang.String | Felső index (a bal oldalon) |

**Visszatérési érték:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Új matematikai elem a(z) [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) típusból
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

Megadja a megadott fokú matematikai gyököt a megadott argumentumból.

---

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
| degree | [IMathElement](../../com.aspose.slides/imathelement) | A gyök fokszáma |

**Visszatérési érték:**
[IMathRadical](../../com.aspose.slides/imathradical) - Új példány a(z) [IMathRadical](../../com.aspose.slides/imathradical) típusból
### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```

Megadja a megadott fokú matematikai gyököt a megadott argumentumból.

---

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| degree | java.lang.String | A gyök fokszáma |

**Visszatérési érték:**
[IMathRadical](../../com.aspose.slides/imathradical) - Új példány a(z) [IMathRadical](../../com.aspose.slides/imathradical) típusból
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```

Felveszi a felső korlátot

---

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
[IMathLimit](../../com.aspose.slides/imathlimit) - Új példány a(z) [IMathLimit](../../com.aspose.slides/imathlimit) típusból
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```

Felveszi a felső korlátot

---

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
[IMathLimit](../../com.aspose.slides/imathlimit) - Új példány a(z) [IMathLimit](../../com.aspose.slides/imathlimit) típusból
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

Felveszi az alsó korlátot

---

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
[IMathLimit](../../com.aspose.slides/imathlimit) - Új példány a(z) [IMathLimit](../../com.aspose.slides/imathlimit) típusból
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

Felveszi az alsó korlátot

---

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
[IMathLimit](../../com.aspose.slides/imathlimit) - Új példány a(z) [IMathLimit](../../com.aspose.slides/imathlimit) típusból
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

N-áris operátort hoz létre

---

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
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Az alsó korlát |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | A felső korlát |

**Visszatérési érték:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Új példány a(z) [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) típusból
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

N-áris operátort hoz létre

---

> ```
> Példa:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | Az N-áris operátor típusa |
| lowerLimit | java.lang.String | Az alsó korlát |
| upperLimit | java.lang.String | A felső korlát |

**Visszatérési érték:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Új példány a(z) [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) típusból
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Függőleges tömbbe helyezi

---

> ```
> Példa:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```


**Visszatérési érték:**
[IMathArray](../../com.aspose.slides/imatharray) - Új példány a(z) [IMathArray](../../com.aspose.slides/imatharray) típusból
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

Integrált vesz fel

---

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
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Az integrál alsó határa |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Az integrál felső határa |
| limitLocations | int | Határok elhelyezkedése |

**Visszatérési érték:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Új példány a(z) [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) típusból
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

Integrált vesz fel

---

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
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Az integrál alsó határa |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Az integrál felső határa |

**Visszatérési érték:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Új példány a(z) [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) típusból
### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

Korlátok nélküli integrált vesz fel

---

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
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Új példány a(z) [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) típusból
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

Integrált vesz fel

---

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
| lowerLimit | java.lang.String | Az integrál alsó határa |
| upperLimit | java.lang.String | Az integrál felső határa |
| limitLocations | int | Határok elhelyezkedése |

**Visszatérési érték:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Új példány a(z) [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) típusból
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

Integrált vesz fel

---

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
| lowerLimit | java.lang.String | Az integrál alsó határa |
| upperLimit | java.lang.String | Az integrál felső határa |

**Visszatérési érték:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Új példány a(z) [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) típusból
### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

Akcentus jelet állít be (egy karakter az elem tetején)

---

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
[IMathAccent](../../com.aspose.slides/imathaccent) - Új példány a(z) [IMathAccent](../../com.aspose.slides/imathaccent) típusból
### overbar() {#overbar--}
```
public final IMathBar overbar()
```

Vonalat helyez az elem tetejére

---

> ```
> Példa:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```


**Visszatérési érték:**
[IMathBar](../../com.aspose.slides/imathbar) - Új példány a(z) [IMathBar](../../com.aspose.slides/imathbar) típusból
### underbar() {#underbar--}
```
public final IMathBar underbar()
```

Vonalat helyez az elem aljára

---

> ```
> Példa:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Visszatérési érték:**
[IMathBar](../../com.aspose.slides/imathbar) - Új példány a(z) [IMathBar](../../com.aspose.slides/imathbar) típusból
### group() {#group--}
```
public final IMathGroupingCharacter group()
```

Az elemet egy csoportba helyezi alsó kapcsos zárójelet használva

---

> ```
> Példa:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**Visszatérési érték:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Új példány a(z) [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) típusból
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Az elemet egy csoportba helyezi egy csoportosító karakter (pl. alsó kapcsos zárójel vagy más) használatával

---

> ```
> Példa:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| character | char | Csoportosító karakter, például BOTTOM CURLY BRACKET (U+23DF) vagy bármely más |
| position | int | A csoportosító karakter pozíciója |
| verticalJustification | int | A csoportosító karakter függőleges igazítása. Meghatározza az objektum igazítását az alapvonalhoz képest. Például, ha a karakter az objektum felett van, a Top igazítás azt jelenti, hogy az objektum teteje az alapvonalon van; ha a Bottom érték van beállítva, akkor az objektum alja az alapvonalon van |

**Visszatérési érték:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Új példány a(z) [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) típusból
### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

Az elemet egy szegélydobozba helyezi

---

> ```
> Példa:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Visszatérési érték:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Szegélydoboz az elemmel belül
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Az elemet egy szegélydobozba helyezi

---

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
| strikethroughHorizontal | boolean | Szegélydoboz vízszintes áthúzása |
| strikethroughVertical | boolean | Szegélydoboz függőleges áthúzása |
| strikethroughBottomLeftToTopRight | boolean | Szegélydoboz áthúzása bal alsó saroktól jobb felső sarokig |
| strikethroughTopLeftToBottomRight | boolean | Szegélydoboz áthúzása bal felső saroktól jobb alsó sarokig |

**Visszatérési érték:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Szegélydoboz az elemmel belül
### toBox() {#toBox--}
```
public final IMathBox toBox()
```

Az elemet egy nem látható dobozba (logikai csoportosítás) helyezi, amelyet egyenlet vagy egyéb matematikai szövegrész komponenseinek csoportosítására használnak. Egy keretezett objektum például operátor emulátorként szolgálhat igazítási ponttal vagy anélkül, sorbontási pontként működhet, vagy úgy csoportosítható, hogy ne engedje a sortöréseket.

---

> ```
> Példa:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```


**Visszatérési érték:**
[IMathBox](../../com.aspose.slides/imathbox) - Logikai doboz az elemmel belül
### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

Gyermekelemek lekérése

**Visszatérési érték:**
com.aspose.slides.IMathElement[] - [IMathElement](../../com.aspose.slides/imathelement) tömbje