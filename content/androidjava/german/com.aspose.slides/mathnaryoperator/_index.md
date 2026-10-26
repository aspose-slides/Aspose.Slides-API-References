---
title: MathNaryOperator
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Beschreibt ein n-äres mathematisches Objekt wie Summation und Integral.
type: docs
url: /de/com.aspose.slides/mathnaryoperator/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathNaryOperator](../../com.aspose.slides/imathnaryoperator), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathNaryOperator extends MathElementBase implements IMathNaryOperator, IHasControlCharacterProperties
```

Beschreibt ein n-äres mathematisches Objekt, wie Summation und Integral. Es besteht aus einem Operator, einer Basis (oder Operand) und optionalen oberen und unteren Grenzen. Beispiele für n-äre Operatoren sind: Summation, Union, Intersection, Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initialisiert eine neue Instanz der MathNaryOperator-Klasse. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initialisiert eine neue Instanz der MathNaryOperator-Klasse. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#MathNaryOperator-char-com.aspose.slides.IMathElement-) | Initialisiert eine neue Instanz der MathNaryOperator-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getSubscript()](#getSubscript--) | Gibt ein tiefgestelltes Argument an, das zum Beispiel im Fall eines Integrals die untere Grenze festlegt |
| [getSuperscript()](#getSuperscript--) | Gibt ein hochgestelltes Argument an, das zum Beispiel im Fall eines Integrals die obere Grenze festlegt |
| [getOperator()](#getOperator--) | N-äres Operator-Zeichen, zum Beispiel: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | N-äres Operator-Zeichen, zum Beispiel: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | Lage der Grenzen (Tief- und Hochstellung) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | Lage der Grenzen (Tief- und Hochstellung) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Operator-Zeichen wächst vertikal, um die Höhe seines Operanden anzupassen |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Operator-Zeichen wächst vertikal, um die Höhe seines Operanden anzupassen |
| [getHideSubscript()](#getHideSubscript--) | Untertiefstellung ausblenden |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Untertiefstellung ausblenden |
| [getHideSuperscript()](#getHideSuperscript--) | Hochstellung ausblenden |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Hochstellung ausblenden |
| [getChildren()](#getChildren--) | Kind-Elemente abrufen |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Steuerzeichen-Eigenschaften |
### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


Initialisiert eine neue Instanz der MathNaryOperator-Klasse.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i=0"), new MathematicalText("\ud835\udc5b"));
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| operatorSymbol | char | N-äres Operatorsymbol |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Untere Grenze |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Obere Grenze |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


Initialisiert eine neue Instanz der MathNaryOperator-Klasse.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i"));
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| operatorSymbol | char | N-äres Operatorsymbol |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Untere Grenze |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#MathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


Initialisiert eine neue Instanz der MathNaryOperator-Klasse.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"));
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| operatorSymbol | char | N-äres Operatorsymbol |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Basisargument

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
> ```

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```


Gibt ein tiefgestelltes Argument an, das zum Beispiel im Fall eines Integrals die untere Grenze festlegt

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```


Gibt ein hochgestelltes Argument an, das zum Beispiel im Fall eines Integrals die obere Grenze festlegt

--------------------

> ```
> Beispiel:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperator() {#getOperator--}
```
public final char getOperator()
```


N-äres Operator-Zeichen, zum Beispiel: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Rückgabewert:**
char
### setOperator(char value) {#setOperator-char-}
```
public final void setOperator(char value)
```


N-äres Operator-Zeichen, zum Beispiel: '\\u2211', '\\u222b'

--------------------

> ```
> Beispiel:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public final int getLimitLocation()
```


Lage der Grenzen (Tief- und Hochstellung)

--------------------

> ```
> Beispiel:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Rückgabewert:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public final void setLimitLocation(int value)
```


Lage der Grenzen (Tief- und Hochstellung)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```


Operator-Zeichen wächst vertikal, um die Höhe seines Operanden anzupassen

--------------------

> ```
> Beispiel:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Rückgabewert:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```


Operator-Zeichen wächst vertikal, um die Höhe seines Operanden anzupassen

--------------------

> ```
> Beispiel:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public final boolean getHideSubscript()
```


Untertiefstellung ausblenden

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Rückgabewert:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public final void setHideSubscript(boolean value)
```


Untertiefstellung ausblenden

--------------------

> ```
> Beispiel:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public final boolean getHideSuperscript()
```


Hochstellung ausblenden

--------------------

> ```
> Beispiel:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Rückgabewert:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public final void setHideSuperscript(boolean value)
```


Hochstellung ausblenden

--------------------

> ```
> Beispiel:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Kind-Elemente abrufen

**Rückgabewert:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Steuerzeichen-Eigenschaften

**Rückgabewert:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps