---
title: MathPhantom
second_title: Aspose.Slides for Java API Referansı
description: Phantom bir matematik nesnesi olan ltmphantgt'yi temsil eder; bu nesne, alt öğesinin düzenini gerekli olmadan görüntülenmeden etkiler.
type: docs
url: /tr/com.aspose.slides/mathphantom/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

Bir fantezi matematik nesnesini (<m:phant>) temsil eder ve alt öğesinin düzenini, mutlaka görüntülenmesi gerekmeden etkiler. Bir fantezi, temel ifadesini gizleyebilir ancak formülleri hizalamak veya boşluk ayırmak için genişliğini, yüksekliğini veya derinliğini korur. Görünürlük ve geometrik davranış, Show, ZeroWid, ZeroAsc, ZeroDesc ve Transp gibi özelliklerle kontrol edilir.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // İçeriği gizle
>  phantom.setZeroWidth(false);     // Genişliği koru
```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | Belirtilen temel matematik öğesini kullanarak [MathPhantom](../../com.aspose.slides/mathphantom) sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBase()](#getBase--) | Temel argüman |
| [getShow()](#getShow--) | Temel öğenin görüntülenip görüntülenmediğini belirten bir değeri alır veya ayarlar. |
| [setShow(boolean value)](#setShow-boolean-) | Temel öğenin görüntülenip görüntülenmediğini belirten bir değeri alır veya ayarlar. |
| [getZeroWidth()](#getZeroWidth--) | Temel öğenin genişliğinin sıfır olarak ele alınması gerektiğini belirten bir değeri alır veya ayarlar. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Temel öğenin genişliğinin sıfır olarak ele alınması gerektiğini belirten bir değeri alır veya ayarlar. |
| [getZeroAsc()](#getZeroAsc--) | Temel öğenin yukarı doğru yükselişinin (taban çizgisinin üzerindeki yükseklik) sıfır olarak ele alınması gerektiğini belirten bir değeri alır veya ayarlar. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Temel öğenin yukarı doğru yükselişinin (taban çizgisinin üzerindeki yükseklik) sıfır olarak ele alınması gerektiğini belirten bir değeri alır veya ayarlar. |
| [getZeroDesc()](#getZeroDesc--) | Temel öğenin aşağı doğru alçalmasının (taban çizgisinin altındaki derinlik) sıfır olarak ele alınması gerektiğini belirten bir değeri alır veya ayarlar. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Temel öğenin aşağı doğru alçalmasının (taban çizgisinin altındaki derinlik) sıfır olarak ele alınması gerektiğini belirten bir değeri alır veya ayarlar. |
| [getTransp()](#getTransp--) | Sınıf tabanlı boşluk kuralları için fantezin şeffaf olup olmadığını belirten bir değeri alır veya ayarlar. |
| [setTransp(boolean value)](#setTransp-boolean-) | Sınıf tabanlı boşluk kuralları için fantezin şeffaf olup olmadığını belirten bir değeri alır veya ayarlar. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Kontrol Karakter Özellikleri |
| [getChildren()](#getChildren--) | Çocuk öğeleri al |
### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```

Belirtilen temel matematik öğesini kullanarak [MathPhantom](../../com.aspose.slides/mathphantom) sınıfının yeni bir örneğini başlatır.

--------------------

> ```
> Example:
>  
>  IMathElement fraction = new MathFraction(
>      new MathematicalText("1"),
>      new MathematicalText("2"));
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Fantez tarafından görünürlüğü ve düzeni kontrol edilecek temel [IMathElement](../../com.aspose.slides/imathelement). Bu öğe gizlenebilir veya gösterilebilir, ancak çevredeki matematiğin geometrik hizalamasını etkiler. |

The phantom element is used to reserve or suppress the visual space of its base expression without necessarily displaying it. It corresponds to the OMML element <m:phant>. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Temel argüman

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Dönüş Değeri:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public final boolean getShow()
```

Temel öğenin görüntülenip görüntülenmediğini belirten bir değeri alır veya ayarlar.

--------------------

Yanlış olduğunda, temel öğe gizlenir ancak diğer fantezi ayarlarına bağlı olarak hâlâ alan kaplayabilir. OMML özniteliği m:show ile eşdeğerdir.

**Dönüş Değeri:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```

Temel öğenin görüntülenip görüntülenmediğini belirten bir değeri alır veya ayarlar.

--------------------

Yanlış olduğunda, temel öğe gizlenir ancak diğer fantezi ayarlarına bağlı olarak hâlâ alan kaplayabilir. OMML özniteliği m:show ile eşdeğerdir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```

Temel öğenin genişliğinin sıfır olarak ele alınması gerektiğini belirten bir değeri alır veya ayarlar.

--------------------

Doğru olduğunda, fantezi temel öğesi için yatay alan ayırmaz. OMML özniteliği m:zeroWid ile eşdeğerdir.

**Dönüş Değeri:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```

Temel öğenin genişliğinin sıfır olarak ele alınması gerektiğini belirten bir değeri alır veya ayarlar.

--------------------

Doğru olduğunda, fantezi temel öğesi için yatay alan ayırmaz. OMML özniteliği m:zeroWid ile eşdeğerdir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```

Temel öğenin yukarı doğru yükselişinin (taban çizgisinin üzerindeki yükseklik) sıfır olarak ele alınması gerektiğini belirten bir değeri alır veya ayarlar.

--------------------

Doğru olduğunda, fantezi çevredeki matematik satırının taban çizgisini yükseltmez. OMML özniteliği m:zeroAsc ile eşdeğerdir.

**Dönüş Değeri:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```

Temel öğenin yukarı doğru yükselişinin (taban çizgisinin üzerindeki yükseklik) sıfır olarak ele alınması gerektiğini belirten bir değeri alır veya ayarlar.

--------------------

Doğru olduğunda, fantezi çevredeki matematik satırının taban çizgisini yükseltmez. OMML özniteliği m:zeroAsc ile eşdeğerdir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```

Temel öğenin aşağı doğru alçalmasının (taban çizgisinin altındaki derinlik) sıfır olarak ele alınması gerektiğini belirten bir değeri alır veya ayarlar.

--------------------

Doğru olduğunda, fantezi çevredeki matematik satırının taban çizgisini alçaltmaz. OMML özniteliği m:zeroDesc ile eşdeğerdir.

**Dönüş Değeri:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```

Temel öğenin aşağı doğru alçalmasının (taban çizgisinin altındaki derinlik) sıfır olarak ele alınması gerektiğini belirten bir değeri alır veya ayarlar.

--------------------

Doğru olduğunda, fantezi çevredeki matematik satırının taban çizgisini alçaltmaz. OMML özniteliği m:zeroDesc ile eşdeğerdir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getTransp() {#getTransp--}
```
public final boolean getTransp()
```

Sınıf tabanlı boşluk kuralları için fantezin şeffaf olup olmadığını belirten bir değeri alır veya ayarlar.

--------------------

Doğru olduğunda, fantezin içindeki operatörler ve semboller hâlâ fantezin etrafındaki matematiksel boşluğu etkiler (görünür gibi). Yanlış olduğunda, sınıf tabanlı boşluk yoksayılır. OMML özniteliği m:transp ile eşdeğerdir.

**Dönüş Değeri:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```

Sınıf tabanlı boşluk kuralları için fantezin şeffaf olup olmadığını belirten bir değeri alır veya ayarlar.

--------------------

Doğru olduğunda, fantezin içindeki operatörler ve semboller hâlâ fantezin etrafındaki matematiksel boşluğu etkiler (görünür gibi). Yanlış olduğunda, sınıf tabanlı boşluk yoksayılır. OMML özniteliği m:transp ile eşdeğerdir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Kontrol Karakter Özellikleri

**Dönüş Değeri:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Çocuk öğeleri al

**Dönüş Değeri:**
com.aspose.slides.IMathElement[]