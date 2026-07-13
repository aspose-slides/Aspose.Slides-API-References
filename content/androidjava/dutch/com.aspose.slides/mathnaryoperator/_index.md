---
title: MathNaryOperator
second_title: Aspose.Slides voor Android via Java API-referentie
description: Specificeert een N-ary wiskundig object, zoals Som en Integraal.
type: docs
url: /nl/com.aspose.slides/mathnaryoperator/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathNaryOperator](../../com.aspose.slides/imathnaryoperator), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathNaryOperator extends MathElementBase implements IMathNaryOperator, IHasControlCharacterProperties
```

Specificeert een N-ary wiskundig object, zoals Som en Integraal. Het bestaat uit een operator, een basis (of operand), en optionele boven- en onderlimieten. Voorbeelden van N-ary operatoren zijn: Som, Unie, Doorsnede, Integraal

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initialiseert een nieuw exemplaar van de MathNaryOperator-klasse. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initialiseert een nieuw exemplaar van de MathNaryOperator-klasse. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#MathNaryOperator-char-com.aspose.slides.IMathElement-) | Initialiseert een nieuw exemplaar van de MathNaryOperator-klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getSubscript()](#getSubscript--) | Specificeert een subscript argument dat bijvoorbeeld, in het geval van een integraal, de onderlimiet instelt |
| [getSuperscript()](#getSuperscript--) | Specificeert een superscript argument dat bijvoorbeeld, in het geval van een integraal, de bovenlimiet instelt |
| [getOperator()](#getOperator--) | Nary-operatorteken Bijvoorbeeld: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Nary-operatorteken Bijvoorbeeld: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | De locatie van limieten (subscript en superscript) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | De locatie van limieten (subscript en superscript) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Operatorteken groeit verticaal om de hoogte van zijn operand te evenaren |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Operatorteken groeit verticaal om de hoogte van zijn operand te evenaren |
| [getHideSubscript()](#getHideSubscript--) | Verberg subscript |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Verberg subscript |
| [getHideSuperscript()](#getHideSuperscript--) | Verberg superscript |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Verberg superscript |
| [getChildren()](#getChildren--) | Haalt kindelementen op |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Eigenschappen van controlekarakters |
### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

Initialiseert een nieuw exemplaar van de MathNaryOperator-klasse.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i=0"), new MathematicalText("\ud835\udc5b"));
```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| operatorSymbol | char | Nary-operator symbool |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Onderlimiet |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Bovenlimiet |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

Initialiseert een nieuw exemplaar van de MathNaryOperator-klasse.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i"));
```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| operatorSymbol | char | Nary-operator symbool |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Onderlimiet |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#MathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

Initialiseert een nieuw exemplaar van de MathNaryOperator-klasse.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"));
```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| operatorSymbol | char | Nary-operator symbool |
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
```

**Retourwaarde:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```

Specificeert een subscript argument dat bijvoorbeeld, in het geval van een integraal, de onderlimiet instelt

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
```

**Retourwaarde:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```

Specificeert een superscript argument dat bijvoorbeeld, in het geval van een integraal, de bovenlimiet instelt

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Retourwaarde:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperator() {#getOperator--}
```
public final char getOperator()
```

Nary-operatorteken Bijvoorbeeld: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Retourwaarde:**
char
### setOperator(char value) {#setOperator-char-}
```
public final void setOperator(char value)
```

Nary-operatorteken Bijvoorbeeld: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public final int getLimitLocation()
```

De locatie van limieten (subscript en superscript)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Retourwaarde:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public final void setLimitLocation(int value)
```

De locatie van limieten (subscript en superscript)

--------------------

> ```
public final void setLimitLocation(int value)
```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```

Operatorteken groeit verticaal om de hoogte van zijn operand te evenaren

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Retourwaarde:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

Operatorteken groeit verticaal om de hoogte van zijn operand te evenaren

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public final boolean getHideSubscript()
```

Verberg subscript

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Retourwaarde:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public final void setHideSubscript(boolean value)
```

Verberg subscript

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public final boolean getHideSuperscript()
```

Verberg superscript

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Retourwaarde:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public final void setHideSuperscript(boolean value)
```

Verberg superscript

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Haalt kindelementen op

**Retourwaarde:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Eigenschappen van controlekarakters

**Retourwaarde:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps