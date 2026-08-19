---
title: MathNaryOperator
second_title: Aspose.Slides pro Java API Reference
description: Specifikuje n-ary matematický objekt, například Summation a Integral.
type: docs
url: /cs/com.aspose.slides/mathnaryoperator/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IMathNaryOperator](../../com.aspose.slides/imathnaryoperator), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathNaryOperator extends MathElementBase implements IMathNaryOperator, IHasControlCharacterProperties
```

Specifikuje n-ary matematický objekt, jako je Summation a Integral. Skládá se z operátoru, základny (nebo operandu) a volitelných horních a dolních mezí. Příklady n-ary operátorů jsou: Summation, Union, Intersection, Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Inicializuje novou instanci třídy MathNaryOperator. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Inicializuje novou instanci třídy MathNaryOperator. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#MathNaryOperator-char-com.aspose.slides.IMathElement-) | Inicializuje novou instanci třídy MathNaryOperator. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getBase()](#getBase--) | Základní argument |
| [getSubscript()](#getSubscript--) | Specifikuje argument dolního indexu, který například v případě integrálu určuje dolní mez |
| [getSuperscript()](#getSuperscript--) | Specifikuje argument horního indexu, který například v případě integrálu určuje horní mez |
| [getOperator()](#getOperator--) | Znak n-ary operátoru. Například: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Znak n-ary operátoru. Například: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | Umístění mezí (dolní a horní index) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | Umístění mezí (dolní a horní index) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Znak operátoru roste vertikálně, aby odpovídal výšce operandu |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Znak operátoru roste vertikálně, aby odpovídal výšce operandu |
| [getHideSubscript()](#getHideSubscript--) | Skrýt dolní index |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Skrýt dolní index |
| [getHideSuperscript()](#getHideSuperscript--) | Skrýt horní index |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Skrýt horní index |
| [getChildren()](#getChildren--) | Získat podřízené prvky |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Vlastnosti řídícího znaku |
### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

Inicializuje novou instanci třídy MathNaryOperator.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i=0"), new MathematicalText("\ud835\udc5b"));
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| operatorSymbol | char | Symbol n-ary operátoru |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Základní argument |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Dolní mez |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Horní mez |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

Inicializuje novou instanci třídy MathNaryOperator.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i"));
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| operatorSymbol | char | Symbol n-ary operátoru |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Základní argument |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Dolní mez |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#MathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

Inicializuje novou instanci třídy MathNaryOperator.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"));
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| operatorSymbol | char | Symbol n-ary operátoru |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Základní argument |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Základní argument

--------------------

> ```
> Example:
>  
>  IMMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMMathElement baseArg = naryOperator.getBase();
> ```

**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```

Specifikuje argument dolního indexu, který například v případě integrálu určuje dolní mez

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```

Specifikuje argument horního indexu, který například v případě integrálu určuje horní mez

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperator() {#getOperator--}
```
public final char getOperator()
```

Znak n-ary operátoru. Například: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Vrací:**
char
### setOperator(char value) {#setOperator-char-}
```
public final void setOperator(char value)
```

Znak n-ary operátoru. Například: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public final int getLimitLocation()
```

Umístění mezí (dolní a horní index)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Vrací:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public final void setLimitLocation(int value)
```

Umístění mezí (dolní a horní index)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```

Znak operátoru roste vertikálně, aby odpovídal výšce operandu

--------------------

> ```
> Příklad:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Vrací:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

Znak operátoru roste vertikálně, aby odpovídal výšce operandu

--------------------

> ```
> Příklad:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public final boolean getHideSubscript()
```

Skrýt dolní index

--------------------

> ```
> Příklad:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Vrací:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public final void setHideSubscript(boolean value)
```

Skrýt dolní index

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public final boolean getHideSuperscript()
```

Skrýt horní index

--------------------

> ```
> Příklad:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Vrací:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public final void setHideSuperscript(boolean value)
```

Skrýt horní index

--------------------

> ```
> Příklad:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Získat podřízené prvky

**Vrací:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Vlastnosti řídícího znaku

**Vrací:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps