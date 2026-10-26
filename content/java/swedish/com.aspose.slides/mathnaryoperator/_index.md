---
title: MathNaryOperator
second_title: Aspose.Slides för Java API-referens
description: Specificerar ett N-ärt matematiskt objekt såsom Summation och Integral.
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

Specificerar ett N-ärt matematiskt objekt, såsom Summation och Integral. Det består av en operator, en bas (eller operand), och valfria övre och nedre gränser. Exempel på N-ära operatorer är: Summation, Union, Intersection, Integral

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
| [getSubscript()](#getSubscript--) | Specificerar ett subskriptargument som till exempel, i fallet med en integral, anger den nedre gränsen |
| [getSuperscript()](#getSuperscript--) | Specificerar ett superskriptargument som till exempel, i fallet med en integral, anger den övre gränsen |
| [getOperator()](#getOperator--) | N-ärt operatortecken Till exempel: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | N-ärt operatortecken Till exempel: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | Placeringen av gränserna (subskript och superskript) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | Placeringen av gränserna (subskript och superskript) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Operatortecken växer vertikalt för att matcha operandens höjd |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Operatortecken växer vertikalt för att matcha operandens höjd |
| [getHideSubscript()](#getHideSubscript--) | Dölj subskript |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Dölj subskript |
| [getHideSuperscript()](#getHideSuperscript--) | Dölj superskript |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Dölj superskript |
| [getChildren()](#getChildren--) | Hämta barnelement |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Kontrollteckenegenskaper |
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
| operatorSymbol | char | N-ärt operatorsymbol |
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
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| operatorSymbol | char | N-ärt operatorsymbol |
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
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| operatorSymbol | char | N-ärt operatorsymbol |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basargument |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Basargument

--------------------

> ```
> Exempel:
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


Specificerar ett subskriptargument som till exempel, i fallet med en integral, anger den nedre gränsen

--------------------

> ```
> Exempel:
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


Specificerar ett superskriptargument som till exempel, i fallet med en integral, anger den övre gränsen

--------------------

> ```
> Exempel:
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


N-ärt operatortecken Till exempel: '\\u2211', '\\u222b'

--------------------

> ```
> Exempel:
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


N-ärt operatortecken Till exempel: '\\u2211', '\\u222b'

--------------------

> ```
> Exempel:
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


Placeringen av gränserna (subskript och superskript)

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


Placeringen av gränserna (subskript och superskript)

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


Operatortecken växer vertikalt för att matcha operandens höjd

--------------------

> ```
> Exempel:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> 
```

**Returnerar:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```


Operatortecken växer vertikalt för att matcha operandens höjd

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
> Exempel:
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
> Exempel:
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
> Exempel:
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


Hämta barnelement

**Returnerar:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Kontrollteckenegenskaper

**Returnerar:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps