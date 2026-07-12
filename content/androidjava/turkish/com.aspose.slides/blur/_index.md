---
title: Blur
second_title: Aspose.Slides for Android, Java API Referansı aracılığıyla
description: Dolgu dahil tüm şekle uygulanan bir Blur etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/blur/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect
```
public final class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

Tam şekle, dolgu dahil, uygulanan bir Blur (Bulanıklaştırma) etkisini temsil eder. Alfa kanalı dahil olmak üzere tüm renk kanalları etkilenir.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRadius()](#getRadius--) | Bulanıklaştırma yarıçapını döndürür veya ayarlar. |
| [setRadius(double value)](#setRadius-double-) | Bulanıklaştırma yarıçapını döndürür veya ayarlar. |
| [getGrow()](#getGrow--) | Nesnenin sınırlarının, bulanıklaştırma sonucu büyütülüp büyütülmeyeceğini belirler. |
| [setGrow(boolean value)](#setGrow-boolean-) | Nesnenin sınırlarının, bulanıklaştırma sonucu büyütülüp büyütülmeyeceğini belirler. |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili Blur (Bulanıklaştırma) efekt verilerini alır. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [Blur](../../com.aspose.slides/blur) mevcut [Blur](../../com.aspose.slides/blur) ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tür için hash işlevi olarak hizmet eder. |

### getRadius() {#getRadius--}
```
public final double getRadius()
```

Bulanıklaştırma yarıçapını döndürür veya ayarlar. Okunur/Yazılır double.

**Dönüş:**
double

### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Bulanıklaştırma yarıçapını döndürür veya ayarlar. Okunur/Yazılır double.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public final boolean getGrow()
```

Nesnenin sınırlarının, bulanıklaştırma sonucu büyütülüp büyütülmeyeceğini belirler. True, sınırların büyütüldüğünü, false ise büyütülmediğini gösterir. Okunur/Yazılır boolean.

**Dönüş:**
boolean

### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```

Nesnenin sınırlarının, bulanıklaştırma sonucu büyütülüp büyütülmeyeceğini belirler. True, sınırların büyütüldüğünü, false ise büyütülmediğini gösterir. Okunur/Yazılır boolean.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```

Kalıtım uygulanmış etkili Blur (Bulanıklaştırma) veri setini alır.

**Dönüş:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - A [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Belirtilen [Blur](../../com.aspose.slides/blur) mevcut [Blur](../../com.aspose.slides/blur) ile eşit olup olmadığını belirler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak [Blur](../../com.aspose.slides/blur). |

**Dönüş:**
boolean - true if objects are equal; otherwise, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Belirli bir tür için hash işlevi olarak hizmet eder.

**Dönüş:**
int - A hash code for the current object.