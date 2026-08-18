---
title: MathNaryOperator
second_title: Aspose.Slides Java API-referencia
description: Megad egy N-áris matematikai objektumot, például összegzést és integrált.
type: docs
url: /hu/com.aspose.slides/mathnaryoperator/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Minden megvalósított interfész:**
[com.aspose.slides.IMathNaryOperator](../../com.aspose.slides/imathnaryoperator), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathNaryOperator extends MathElementBase implements IMathNaryOperator, IHasControlCharacterProperties
```

N-áris matematikai objektumot határoz meg, például összegzést és integrált. Egy operátorból, egy bázisból (vagy operandusból) és opcionális felső és alsó határból áll. Az N-áris operátorok példái: Összegzés, Unió, Metszet, Integrál

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Új példányt hoz létre a MathNaryOperator osztályból. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Új példányt hoz létre a MathNaryOperator osztályból. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#MathNaryOperator-char-com.aspose.slides.IMathElement-) | Új példányt hoz létre a MathNaryOperator osztályból. |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getBase()](#getBase--) | Alap argumentum |
| [getSubscript()](#getSubscript--) | Aláindex argumentumot ad meg, amely például integrál esetén az alsó határt állítja be |
| [getSuperscript()](#getSuperscript--) | Felsőindex argumentumot ad meg, amely például integrál esetén a felső határt állítja be |
| [getOperator()](#getOperator--) | N-áris operátor karakter. Például: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | N-áris operátor karakter. Például: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | A határok helye (alindex és felsőindex) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | A határok helye (alindex és felsőindex) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Az operátor karakter függőlegesen nő, hogy illeszkedjen az operandus magasságához |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Az operátor karakter függőlegesen nő, hogy illeszkedjen az operandus magasságához |
| [getHideSubscript()](#getHideSubscript--) | Alindex elrejtése |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Alindex elrejtése |
| [getHideSuperscript()](#getHideSuperscript--) | Felsőindex elrejtése |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Felsőindex elrejtése |
| [getChildren()](#getChildren--) | Gyermekelemek lekérése |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Vezérlő karakter tulajdonságok |
### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

Új példányt hoz létre a MathNaryOperator osztályból.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i=0"), new MathematicalText("\ud835\udc5b"));
```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| operatorSymbol | char | N-áris operátor szimbólum |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Alap argumentum |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Alsó határ |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Felső határ |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

Új példányt hoz létre a MathNaryOperator osztályból.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i"));
```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| operatorSymbol | char | N-áris operátor szimbólum |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Alap argumentum |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Alsó határ |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#MathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

Új példányt hoz létre a MathNaryOperator osztályból.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"));
```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| operatorSymbol | char | N-áris operátor szimbólum |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Alap argumentum |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Alap argumentum

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
> ```

**Visszatér:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```

Aláindex argumentumot ad meg, amely például integrál esetén az alsó határt állítja be

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**Visszatér:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```

Felsőindex argumentumot ad meg, amely például integrál esetén a felső határt állítja be

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Visszatér:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperator() {#getOperator--}
```
public final char getOperator()
```

N-áris operátor karakter. Például: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Visszatér:**
char
### setOperator(char value) {#setOperator-char-}
```
public final void setOperator(char value)
```

N-áris operátor karakter. Például: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public final int getLimitLocation()
```

A határok helye (alindex és felsőindex)

--------------------

> ```
> Példa:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Visszatér:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public final void setLimitLocation(int value)
```

A határok helye (alindex és felsőindex)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```

Az operátor karakter függőlegesen nő, hogy illeszkedjen az operandus magasságához

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Visszatér:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

Az operátor karakter függőlegesen nő, hogy illeszkedjen az operandus magasságához

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public final boolean getHideSubscript()
```

Alindex elrejtése

--------------------

> ```
> Példa:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Visszatér:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public final void setHideSubscript(boolean value)
```

Alindex elrejtése

--------------------

> ```
> Példa:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public final boolean getHideSuperscript()
```

Felsőindex elrejtése

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Visszatér:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public final void setHideSuperscript(boolean value)
```

Felsőindex elrejtése

--------------------

> ```
> Példa:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Gyermekelemek lekérése

**Visszatér:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Vezérlő karakter tulajdonságok

**Visszatér:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps