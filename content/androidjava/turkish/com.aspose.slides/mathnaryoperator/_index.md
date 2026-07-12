---
title: MathNaryOperator
second_title: Aspose.Slides Android için Java API Referansı
description: Toplama ve İntegral gibi N-ary matematiksel bir nesneyi tanımlar.
type: docs
url: /tr/com.aspose.slides/mathnaryoperator/
---
**Kalıtım:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Uygulanan Tüm Arabirimler:**  
[com.aspose.slides.IMathNaryOperator](../../com.aspose.slides/imathnaryoperator), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathNaryOperator extends MathElementBase implements IMathNaryOperator, IHasControlCharacterProperties
```

N-ary bir matematiksel nesneyi tanımlar; örnek olarak Toplama ve İntegral gibi. Bir operatör, bir temel (veya operand) ve isteğe bağlı üst ve alt limitlerden oluşur. N-ary operatör örnekleri: Toplama, Birleşim, Kesişim, İntegral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | MathNaryOperator sınıfının yeni bir örneğini başlatır. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | MathNaryOperator sınıfının yeni bir örneğini başlatır. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#MathNaryOperator-char-com.aspose.slides.IMathElement-) | MathNaryOperator sınıfının yeni bir örneğini başlatır. |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getBase()](#getBase--) | Temel argüman |
| [getSubscript()](#getSubscript--) | Alt simge argümanını belirtir; örneğin integralde alt sınırı ayarlar |
| [getSuperscript()](#getSuperscript--) | Üst simge argümanını belirtir; örneğin integralde üst sınırı ayarlar |
| [getOperator()](#getOperator--) | Nary Operatör Karakteri Örneğin: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Nary Operatör Karakteri Örneğin: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | Sınırlamaların konumu (alt ve üst simge) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | Sınırlamaların konumu (alt ve üst simge) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Operatör Karakteri, operand yüksekliğine uyacak şekilde dikey olarak büyür |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Operatör Karakteri, operand yüksekliğine uyacak şekilde dikey olarak büyür |
| [getHideSubscript()](#getHideSubscript--) | Alt Simgeyi Gizle |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Alt Simgeyi Gizle |
| [getHideSuperscript()](#getHideSuperscript--) | Üst Simgeyi Gizle |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Üst Simgeyi Gizle |
| [getChildren()](#getChildren--) | Alt elemanları al |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Kontrol Karakteri Özellikleri |
### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


MathNaryOperator sınıfının yeni bir örneğini başlatır.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i=0"), new MathematicalText("\ud835\udc5b"));
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| operatorSymbol | char | N-ary operatör sembolü |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Temel argüman |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Alt limit |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Üst limit |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


MathNaryOperator sınıfının yeni bir örneğini başlatır.

--------------------

> ```
> Örnek:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i"));
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| operatorSymbol | char | N-ary operatör sembolü |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Temel argüman |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Alt limit |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#MathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


MathNaryOperator sınıfının yeni bir örneğini başlatır.

--------------------

> ```
> Örnek:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"));
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| operatorSymbol | char | N-ary operatör sembolü |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Temel argüman |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Temel argüman

--------------------

> ```
> Örnek:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
> ```

**Döndürür:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```


Alt simge argümanını belirtir; örneğin integralde alt sınırı ayarlar

--------------------

> ```
> Örnek:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**Döndürür:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```


Üst simge argümanını belirtir; örneğin integralde üst sınırı ayarlar

--------------------

> ```
> Örnek:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```


**Döndürür:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getOperator() {#getOperator--}
```
public final char getOperator()
```


Nary Operatör Karakteri Örneğin: '\\u2211', '\\u222b'

--------------------

> ```
> Örnek:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Döndürür:**  
char
### setOperator(char value) {#setOperator-char-}
```
public final void setOperator(char value)
```


Nary Operatör Karakteri Örneğin: '\\u2211', '\\u222b'

--------------------

> ```
> Örnek:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public final int getLimitLocation()
```


Sınırlamaların konumu (alt ve üst simge)

--------------------

> ```
> Örnek:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Döndürür:**  
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public final void setLimitLocation(int value)
```


Sınırlamaların konumu (alt ve üst simge)

--------------------

> ```
> Örnek:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```


Operatör Karakteri, operand yüksekliğine uyacak şekilde dikey olarak büyür

--------------------

> ```
> Örnek:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Döndürür:**  
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```


Operatör Karakteri, operand yüksekliğine uyacak şekilde dikey olarak büyür

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public final boolean getHideSubscript()
```


Alt Simgeyi Gizle

--------------------

> ```
> Örnek:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Döndürür:**  
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public final void setHideSubscript(boolean value)
```


Alt Simgeyi Gizle

--------------------

> ```
> Örnek:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public final boolean getHideSuperscript()
```


Üst Simgeyi Gizle

--------------------

> ```
> Örnek:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Döndürür:**  
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public final void setHideSuperscript(boolean value)
```


Üst Simgeyi Gizle

--------------------

> ```
> Örnek:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Alt elemanları al

**Döndürür:**  
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Kontrol Karakteri Özellikleri

**Döndürür:**  
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps