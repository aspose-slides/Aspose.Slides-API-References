---
title: MathNaryOperator
second_title: Aspose.Slides dla Java – odniesienie API
description: Określa obiekt matematyczny n-arności, taki jak suma i całka.
type: docs
url: /pl/com.aspose.slides/mathnaryoperator/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**
[com.aspose.slides.IMathNaryOperator](../../com.aspose.slides/imathnaryoperator), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathNaryOperator extends MathElementBase implements IMathNaryOperator, IHasControlCharacterProperties
```

Określa obiekt matematyczny n-arności, taki jak Suma i Całka. Składa się z operatora, podstawy (lub operandu) oraz opcjonalnych górnych i dolnych limitów. Przykłady operatorów n-arności to: Summation, Union, Intersection, Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Inicjalizuje nową instancję klasy MathNaryOperator. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Inicjalizuje nową instancję klasy MathNaryOperator. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#MathNaryOperator-char-com.aspose.slides.IMathElement-) | Inicjalizuje nową instancję klasy MathNaryOperator. |
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Argument bazowy |
| [getSubscript()](#getSubscript--) | Określa argument indeksu dolnego, który np. w przypadku całki ustawia dolny limit |
| [getSuperscript()](#getSuperscript--) | Określa argument indeksu górnego, który np. w przypadku całki ustawia górny limit |
| [getOperator()](#getOperator--) | Znak operatora N-owego, np.: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Znak operatora N-owego, np.: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | Lokalizacja limitów (indeks dolny i indeks górny) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | Lokalizacja limitów (indeks dolny i indeks górny) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Znak operatora rośnie pionowo, aby dopasować się do wysokości operanda |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Znak operatora rośnie pionowo, aby dopasować się do wysokości operanda |
| [getHideSubscript()](#getHideSubscript--) | Ukryj indeks dolny |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Ukryj indeks dolny |
| [getHideSuperscript()](#getHideSuperscript--) | Ukryj indeks górny |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Ukryj indeks górny |
| [getChildren()](#getChildren--) | Pobierz elementy potomne |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Właściwości znaków kontrolnych |
### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


Inicjalizuje nową instancję klasy MathNaryOperator.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i=0"), new MathematicalText("\ud835\udc5b"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | Symbol operatora N-owego |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argument bazowy |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Dolny limit |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Górny limit |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


Inicjalizuje nową instancję klasy MathNaryOperator.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | Symbol operatora N-owego |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argument bazowy |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Dolny limit |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#MathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


Inicjalizuje nową instancję klasy MathNaryOperator.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | Symbol operatora N-owego |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argument bazowy |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Argument bazowy

--------------------

> ```
> Example:
>  
>  IMMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMMathElement baseArg = naryOperator.getBase();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```


Określa argument indeksu dolnego, który np. w przypadku całki ustawia dolny limit

--------------------

> ```
> Przykład:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```


Określa argument indeksu górnego, który np. w przypadku całki ustawia górny limit

--------------------

> ```
> Przykład:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperator() {#getOperator--}
```
public final char getOperator()
```


Znak operatora N-owego, np.: '\\u2211', '\\u222b'

--------------------

> ```
> Przykład:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Returns:**
char
### setOperator(char value) {#setOperator-char-}
```
public final void setOperator(char value)
```


Znak operatora N-owego, np.: '\\u2211', '\\u222b'

--------------------

> ```
> Przykład:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public final int getLimitLocation()
```


Lokalizacja limitów (indeks dolny i indeks górny)

--------------------

> ```
> Przykład:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Returns:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public final void setLimitLocation(int value)
```


Lokalizacja limitów (indeks dolny i indeks górny)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```


Znak operatora rośnie pionowo, aby dopasować się do wysokości operanda

--------------------

> ```
> Przykład:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Returns:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```


Znak operatora rośnie pionowo, aby dopasować się do wysokości operanda

--------------------

> ```
> Przykład:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public final boolean getHideSubscript()
```


Ukryj indeks dolny

--------------------

> ```
> Przykład:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Returns:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public final void setHideSubscript(boolean value)
```


Ukryj indeks dolny

--------------------

> ```
> Przykład:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public final boolean getHideSuperscript()
```


Ukryj indeks górny

--------------------

> ```
> Przykład:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Returns:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public final void setHideSuperscript(boolean value)
```


Ukryj indeks górny

--------------------

> ```
> Przykład:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Pobierz elementy potomne

**Returns:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Właściwości znaków kontrolnych

**Returns:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps