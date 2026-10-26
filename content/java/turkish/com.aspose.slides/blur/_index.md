---
title: Blur
second_title: Aspose.Slides for Java API Referansı
description: Bulanıklık etkisini, doldurulması dahil olmak üzere tüm şekle uygulayan bir Blur etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/blur/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect
```
public final class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

Tam şekle, doldurulmasını da dahil ederek uygulanmış bir Blur etkisini temsil eder. Alfa kanalı dahil tüm renk kanalları etkilenir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRadius()](#getRadius--) | Bulanıklık yarıçapını döndürür veya ayarlar. |
| [setRadius(double value)](#setRadius-double-) | Bulanıklık yarıçapını döndürür veya ayarlar. |
| [getGrow()](#getGrow--) | Nesnenin sınırlarının bulanıklaştırma sonucunda büyütülüp büyütülmeyeceğini belirler. |
| [setGrow(boolean value)](#setGrow-boolean-) | Nesnenin sınırlarının bulanıklaştırma sonucunda büyütülüp büyütülmeyeceğini belirler. |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili Blur etki verisini alır. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [Blur](../../com.aspose.slides/blur) geçerli [Blur](../../com.aspose.slides/blur) ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tür için hash işlevi sağlar. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

Bulanıklık yarıçapını döndürür veya ayarlar. Okunabilir/Yazılabilir double.

**Döndürür:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Bulanıklık yarıçapını döndürür veya ayarlar. Okunabilir/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getGrow() {#getGrow--}
```
public final boolean getGrow()
```

Nesnenin sınırlarının bulanıklaştırma sonucunda büyütülüp büyütülmeyeceğini belirler. True, sınırların büyütüldüğünü, false ise büyütülmediğini gösterir. Okunabilir/Yazılabilir boolean.

**Döndürür:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```

Nesnenin sınırlarının bulanıklaştırma sonucunda büyütülüp büyütülmeyeceğini belirler. True, sınırların büyütüldüğünü, false ise büyütülmediğini gösterir. Okunabilir/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```

Kalıtım uygulanmış etkili Blur etki verisini alır.

**Döndürür:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - Bir [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Belirtilen [Blur](../../com.aspose.slides/blur) geçerli [Blur](../../com.aspose.slides/blur) ile eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak [Blur](../../com.aspose.slides/blur). |

**Döndürür:**
boolean - nesneler eşitse true; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Belirli bir tür için hash işlevi sağlar.

**Döndürür:**
int - Geçerli nesne için bir hash kodu.