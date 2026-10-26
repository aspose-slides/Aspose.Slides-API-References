---
title: MathNaryOperator
second_title: Aspose.Slides för Android via Java API-referens
description: Anger ett N-ärt matematiskt objekt, såsom Summation och Integral.
type: docs
url: /sv/com.aspose.slides/mathnaryoperator/
---
**Arv:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathNaryOperator](../../com.aspose.slides/imathnaryoperator), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathNaryOperator extends MathElementBase implements IMathNaryOperator, IHasControlCharacterProperties
```

Anger ett N-ärt matematiskt objekt, såsom summation och integral. Det består av en operator, en bas (eller operand) och valfria övre och nedre gränser. Exempel på N-ära operatorer är: Summation, Union, Intersection, Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initierar en ny instans av MathNaryOperator-klassen. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initierar en ny instans av MathNaryOperator-klassen. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#MathNaryOperator-char-com.aspose.slides.IMathElement-) | Initierar en ny instans av MathNaryOperator-klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBase()](#getBase--) | Basargument |
| [getSubscript()](#getSubscript--) | Anger ett subskript-argument som exempelvis i fallet med en integral sätter den nedre gränsen |
| [getSuperscript()](#getSuperscript--) | Anger ett superskript-argument som exempelvis i fallet med en integral sätter den övre gränsen |
| [getOperator()](#getOperator--) | N-är operator-tecken Till exempel: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | N-är operator-tecken Till exempel: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | Platsen för gränserna (subskript och superskript) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | Platsen för gränserna (subskript och superskript) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Operator-tecken växer vertikalt för att matcha operandens höjd |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Operator-tecken växer vertikalt för att matcha operandens höjd |
| [getHideSubscript()](#getHideSubscript--) | Dölj subskript |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Dölj subskript |
| [getHideSuperscript()](#getHideSuperscript--) | Dölj superskript |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Dölj superskript |
| [getChildren()](#getChildren--) | Hämta barn-element |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Egenskaper för kontrolltecken |
### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

Initierar en ny instans av MathNaryOperator-klassen.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i=0"), new MathematicalText("\ud835\udc5b"));
```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| operatorSymbol | char | N-är operator-symbol |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basargument |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Nedre gräns |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Övre gräns |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

Initierar en ny instans av MathNaryOperator-klassen.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i"));
```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| operatorSymbol | char | N-är operator-symbol |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basargument |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Nedre gräns |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#MathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

Initierar en ny instans av MathNaryOperator-klassen.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"));
```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| operatorSymbol | char | N-är operator-symbol |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basargument |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Basargument

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
> ```

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```

Anger ett subskript-argument som exempelvis i fallet med en integral sätter den nedre gränsen

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```

Anger ett superskript-argument som exempelvis i fallet med en integral sätter den övre gränsen

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperator() {#getOperator--}
```
public final char getOperator()
```

N-är operator-tecken Till exempel: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Returnerar:**
char
### setOperator(char value) {#setOperator-char-}
```
public final void setOperator(char value)
```

N-är operator-tecken Till exempel: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public final int getLimitLocation()
```

Platsen för gränserna (subskript och superskript)

--------------------

> ```
> Exempel:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Returnerar:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public final void setLimitLocation(int value)
```

Platsen för gränserna (subskript och superskript)

--------------------

> ```
> Exempel:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```

Operator-tecken växer vertikalt för att matcha operandens höjd

--------------------

> ```
> Exempel:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Returnerar:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

Operator-tecken växer vertikalt för att matcha operandens höjd

--------------------

> ```
> Exempel:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public final boolean getHideSubscript()
```

Dölj subskript

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Returnerar:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public final void setHideSubscript(boolean value)
```

Dölj subskript

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public final boolean getHideSuperscript()
```

Dölj superskript

--------------------

> ```
> Exempel:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Returnerar:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public final void setHideSuperscript(boolean value)
```

Dölj superskript

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Hämta barn-element

**Returnerar:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Egenskaper för kontrolltecken

**Returnerar:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps