---
title: HSL
second_title: Aspose.Slides for Java API Referansı
description: Hue/Saturation/Luminance etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/hsl/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IHSL](../../com.aspose.slides/ihsl), com.aspose.slides.IVisualEffect
```
public final class HSL extends ImageTransformOperation implements IHSL, IVisualEffect
```

Hue/Saturation/Luminance etkisini temsil eder. Hue, saturation ve luminance, mevcut değerlerine göre ayarlanabilir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEffective()](#getEffective--) | Etkilenmiş Hue/Saturation/Luminance etkisi verilerini, kalıtım uygulanmış şekilde alır. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [HSL](../../com.aspose.slides/hsl)'nin mevcut [HSL](../../com.aspose.slides/hsl) ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tür için hash işlevi olarak hizmet eder. |
### getEffective() {#getEffective--}
```
public final IHSLEffectiveData getEffective()
```


Etkilenmiş Hue/Saturation/Luminance etkisi verilerini, kalıtım uygulanmış şekilde alır.

**Döndürür:**
[IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata) - Bir [IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen [HSL](../../com.aspose.slides/hsl)'nin mevcut [HSL](../../com.aspose.slides/hsl) ile eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak [HSL](../../com.aspose.slides/hsl). |

**Döndürür:**
boolean - nesneler eşitse true; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Belirli bir tür için hash işlevi olarak hizmet eder.

**Döndürür:**
int - Geçerli nesne için bir hash kodu.