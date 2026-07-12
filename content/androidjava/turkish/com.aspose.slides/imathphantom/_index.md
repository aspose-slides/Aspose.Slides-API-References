---
title: IMathPhantom
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Çocuk öğesinin yerleşimini etkileyen, zorunlu olarak görüntülenmesi gerekmeyen bir hayalet matematik nesnesi ltmphantgt temsil eder.
type: docs
url: /tr/com.aspose.slides/imathphantom/
---
**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

Yalnızca görüntülenmek zorunda olmayan bir çocuk öğesinin yerleşimini etkileyen bir hayalet matematik nesnesi (<m:phant>) temsil eder. Bir hayalet, formülleri hizalamak veya alan ayırmak için genişliğini, yüksekliğini veya derinliğini korurken temel ifadesini gizleyebilir. Görünürlük ve geometrik davranış, Show, ZeroWid, ZeroAsc, ZeroDesc ve Transp gibi özelliklerle kontrol edilir.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // İçeriği gizle
>  phantom.setZeroWidth(false);     // Genişliği koru
```
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getBase()](#getBase--) | Temel argüman |
| [getShow()](#getShow--) | Temel öğenin görüntülenip görüntülenmediğini belirten bir değeri alır veya ayarlar. |
| [setShow(boolean value)](#setShow-boolean-) | Temel öğenin görüntülenip görüntülenmediğini belirten bir değeri alır veya ayarlar. |
| [getZeroWidth()](#getZeroWidth--) | Temel öğenin genişliğinin sıfır olarak ele alınması gerektiğini belirten bir değeri alır veya ayarlar. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Temel öğenin genişliğinin sıfır olarak ele alınması gerektiğini belirten bir değeri alır veya ayarlar. |
| [getZeroAsc()](#getZeroAsc--) | Temel öğenin yükselişinin (taban çizgisi üzerindeki yüksekliği) sıfır olarak ele alınması gerektiğini belirten bir değeri alır veya ayarlar. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Temel öğenin yükselişinin (taban çizgisi üzerindeki yüksekliği) sıfır olarak ele alınması gerektiğini belirten bir değeri alır veya ayarlar. |
| [getZeroDesc()](#getZeroDesc--) | Temel öğenin alçalmasının (taban çizgisinin altındaki derinlik) sıfır olarak ele alınması gerektiğini belirten bir değeri alır veya ayarlar. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Temel öğenin alçalmasının (taban çizgisinin altındaki derinlik) sıfır olarak ele alınması gerektiğini belirten bir değeri alır veya ayarlar. |
| [getTransp()](#getTransp--) | Hayaletin sınıf tabanlı boşluk kuralları için şeffaf olup olmadığını belirten bir değeri alır veya ayarlar. |
| [setTransp(boolean value)](#setTransp-boolean-) | Hayaletin sınıf tabanlı boşluk kuralları için şeffaf olup olmadığını belirten bir değeri alır veya ayarlar. |
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
> ```

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public abstract boolean getShow()
```

Temel öğenin görüntülenip görüntülenmediğini belirten bir değeri alır veya ayarlar.

--------------------

Yanlış olduğunda, temel öğe gizlenir ancak diğer hayalet ayarlarına bağlı olarak hâlâ alan kaplayabilir. OMML niteliği m:show ile eşdeğerdir.

**Döndürür:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```

Temel öğenin görüntülenip görüntülenmediğini belirten bir değeri alır veya ayarlar.

--------------------

Yanlış olduğunda, temel öğe gizlenir ancak diğer hayalet ayarlarına bağlı olarak hâlâ alan kaplayabilir. OMML niteliği m:show ile eşdeğerdir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```

Temel öğenin genişliğinin sıfır olarak ele alınması gerektiğini belirten bir değeri alır veya ayarlar.

--------------------

Doğru olduğunda, hayalet temel öğesi için yatay alan ayırmaz. OMML niteliği m:zeroWid ile eşdeğerdir.

**Döndürür:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```

Temel öğenin genişliğinin sıfır olarak ele alınması gerektiğini belirten bir değeri alır veya ayarlar.

--------------------

Doğru olduğunda, hayalet temel öğesi için yatay alan ayırmaz. OMML niteliği m:zeroWid ile eşdeğerdir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```

Temel öğenin yükselişinin (taban çizgisi üzerindeki yüksekliği) sıfır olarak ele alınması gerektiğini belirten bir değeri alır veya ayarlar.

--------------------

Doğru olduğunda, hayalet çevresindeki matematik satırının taban çizgisini yükseltmez. OMML niteliği m:zeroAsc ile eşdeğerdir.

**Döndürür:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```

Temel öğenin yükselişinin (taban çizgisi üzerindeki yüksekliği) sıfır olarak ele alınması gerektiğini belirten bir değeri alır veya ayarlar.

--------------------

Doğru olduğunda, hayalet çevresindeki matematik satırının taban çizgisini yükseltmez. OMML niteliği m:zeroAsc ile eşdeğerdir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```

Temel öğenin alçalmasının (taban çizgisinin altındaki derinlik) sıfır olarak ele alınması gerektiğini belirten bir değeri alır veya ayarlar.

--------------------

Doğru olduğunda, hayalet çevresindeki matematik satırının taban çizgisini alçaltmaz. OMML niteliği m:zeroDesc ile eşdeğerdir.

**Döndürür:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```

Temel öğenin alçalmasının (taban çizgisinin altındaki derinlik) sıfır olarak ele alınması gerektiğini belirten bir değeri alır veya ayarlar.

--------------------

Doğru olduğunda, hayalet çevresindeki matematik satırının taban çizgisini alçaltmaz. OMML niteliği m:zeroDesc ile eşdeğerdir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```

Hayaletin sınıf tabanlı boşluk kuralları için şeffaf olup olmadığını belirten bir değeri alır veya ayarlar.

--------------------

Doğru olduğunda, hayaletin içindeki operatörler ve semboller hâlâ hayaletin etrafındaki matematiksel boşluğu etkiler (görünürmüş gibi). Yanlış olduğunda, sınıf tabanlı boşluk yoksayılır. OMML niteliği m:transp ile eşdeğerdir.

**Döndürür:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)
```

Hayaletin sınıf tabanlı boşluk kuralları için şeffaf olup olmadığını belirten bir değeri alır veya ayarlar.

--------------------

Doğru olduğunda, hayaletin içindeki operatörler ve semboller hâlâ hayaletin etrafındaki matematiksel boşluğu etkiler (görünürmüş gibi). Yanlış olduğunda, sınıf tabanlı boşluk yoksayılır. OMML niteliği m:transp ile eşdeğerdir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |