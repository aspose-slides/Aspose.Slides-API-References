---
title: MathNaryOperator
second_title: Aspose.Slides için Java API Referansı
description: Toplam ve İntegral gibi N-ary bir matematiksel nesneyi tanımlar.
type: docs
url: /tr/com.aspose.slides/mathnaryoperator/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IMathNaryOperator](../../com.aspose.slides/imathnaryoperator), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathNaryOperator extends MathElementBase implements IMathNaryOperator, IHasControlCharacterProperties
```

N-ary bir matematiksel nesneyi tanımlar, örneğin Toplam ve İntegral. Bir operatör, bir temel (veya operand) ve isteğe bağlı üst ve alt limitlerden oluşur. N-ary operatörlere örnek olarak: Toplam, Birleşim, Kesişim, İntegral

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
## Metodlar

| Metod | Açıklama |
| --- | --- |
| [getBase()](#getBase--) | Temel argüman |
| [getSubscript()](#getSubscript--) | Bir alt çizgi argümanını belirtir; örneğin bir integral durumunda alt limiti ayarlar |
| [getSuperscript()](#getSuperscript--) | Bir üst çizgi argümanını belirtir; örneğin bir integralde üst limiti ayarlar |
| [getOperator()](#getOperator--) | Nary Operatör Karakteri Örneğin: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Nary Operatör Karakteri Örneğin: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | Limitlerin konumu (alt ve üst) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | Limitlerin konumu (alt ve üst) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Operatör Karakteri, operand yüksekliğine uyacak şekilde dikey olarak büyür |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Operatör Karakteri, operand yüksekliğine uyacak şekilde dikey olarak büyür |
| [getHideSubscript()](#getHideSubscript--) | Alt Çizgiyi Gizle |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Alt Çizgiyi Gizle |
| [getHideSuperscript()](#getHideSuperscript--) | Üst Çizgiyi Gizle |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Üst Çizgiyi Gizle |
| [getChildren()](#getChildren--) | Alt öğeleri al |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Kontrol Karakteri Özellikleri |
### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

MathNaryOperator sınıfının yeni bir örneğini başlatır.

--------------------

> ```
> Örnek:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i=0"), new MathematicalText("\ud835\udc5b"));
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| operatorSymbol | char | Nary operatör sembolü |
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
| operatorSymbol | char | Nary operatör sembolü |
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
| operatorSymbol | char | Nary operatör sembolü |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Temel argüman |
### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Temel argüman

--------------------

> ```
> Example:
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

Bir alt çizgi argümanını belirtir; örneğin bir integral durumunda alt limiti ayarlar

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

Bir üst çizgi argümanını belirtir; örneğin bir integralde üst limiti ayarlar

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

Limitlerin konumu (alt ve üst)

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

Limitlerin konumu (alt ve üst)

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
> Örnek:
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

Alt Çizgiyi Gizle

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

Alt Çizgiyi Gizle

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

Üst Çizgiyi Gizle

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

Üst Çizgiyi Gizle

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

Alt öğeleri al

**Döndürür:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Kontrol Karakteri Özellikleri

**Döndürür:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps