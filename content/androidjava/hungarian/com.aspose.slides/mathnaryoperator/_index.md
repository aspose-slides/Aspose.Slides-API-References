---
title: MathNaryOperator
second_title: Aspose.Slides Androidra a Java API hivatkozás
description: N-árnyalatos matematikai objektumot határoz meg, például Összegzést és Integrált.
type: docs
url: /hu/com.aspose.slides/mathnaryoperator/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Az összes megvalósított interfész:**
[com.aspose.slides.IMathNaryOperator](../../com.aspose.slides/imathnaryoperator), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathNaryOperator extends MathElementBase implements IMathNaryOperator, IHasControlCharacterProperties
```

N-árnyalatos matematikai objektumot határoz meg, például Összegzés és Integrál. Egy operátorból, egy alapból (vagy operandusból) és opcionális felső és alsó határokból áll. N-árnyalatos operátorok példái: Összegzés, Unió, Metszés, Integrál

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Létrehoz egy új példányt a MathNaryOperator osztályból. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Létrehoz egy új példányt a MathNaryOperator osztályból. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#MathNaryOperator-char-com.aspose.slides.IMathElement-) | Létrehoz egy új példányt a MathNaryOperator osztályból. |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getBase()](#getBase--) | Alap argumentum |
| [getSubscript()](#getSubscript--) | Megad egy alsó index argumentumot, például egy integrál esetén, ami beállítja az alsó határt |
| [getSuperscript()](#getSuperscript--) | Megad egy felső index argumentumot, például egy integrál esetén, ami beállítja a felső határt |
| [getOperator()](#getOperator--) | N-ary operátor karakter Például: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | N-ary operátor karakter Például: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | A határok helye (alsó és felső index) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | A határok helye (alsó és felső index) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Operátor karakter függőlegesen nő, hogy megfeleljen az operandus magasságának |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Operátor karakter függőlegesen nő, hogy megfeleljen az operandus magasságának |
| [getHideSubscript()](#getHideSubscript--) | Alsó index elrejtése |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Alsó index elrejtése |
| [getHideSuperscript()](#getHideSuperscript--) | Felső index elrejtése |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Felső index elrejtése |
| [getChildren()](#getChildren--) | Gyermek elemek lekérése |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Vezérlő karakter tulajdonságok |
### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


Létrehoz egy új példányt a MathNaryOperator osztályból.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i=0"), new MathematicalText("\ud835\udc5b"));
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| operatorSymbol | char | N-ary operátor szimbólum |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Alap argumentum |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Alsó határ |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Felső határ |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


Létrehoz egy új példányt a MathNaryOperator osztályból.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i"));
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| operatorSymbol | char | N-ary operátor szimbólum |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Alap argumentum |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Alsó határ |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#MathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


Létrehoz egy új példányt a MathNaryOperator osztályból.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"));
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| operatorSymbol | char | N-ary operátor szimbólum |
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


Megad egy alsó index argumentumot, például egy integrál esetén, ami beállítja az alsó határt

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


Megad egy felső index argumentumot, például egy integrál esetén, ami beállítja a felső határt

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


N-ary operátor karakter Például: '\\u2211', '\\u222b'

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


N-ary operátor karakter Például: '\\u2211', '\\u222b'

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


A határok helye (alsó és felső index)

--------------------

> ```
> Example:
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


A határok helye (alsó és felső index)

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


Operátor karakter függőlegesen nő, hogy megfeleljen az operandus magasságának

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


Operátor karakter függőlegesen nő, hogy megfeleljen az operandus magasságának

--------------------

> ```
> Példa:
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


Alsó index elrejtése

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


Alsó index elrejtése

--------------------

> ```
> Example:
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


Felső index elrejtése

--------------------

> ```
> Példa:
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


Felső index elrejtése

--------------------

> ```
> Example:
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


Gyermek elemek lekérése

**Visszatér:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Vezérlő karakter tulajdonságok

**Visszatér:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps