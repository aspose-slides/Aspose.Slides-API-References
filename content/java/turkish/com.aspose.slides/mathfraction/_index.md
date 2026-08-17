---
title: MathFraction
second_title: Aspose.Slides for Java API Referansı
description: Bir pay ve paydayı kesir çubuğu ile ayıran kesir nesnesini belirtir.
type: docs
url: /tr/com.aspose.slides/mathfraction/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IMathFraction](../../com.aspose.slides/imathfraction), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathFraction extends MathElementBase implements IMathFraction, IHasControlCharacterProperties
```

Bir pay ve payda içeren, payda çubuğu ile ayrılmış kesir nesnesini tanımlar. Kesir çubuğu, kesir özelliklerine bağlı olarak yatay ya da diyagonal olabilir. Kesir nesnesi ayrıca, bir elemanı diğerinin üzerine yerleştiren ve kesir çubuğu olmayan yığın işlevini temsil etmek için de kullanılır.

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Belirtilen payı, paydayı ve türü ile MathFraction'ı başlatır |
| [MathFraction(IMathElement numerator, IMathElement denominator)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Belirtilen payı ve paydayı ile 'Bar' türünde bir MathFraction'ı başlatır |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFractionType()](#getFractionType--) | Kesir türü Varsayılan: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Kesir türü Varsayılan: Bar |
| [getNumerator()](#getNumerator--) | Pay |
| [getDenominator()](#getDenominator--) | Payda |
| [getChildren()](#getChildren--) | Alt öğeleri al |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Kontrol Karakteri Özellikleri |
### MathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


Belirtilen payı, paydayı ve türü ile MathFraction'ı başlatır

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Pay |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Payda |
| fractionType | int | Kesir türü |

### MathFraction(IMathElement numerator, IMathElement denominator) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFraction(IMathElement numerator, IMathElement denominator)
```


Belirtilen payı ve paydayı ile 'Bar' türünde bir MathFraction'ı başlatır

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"));
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Pay |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Payda |

### getFractionType() {#getFractionType--}
```
public final int getFractionType()
```


Kesir türü Varsayılan: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Döndürür:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public final void setFractionType(int value)
```


Kesir türü Varsayılan: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getNumerator() {#getNumerator--}
```
public final IMathElement getNumerator()
```


Pay

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public final IMathElement getDenominator()
```


Payda

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
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