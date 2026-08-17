---
title: IMathPhantom
second_title: Aspose.Slides for Java API Referansı
description: Çocuk öğesinin düzenini, mutlaka görüntülenmesi gerekmeksizin etkileyen bir hayalet matematik nesnesini temsil eder.
type: docs
url: /tr/com.aspose.slides/imathphantom/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

Bir alt öğesinin düzenini mutlaka göstermezken etkileyen bir hayalet matematik nesnesini (<m:phant>) temsil eder. Hayalet, formülleri hizalamak veya boşluk ayırmak için genişlik, yükseklik veya derinliğini koruyarak temel ifadesini gizleyebilir. Görünürlük ve geometri davranışı Show, ZeroWid, ZeroAsc, ZeroDesc ve Transp gibi özelliklerle kontrol edilir.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // İçeriği gizle
>  phantom.setZeroWidth(false);     // Genişliği koru
>  ```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getShow()](#getShow--) | Gets or sets a value indicating whether the base element is displayed. |
| [setShow(boolean value)](#setShow-boolean-) | Gets or sets a value indicating whether the base element is displayed. |
| [getZeroWidth()](#getZeroWidth--) | Gets or sets a value indicating whether the width of the base element should be treated as zero. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Gets or sets a value indicating whether the width of the base element should be treated as zero. |
| [getZeroAsc()](#getZeroAsc--) | Gets or sets a value indicating whether the ascent (height above baseline) of the base element should be treated as zero. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Gets or sets a value indicating whether the ascent (height above baseline) of the base element should be treated as zero. |
| [getZeroDesc()](#getZeroDesc--) | Gets or sets a value indicating whether the descent (depth below baseline) of the base element should be treated as zero. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Gets or sets a value indicating whether the descent (depth below baseline) of the base element should be treated as zero. |
| [getTransp()](#getTransp--) | Gets or sets a value indicating whether the phantom is transparent for class-based spacing rules. |
| [setTransp(boolean value)](#setTransp-boolean-) | Gets or sets a value indicating whether the phantom is transparent for class-based spacing rules. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Temel argüman

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
>  ```


**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public abstract boolean getShow()
```


Temel öğenin gösterilip gösterilmediğini belirten bir değeri alır veya ayarlar.

--------------------

false olduğunda, temel öğe gizlenir ancak diğer hayalet ayarlarına bağlı olarak hâlâ yer kaplayabilir. OMML özniteliği m:show ile eşleşir.

**Döndürür:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```


Temel öğenin gösterilip gösterilmediğini belirten bir değeri alır veya ayarlar.

--------------------

false olduğunda, temel öğe gizlenir ancak diğer hayalet ayarlarına bağlı olarak hâlâ yer kaplayabilir. OMML özniteliği m:show ile eşleşir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```


Temel öğenin genişliğinin sıfır olarak ele alınması gerekip gerekmediğini belirten bir değeri alır veya ayarlar.

--------------------

true olduğunda, hayalet temel için yatay alan ayırmaz. OMML özniteliği m:zeroWid ile eşleşir.

**Döndürür:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```


Temel öğenin genişliğinin sıfır olarak ele alınması gerekip gerekmediğini belirten bir değeri alır veya ayarlar.

--------------------

true olduğunda, hayalet temel için yatay alan ayırmaz. OMML özniteliği m:zeroWid ile eşleşir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```


Temel öğenin yükselişinin (taban çizgisinin üzerindeki yükseklik) sıfır olarak ele alınması gerekip gerekmediğini belirten bir değeri alır veya ayarlar.

--------------------

true olduğunda, hayalet çevredeki matematik satırının taban çizgisini yükseltmez. OMML özniteliği m:zeroAsc ile eşleşir.

**Döndürür:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```


Temel öğenin yükselişinin (taban çizgisinin üzerindeki yükseklik) sıfır olarak ele alınması gerekip gerekmediğini belirten bir değeri alır veya ayarlar.

--------------------

true olduğunda, hayalet çevredeki matematik satırının taban çizgisini yükseltmez. OMML özniteliği m:zeroAsc ile eşleşir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```


Temel öğenin alçalmasının (taban çizgisinin altındaki derinlik) sıfır olarak ele alınması gerekip gerekmediğini belirten bir değeri alır veya ayarlar.

--------------------

true olduğunda, hayalet çevredeki matematik satırının taban çizgisini alçaltmaz. OMML özniteliği m:zeroDesc ile eşleşir.

**Döndürür:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```


Temel öğenin alçalmasının (taban çizgisinin altındaki derinlik) sıfır olarak ele alınması gerekip gerekmediğini belirten bir değeri alır veya ayarlar.

--------------------

true olduğunda, hayalet çevredeki matematik satırının taban çizgisini alçaltmaz. OMML özniteliği m:zeroDesc ile eşleşir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```


Hayaletin sınıf tabanlı boşluk kuralları için şeffaf olup olmadığını belirten bir değeri alır veya ayarlar.

--------------------

true olduğunda, hayalet içindeki operatörler ve semboller hayaletin etrafındaki matematiksel boşlukları etkiler (görünürmüş gibi). false olduğunda, sınıf tabanlı boşluk kuralları yok sayılır. OMML özniteliği m:transp ile eşleşir.

**Döndürür:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)
```


Hayaletin sınıf tabanlı boşluk kuralları için şeffaf olup olmadığını belirten bir değeri alır veya ayarlar.

--------------------

true olduğunda, hayalet içindeki operatörler ve semboller hayaletin etrafındaki matematiksel boşlukları etkiler (görünürmüş gibi). false olduğunda, sınıf tabanlı boşluk kuralları yok sayılır. OMML özniteliği m:transp ile eşleşir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |