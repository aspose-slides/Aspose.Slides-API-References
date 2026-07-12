---
title: MathPhantom
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: ltmphantgt adlı hayalet bir matematik nesnesini temsil eder; bu nesne, alt öğesinin düzenini mutlaka görüntülenmek zorunda olmaksızın etkiler.
type: docs
url: /tr/com.aspose.slides/mathphantom/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

Temel ifadesini mutlaka göstermeden, alt öğesinin düzenini etkileyen bir sahte matematik nesnesini (<m:phant>) temsil eder. Bir sahte, temel ifadesini gizleyebilir ancak formülleri hizalamak veya boşluk ayırmak için genişliğini, yüksekliğini veya derinliğini korur. Görünürlük ve geometrik davranış Show, ZeroWid, ZeroAsc, ZeroDesc ve Transp gibi özelliklerle kontrol edilir.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // İçeriği gizle
>  phantom.setZeroWidth(false);     // Genişliği koru
> ```
## Yapıcılar

| Constructor | Description |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | Belirtilen temel matematik öğesini kullanarak [MathPhantom](../../com.aspose.slides/mathphantom) sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Temel argüman |
| [getShow()](#getShow--) | Temel öğenin görüntülenip görüntülenmediğini belirten bir değeri alır veya ayarlar. |
| [setShow(boolean value)](#setShow-boolean-) | Temel öğenin görüntülenip görüntülenmediğini belirten bir değeri alır veya ayarlar. |
| [getZeroWidth()](#getZeroWidth--) | Temel öğenin genişliğinin sıfır olarak değerlendirilip değerlendirilmeyeceğini belirten bir değeri alır veya ayarlar. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Temel öğenin genişliğinin sıfır olarak değerlendirilip değerlendirilmeyeceğini belirten bir değeri alır veya ayarlar. |
| [getZeroAsc()](#getZeroAsc--) | Temel öğenin yükselişinin (çizgi üstü yükseklik) sıfır olarak değerlendirilip değerlendirilmeyeceğini belirten bir değeri alır veya ayarlar. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Temel öğenin yükselişinin (çizgi üstü yükseklik) sıfır olarak değerlendirilip değerlendirilmeyeceğini belirten bir değeri alır veya ayarlar. |
| [getZeroDesc()](#getZeroDesc--) | Temel öğenin alçalmasının (çizgi altı derinlik) sıfır olarak değerlendirilip değerlendirilmeyeceğini belirten bir değeri alır veya ayarlar. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Temel öğenin alçalmasının (çizgi altı derinlik) sıfır olarak değerlendirilip değerlendirilmeyeceğini belirten bir değeri alır veya ayarlar. |
| [getTransp()](#getTransp--) | Phantom'un sınıf tabanlı boşluk kuralları için şeffaf olup olmadığını belirten bir değeri alır veya ayarlar. |
| [setTransp(boolean value)](#setTransp-boolean-) | Phantom'un sınıf tabanlı boşluk kuralları için şeffaf olup olmadığını belirten bir değeri alır veya ayarlar. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Kontrol Karakteri Özellikleri |
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
| element | [IMathElement](../../com.aspose.slides/imathelement) | Phantom tarafından görünürlüğü ve düzeni kontrol edilecek temel [IMathElement](../../com.aspose.slides/imathelement). Bu öğe, gizlenebilen veya gösterilebilen içeriği tanımlar ve çevredeki matematiğin geometrik hizalamasını etkiler. |

--------------------

Phantom öğesi, temel ifadesinin görsel alanını rezerve etmek veya bastırmak için kullanılır; mutlaka gösterilmesi gerekmez. OMML öğesi <m:phant> ile eşdeğerdir. |

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

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public final boolean getShow()
```


Temel öğenin görüntülenip görüntülenmediğini belirten bir değeri alır veya ayarlar.

--------------------

Yanlış olduğunda, temel öğe gizlenir ancak diğer phantom ayarlarına bağlı olarak hâlâ yer kaplayabilir. OMML niteliği m:show ile eşdeğerdir.

**Döndürür:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```


Temel öğenin görüntülenip görüntülenmediğini belirten bir değeri alır veya ayarlar.

--------------------

Yanlış olduğunda, temel öğe gizlenir ancak diğer phantom ayarlarına bağlı olarak hâlâ yer kaplayabilir. OMML niteliği m:show ile eşdeğerdir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```


Temel öğenin genişliğinin sıfır olarak değerlendirilip değerlendirilmeyeceğini belirten bir değeri alır veya ayarlar.

--------------------

Doğru olduğunda, phantom temel için yatay alan ayırmaz. OMML niteliği m:zeroWid ile eşdeğerdir.

**Döndürür:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```


Temel öğenin genişliğinin sıfır olarak değerlendirilip değerlendirilmeyeceğini belirten bir değeri alır veya ayarlar.

--------------------

Doğru olduğunda, phantom temel için yatay alan ayırmaz. OMML niteliği m:zeroWid ile eşdeğerdir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```


Temel öğenin yükselişinin (çizgi üstü yükseklik) sıfır olarak değerlendirilip değerlendirilmeyeceğini belirten bir değeri alır veya ayarlar.

--------------------

Doğru olduğunda, phantom çevredeki matematik satırının taban çizgisini yükseltmez. OMML niteliği m:zeroAsc ile eşdeğerdir.

**Döndürür:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```


Temel öğenin yükselişinin (çizgi üstü yükseklik) sıfır olarak değerlendirilip değerlendirilmeyeceğini belirten bir değeri alır veya ayarlar.

--------------------

Doğru olduğunda, phantom çevredeki matematik satırının taban çizgisini yükseltmez. OMML niteliği m:zeroAsc ile eşdeğerdir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```


Temel öğenin alçalmasının (çizgi altı derinlik) sıfır olarak değerlendirilip değerlendirilmeyeceğini belirten bir değeri alır veya ayarlar.

--------------------

Doğru olduğunda, phantom çevredeki matematik satırının taban çizgisini alçaltmaz. OMML niteliği m:zeroDesc ile eşdeğerdir.

**Döndürür:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```


Temel öğenin alçalmasının (çizgi altı derinlik) sıfır olarak değerlendirilip değerlendirilmeyeceğini belirten bir değeri alır veya ayarlar.

--------------------

Doğru olduğunda, phantom çevredeki matematik satırının taban çizgisini alçaltmaz. OMML niteliği m:zeroDesc ile eşdeğerdir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public final boolean getTransp()
```


Phantom'un sınıf tabanlı boşluk kuralları için şeffaf olup olmadığını belirten bir değeri alır veya ayarlar.

--------------------

Doğru olduğunda, phantom içindeki operatör ve semboller, phantom (görünürmüş gibi) matematiksel boşlukları etkilemeye devam eder. Yanlış olduğunda, sınıf tabanlı boşluk yok sayılır. OMML niteliği m:transp ile eşdeğerdir.

**Döndürür:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```


Phantom'un sınıf tabanlı boşluk kuralları için şeffaf olup olmadığını belirten bir değeri alır veya ayarlar.

--------------------

Doğru olduğunda, phantom içindeki operatör ve semboller, phantom (görünürmüş gibi) matematiksel boşlukları etkilemeye devam eder. Yanlış olduğunda, sınıf tabanlı boşluk yok sayılır. OMML niteliği m:transp ile eşdeğerdir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Kontrol Karakteri Özellikleri

**Döndürür:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Çocuk öğeleri al

**Döndürür:**
com.aspose.slides.IMathElement[]